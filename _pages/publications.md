---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

심사 중인 논문들을 위한 Under Review 섹션도 추가했습니다!

기호는 깔끔하게 [UR1], [UR2] 형태로 나오도록 세팅했고, 다른 섹션들과 마찬가지로 올 블랙 컬러에 정렬이 딱 맞게 적용됩니다.

아래 코드를 통째로 복사해서 사용하시면 됩니다.

HTML
<strong>Journal Papers</strong>
<hr>
<ul class="pub-list journal">
  <li><div>저널 논문 제목 내용이 들어갑니다. (2026)</div></li>
  <li><div>저널 논문 제목 내용이 들어갑니다. (2025)</div></li>
</ul>

<br>

<strong>Conference Papers</strong>
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

<br>

<strong>Under Review</strong>
<hr>
<ul class="pub-list under-review">
  <li><div>심사 중인 첫 번째 논문 제목 내용이 들어갑니다.</div></li>
  <li><div>심사 중인 두 번째 논문 제목 내용이 들어갑니다.</div></li>
</ul>


<style>
  /* 공통 스타일 초기화 */
  .pub-list {
    list-style: none;
    padding-left: 0;
    margin-left: 0;
    margin-top: 15px;
    color: #333333;      /* 전체 본문 글자 색상 (검은색) */
  }
  
  /* 가로 배치 및 정렬 설정 */
  .pub-list li {
    display: flex;
    align-items: flex-start;
    margin-bottom: 12px;
    line-height: 1.6;
  }
  
  /* 본문 텍스트 영역 */
  .pub-list li div {
    flex: 1;
  }

  /* 기호([J1], [UR1] 등) 공통 설정 */
  .pub-list li::before {
    font-weight: bold;   /* 기호 볼드 처리 */
    color: #333333;      /* 기호 검은색 통일 */
    display: inline-block;
    width: 55px;         /* UR은 글자가 3자라 너비를 55px로 살짝 넓혔습니다 */
    flex-shrink: 0;      
  }

  /* 1. 저널 설정 */
  .journal { counter-reset: j-idx; }
  .journal li { counter-increment: j-idx; }
  .journal li::before { content: "[J" counter(j-idx) "] "; }

  /* 2. 학회 설정 */
  .conference { counter-reset: c-idx; }
  .conference li { counter-increment: c-idx; }
  .conference li::before { content: "[C" counter(c-idx) "] "; }

  /* 3. 북 챕터 설정 */
  .book { counter-reset: b-idx; }
  .book li { counter-increment: b-idx; }
  .book li::before { content: "[B" counter(b-idx) "] "; }

  /* 4. Under Review 설정 */
  .under-review { counter-reset: ur-idx; }
  .under-review li { counter-increment: ur-idx; }
  .under-review li::before { content: "[UR" counter(ur-idx) "] "; }
</style>



