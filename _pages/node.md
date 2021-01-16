---
layout: page-w-banner
title: 레이븐코인
description: "레이븐코인은 효율적인 자산 생성 및 전송을 위한 피어투피어 블록체인이며, 비트코인 코드를 포크한 오픈소스 프로젝트입니다."
bannerTitle: 레이븐코인
bannerImage: /assets/img/pages/about/about-banner.jpg
permalink: /node/
---
#!/usr/bin/env python
# -*- coding: utf-8 -*-
#
# ravennodes.py - Ravennodes website
#
# By Jeroz Feb, 2019
#
# Permission is hereby granted, free of charge, to any person obtaining
# a copy of this software and associated documentation files (the
# "Software"), to deal in the Software without restriction, including
# without limitation the rights to use, copy, modify, merge, publish,
# distribute, sublicense, and/or sell copies of the Software, and to
# permit persons to whom the Software is furnished to do so, subject to
# the following conditions:
#
# The above copyright notice and this permission notice shall be
# included in all copies or substantial portions of the Software.
#
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
# EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
# MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
# NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
# LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
# OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
# WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Import Modules
import pandas as pd
from flask import Flask, render_template

"""
Read generated tables
"""

dfnodes = pd.read_csv("tables/all_nodes.csv")
dfcountry = pd.read_csv("tables/country_frequency.csv")
dfisp = pd.read_csv("tables/ISP_frequency.csv")
dfversion = pd.read_csv("tables/version_frequency.csv")
dfcount = pd.read_csv("tables/node_count.csv")
last_update = dfcount['Date'].astype('str').iloc[-1] + ' GMT'

# Build Ravennodes website
ravennodes = Flask(__name__)

@ravennodes.route('/')
def home():
    """
    Home Page
    """
    return render_template('home.html', data=len(dfnodes),
                           json_time=last_update,
                           tables=[dfcountry.to_html(classes='table',index=False)])

# Build 24h Stats page
@ravennodes.route('/stats/')
def stats():
    """
    Nodes Page
    """
    return render_template('stats.html', tables=[dfcountry.to_html(classes='table',index=False),
                                                 dfisp.to_html(classes='table',index=False),
                                                 dfversion.to_html(classes='table',index=False),
                                                 ])


# Build Nodes page
@ravennodes.route('/nodes/')
def nodes():
    """
    Nodes Page
    """
    return render_template('nodes.html', tables=[dfnodes.to_html(classes='table',index=False)])


# Build Worldmap page
@ravennodes.route('/worldmap/')
def worldmap():
    """
    World Map page
    """
    return render_template('worldmap.html')


if __name__ == '__main__':
    ravennodes.jinja_env.auto_reload = True
    ravennodes.config['TEMPLATES_AUTO_RELOAD'] = True
    ravennodes.run(debug=False)
