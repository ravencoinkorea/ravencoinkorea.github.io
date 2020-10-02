---
layout: page-w-banner
title: 채굴풀
bannerTitle: 채굴풀
permalink: /pools/
---

<div class="page-content">
  <div class="wrapper mt-8 mb-32 m-auto">
    <h2>레이븐코인 채굴</h2>
    <br>
    <p>소비자용 하드웨어에서 채굴되도록 설계된 레이븐코인은 카포(KAWPOW)라는 새로운 알고리즘을 사용합니다. </p><p style="margin-top:20px"></p>고효율성 반도체 채굴기(ASIC)에 내성을 갖도록 설계되었으며, GPU 하드웨어를 통해 효율적으로 채굴할 수 있도록 설계되었습니다.</p><p style="margin-top:20px"></p>
    채굴 전 지갑을 만든 후, 채굴된 레이븐코인을 받을 주소를 생성해야 합니다. </p><p style="margin-top:20px"></p>
    그리고 채굴풀을 선택하여, 채굴을 시작합니다.<p style="margin-top:30px"></p>
    <p>채굴 가이드(영문): <a href="https://raven.wiki/wiki/Mining" target="_blank" rel="noopener">https://raven.wiki/wiki/Mining</a></p><p style="margin-top:30px"></p>
    <p class="mb-8">이하 레이븐코인 채굴풀입니다:</p>
    <div class="flex flex-wrap">
      {% for exchange in site.data.pools %}
      <div class="mb-6 px-2 sm:w-1/2 md:w-1/3 text-center">
        <div class="bg-grey-lighter max-w-sm rounded overflow-hidden shadow-md hover:by-grey">
          <!-- <a class="block px-6 py-8" href="{{ exchange.url }}" target="_blank"><img src="{{ exchange.logo }}" alt="{{ exchange.name }} exchange"/></a> -->
          <h3 class="px-2 py-6 mb-0"><a class="block p-4" href="{{ exchange.url }}" target="_blank">{{ exchange.name }}</a></h3>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</div>
