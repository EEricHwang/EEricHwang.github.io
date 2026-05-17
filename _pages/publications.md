---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<hr>

<!-- 타이틀 및 구분선 -->
<strong>Journal Papers</strong>
<hr>

<!-- 저널 리스트 시작 -->
<ul class="journal-list">
  <li><strong>"A Deep Learning Approach to Computer Vision"</strong>, IEEE Transactions on Pattern Analysis, 2026.</li>
</ul>

<strong>Conference Proceedings</strong>
<hr>

<strong>Book Chapter</strong>
<hr>

<!-- 스타일 정의 (CSS) -->
<style>
  /* 리스트 전체 스타일 지정 */
  .journal-list {
    list-style: none;             /* 1. 기본 점(블릿) 제거 */
    padding-left: 0;              /* 2. 왼쪽 기본 여백 제거 */
    counter-reset: journal-idx;   /* 3. [J1], [J2] 숫자를 세기 위한 카운터 시작 */
    margin-top: 15px;             /* 4. <hr> 선과의 간격 */
  }

  /* 리스트 각 항목(줄) 스타일 */
  .journal-list li {
    counter-increment: journal-idx;  /* li를 만날 때마다 숫자 +1 */
    margin-bottom: 12px;             /* 항목 간의 아래 간격 */
    line-height: 1.6;                /* 줄간격 */
    
    /* [긴 논문 제목이 줄바꿈 되어도 정렬이 깨지지 않게 해주는 핵심 설정] */
    padding-left: 45px;              /* 왼쪽 여백을 넓혀서 본문 시작점 맞춤 */
    text-indent: -45px;              /* 첫 줄([J1])만 왼쪽으로 당김 */
  }

  /* 각 항목 앞에 [J1], [J2] 자동으로 붙이기 */
  .journal-list li::before {
    content: "[J" counter(journal-idx) "] ";  /* 기호 형태 정의 */
    font-weight: bold;                         /* [J1] 기호만 볼드체 적용 */
    color: #0066cc;                            /* 기호 색상 (원하는 색상 코드로 변경 가능) */
    display: inline-block;
    width: 45px;                               /* 기호가 차지할 고정 너비 */
  }
</style>



