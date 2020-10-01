---
layout: page-w-banner
title: 레이븐코인 거래
bannerTitle: 레이븐코인 거래 가이드
bannerImage: /assets/img/pages/exchanges/exchange-banner.jpg
permalink: /buy-ravencoin/
---

<div class="page-content">
  <div class="wrapper mt-8 mb-32 m-auto">
    <h2>레이븐코인 거래</h2>
    <p class="mb-8">레이븐코인(RVN)은 이하 거래소에서 거래 가능합니다:</p>
    <div class="flex flex-wrap">
      {% for exchange in site.data.exchanges %}
      <div class="mb-6 px-2 sm:w-1/2 md:w-1/3 text-center">
        <div class="bg-grey-lighter max-w-sm rounded overflow-hidden shadow-md hover:by-grey">
          <a class="block px-6 py-8" href="{{ exchange.url }}" target="_blank"><img src="{{ exchange.logo }}" alt="{{ exchange.name }} exchange"/></a>
        </div>
        <h3 class="mt-6"><a href="{{ exchange.url }}" target="_blank">{{ exchange.name }}</a></h3>
      </div>
      {% endfor %}
    </div>
  </div>
</div>
