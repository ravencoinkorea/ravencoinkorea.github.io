---
layout: page-w-banner
title: 채굴풀
bannerTitle: 채굴풀
permalink: /pools/
---

<div class="page-content">
  <div class="wrapper mt-8 mb-32 m-auto">
    <h2>레이븐코인 채굴 방법</h2>
    <p>레이븐코인은 소비자용 하드웨어(GPU&CPU)로 쉽게 채굴할 수 있도록 설계된 X16R 알고리즘을 사용합니다. X16R 알고리즘은은 블록 생성간 16개의 다른 알고리즘들의 지속적인 전환을 통하여, 주문형 반도체(ASIC) 하드웨어 저항하도록 설계 되었습니다.</p>
    <p>레이븐코인을 채굴하기 위해서는, 지갑을 만들고, 채굴된 레이븐코인을 받을 레이븐코인 주소를 생성하여야 합니다. 그리고, 채굴풀을 선택하여, 채굴을 시작할 수 있습니다.</p>
    <p>To learn how to mine, visit: <a href="https://raven.wiki/wiki/Mining" target="_blank" rel="noopener">https://raven.wiki/wiki/Mining</a></p>
    <p class="mb-8">Ravencoin (RVN) is supported by the following mining pools:</p>
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
