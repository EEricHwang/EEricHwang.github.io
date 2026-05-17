---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

<strong>Journal Papers</strong>
<hr>
<ul class="pub-list journal">
  <li><div>저널 논문 제목 내용이 들어갑니다. 아주 길어져서 줄바꿈이 되더라도 이제 정렬이 깨지지 않고 깔끔하게 유지됩니다. (2026)</div></li>
  <li><div>저널 논문 제목 내용이 들어갑니다. (2025)</div></li>
</ul>

<br>

<strong>Conference Proceedings</strong>
<hr>
<ul class="pub-list conference">
  <li><div>학회 논문 제목 내용이 들어갑니다. (2026)</div></li>
</ul>

<br>

<strong>Book Chapters</strong>
<hr>
<ul class="pub-list book">
  <li><div>북 챕터 제목 내용이 들어갑니다. (2024)</div></li>
</ul>


<style>
  /* 공통 스타일 초기화 */
  .pub-list {
    list-style: none;
    padding-left: 0;
    margin-left: 0;   /* 외부 여백 초기화 */
    margin-top: 15px;
  }
  
  /* Flexbox를 사용하여 [J1]과 본문을 가로로 예쁘게 배치 */
  .pub-list li {
    display: flex;
    align-items: flex-start; /* 줄이 길어져도 위쪽 기준으로 정렬 */
    margin-bottom: 12px;
    line-height: 1.6;
  }
  
  /* 본문 텍스트 영역 */
  .pub-list li div {
    flex: 1; /* 남은 가로 공간을 모두 차지하도록 설정 */
  }

  /* 기호([J1], [C1] 등) 공통 설정 */
  .pub-list li::before {
    font-weight: bold;
    display: inline-block;
    width: 45px;        /* 기호가 차지할 고정 너비 */
    flex-shrink: 0;     /* 화면이 작아져도 기호 너비가 줄어들지 않도록 고정 */
  }

  /* 1. 저널 설정 */
  .journal { counter-reset: j-idx; }
  .journal li { counter-increment: j-idx; }
  .journal li::before { 
    content: "[J" counter(j-idx) "] "; 
    color: #333333; 
  }

  /* 2. 학회 설정 */
  .conference { counter-reset: c-idx; }
  .conference li { counter-increment: c-idx; }
  .conference li::before { 
    content: "[C" counter(c-idx) "] "; 
    color: #333333; 
  }

  /* 3. 북 챕터 설정 */
  .book { counter-reset: b-idx; }
  .book li { counter-increment: b-idx; }
  .book li::before { 
    content: "[B" counter(b-idx) "] "; 
    color: #333333; 
  }
</style>



