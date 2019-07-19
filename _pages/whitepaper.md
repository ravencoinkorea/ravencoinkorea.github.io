---
layout: page-w-banner
title: 백서
bannerTitle: 백서
bannerImage: /assets/img/pages/whitepaper/whitepaper-banner.jpg
permalink: /whitepaper/
---

<div class="page-content">
  <div class="wrapper">
    <h2 id="intro" class="text-center">레이븐코인에 대해 알고, 함께 참여해 주시길 바랍니다</h2>
    <p id="pub" class="text-center">백서 작성자 <a href="https://www.linkedin.com/in/brucefenton/" target="_blank">브루스 펜튼</a>, <a href="https://www.linkedin.com/in/tron-black-90287/" target="_blank">트론 블랙</a>, <a href="https://www.linkedin.com/in/joelweight/" target="_blank">조엘 웨이트</a>.</p>
    <p class="text-center">원하시는 다른 국가의 번역본은 이하 국기를 클릭해 주시길 바랍니다.  
    <p class="text-center"><button id="English" onClick="changeTextEnglish()"><img src="/assets/img/pages/whitepaper/English.png" /></button> <button id="German" onClick="changeTextGerman()"><img src="/assets/img/pages/whitepaper/German.png" /></button>
    <div class="flex flex-wrap text-center pt-20 pb-32 m-auto" style="max-width: 700px;">
      <!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ White Paper ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
      <div class="w-full sm:w-1/2 mb-8">
        <a id="whitePaper0" href="/assets/documents/Ravencoin WhitepaperKorean V.1.0.pdf" target="_blank">
          <div class="mb-6 py-4 px-6 inline-block rounded-full bg-grey hover:bg-grey-dark">
            <i class="zmdi zmdi-file-text text-5xl text-white"></i>
          </div>
        </a>
        <h3><a id="whitePaper1" href="/assets/documents/Ravencoin WhitepaperKorean V.1.0.pdf" target="_blank">백서</a></h3>
        <p id="whitePaper2">레이븐코인: 디지털 자산 생성 및 전송을 위한<p></p> 피어투피어(P2P) 전자 지스템</p>

      </div>
      <!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ X16R ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
      <div class="w-full sm:w-1/2 mb-8">
        <a id="x16r0" href="/assets/documents/X16R Whitepaper Korean V.1.0.pdf" target="_blank">
          <div class="mb-6 py-4 px-6 inline-block rounded-full bg-grey hover:bg-grey-dark">
            <i class="zmdi zmdi-file-text text-5xl text-white"></i>
          </div>
        </a>
        <h3><a id="x16r1" href="/assets/documents/X16R Whitepaper Korean V.1.0.pdf" target="_blank">X16R 알고리즘</a></h3>
        <p id="x16r2">X16R: ASIC 저항을 위해 디자인된 알고리즘</p>
      </div>
      <!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ Road Map ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

      <div class="w-full sm:w-1/2 mb-8">
        <a id="roadMap0" href="https://github.com/RavenProject/Ravencoin/tree/master/roadmap" target="_blank">
          <div class="mb-6 py-4 px-6 inline-block rounded-full bg-grey hover:bg-grey-dark">
            <i class="zmdi zmdi-map text-5xl text-white"></i>
          </div>
        </a>
        <h3><a id="roadMap1" href="https://github.com/RavenProject/Ravencoin/tree/master/roadmap" target="_blank">로드맵(번역 준비중)</a></h3>
        <p id="roadMap2">개발 로드맵


<script>
  function changeTextEnglish()
  {
    document.getElementById('intro').innerHTML = 'Be Informed, Stay Involved';
    document.getElementById('pub').innerHTML = 'Documents published by <a href="https://www.linkedin.com/in/brucefenton/" target="_blank">Bruce Fenton</a>, <a href="https://www.linkedin.com/in/tron-black-90287/" target="_blank">Tron Black</a>, and <a href="https://www.linkedin.com/in/joelweight/" target="_blank">Joel Weight</a>.';
    <!-- White Paper -->
    document.getElementById('whitePaper0').href = "/assets/documents/Ravencoin.pdf";
    document.getElementById('whitePaper1').innerHTML = 'White paper';
    document.getElementById('whitePaper1').href = "/assets/documents/Ravencoin.pdf";
    document.getElementById('whitePaper2').innerHTML = 'Ravencoin: A Peer to Peer Electronic System for the Creation and Transfer of Assets';
    document.getElementById('whitePaper2').innerHTML = 'Ravencoin: A Peer to Peer Electronic System for the Creation and Transfer of Assets';
    <!-- X16R -->
    document.getElementById('x16r0').href = "/assets/documents/X16R-Whitepaper.pdf";
    document.getElementById('x16r1').innerHTML = 'X16R algorithm paper';
    document.getElementById('x16r1').href = "/assets/documents/X16R-Whitepaper.pdf";
    document.getElementById('x16r2').innerHTML = 'X16R: ASIC Resistant by Design';
    <!-- Road Map -->
    document.getElementById('roadMap0').href = "https://github.com/RavenProject/Ravencoin/tree/master/roadmap";
    document.getElementById('roadMap1').innerHTML = 'Development roadmap';
    document.getElementById('roadMap1').href = "https://github.com/RavenProject/Ravencoin/tree/master/roadmap";
    document.getElementById('roadMap2').innerHTML = 'Development roadmap';
    <!-- Road Map MD -->
    document.getElementById('roadMapMD').href = "https://github.com/RavenProject/Ravencoin/tree/master/roadmap";
    document.getElementById('roadMapMD').innerHTML = 'Development roadmap';
    document.getElementById('roadMapMD4').href = "https://github.com/RavenProject/Ravencoin/tree/master/roadmap";
    document.getElementById('roadMapMD4').innerHTML = 'Development roadmap';
  }
  function changeTextGerman()
  {
    document.getElementById('intro').innerHTML = 'Seien Sie Informiert, Bleiben Sie Dabei';
    document.getElementById('pub').innerHTML = 'Von <a href="https://www.linkedin.com/in/brucefenton/" target="_blank">Bruce Fenton</a>, <a href="https://www.linkedin.com/in/tron-black-90287/" target="_blank">Tron Black</a>, und <a href="https://www.linkedin.com/in/joelweight/" target="_blank">Joel Weight</a> veröffentlichte Dokumente..';
    <!-- White Paper -->
    document.getElementById('whitePaper0').href = "/assets/documents/Ravencoin.German.pdf";
    document.getElementById('whitePaper1').innerHTML = 'Weißbuch';
    document.getElementById('whitePaper1').href = "/assets/documents/Ravencoin.German.pdf";
    document.getElementById('whitePaper2').innerHTML = 'Ravencoin: Ein elektronisches Peer-to-Peer-System für die Erstellung und Übertragung von Assets';
    <!-- X16R -->
    document.getElementById('x16r0').href = "/assets/documents/X16R-Whitepaper.German.pdf";
    document.getElementById('x16r1').innerHTML = 'X16R Algorithmusentwurf';
    document.getElementById('x16r1').href = "/assets/documents/X16R-Whitepaper.German.pdf";
    document.getElementById('x16r2').innerHTML = 'X16R: AASIC-beständig durch Design';
    <!-- Road Map -->
    document.getElementById('roadMap0').href = "/assets/documents/Roadmap.German.pdf";
    document.getElementById('roadMap1').innerHTML = 'Ravencoin Fahrplan';
    document.getElementById('roadMap1').href = "/assets/documents/Roadmap.German.pdf";
    document.getElementById('roadMap2').innerHTML = 'Ravencoin Fahrplan';
   <!-- Road Map MD -->
   document.getElementById('roadMapMD').style.visibility = "hidden";
  }
  function changeTextKorean()
  {
    document.getElementById('intro').innerHTML = 'Be Informed, Stay Involved';
    document.getElementById('pub').innerHTML = 'Documents published by <a href="https://www.linkedin.com/in/brucefenton/" target="_blank">Bruce Fenton</a>, <a href="https://www.linkedin.com/in/tron-black-90287/" target="_blank">Tron Black</a>, and <a href="https://www.linkedin.com/in/joelweight/" target="_blank">Joel Weight</a>.';
    <!-- White Paper -->
    document.getElementById('whitePaper0').href = "/assets/documents/Ravencoin.pdf";
    document.getElementById('whitePaper1').innerHTML = 'White paper';
    document.getElementById('whitePaper1').href = "/assets/documents/Ravencoin.pdf";
    document.getElementById('whitePaper2').innerHTML = 'Ravencoin: A Peer to Peer Electronic System for the Creation and Transfer of Assets';
    <!-- X16R -->
    document.getElementById('x16r0').href = "/assets/documents/X16R-Whitepaper.pdf";
    document.getElementById('x16r1').innerHTML = 'X16R algorithm paper';
    document.getElementById('x16r1').href = "/assets/documents/X16R-Whitepaper.pdf";
    document.getElementById('x16r2').innerHTML = 'X16R: ASIC Resistant by Design';
    <!-- Road Map -->
    document.getElementById('roadMap0').href = "https://github.com/RavenProject/Ravencoin/tree/master/roadmap";
    document.getElementById('roadMap1').innerHTML = 'Development roadmap';
    document.getElementById('roadMap1').href = "https://github.com/RavenProject/Ravencoin/tree/master/roadmap";
    document.getElementById('roadMap2').innerHTML = 'Development roadmap';
    <!-- Road Map MD -->
    document.getElementById('roadMapMD').style.visibility = "visible";
  }
</script>
