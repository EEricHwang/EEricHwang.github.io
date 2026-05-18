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
  <li><div>저널 논문 제목 내용이 들어갑니다. (2026)</div></li>
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
  <li><div>
    <span style="text-decoration: underline;"><strong>S. Hwang*</strong></span>, G. Wu, M. Cho, and I. Hwang,
    "Energy-Aware Consensus Control for Multi-Agent Systems with Guaranteed Battery Safety via H-Infinity LMI Design,"
    <em>IEEE Control Systems Letters (L-CSS)</em>, Submitted in May 2026.
  </div></li>

  <li><div>
    <span style="text-decoration: underline;"><strong>S. Hwang*</strong></span>, M. Cho, G. Wu, and I. Hwang,
    "Cooperative Constrained Control of Multi-Agent Systems with Rate-Limited Actuators: An LMI-Based Approach,"
    <em>65th IEEE Conference on Decision and Control (CDC)</em>, Submitted in March 2026.
  </div></li>

  <li><div>
    <span style="text-decoration: underline;"><strong>S. Hwang*</strong></span>, G. Wu, M. Cho, and I. Hwang,
    "Koopman-Based State-of-Charge Observer Design for Lithium-Ion Batteries: An LMI-Based Framework,"
    <em>ASME Letters in Dynamic Systems and Control</em>, Submitted in March 2026.
  </div></li>

  <li><div>
    G. Wu, <span style="text-decoration: underline;"><strong>S. Hwang*</strong></span>, Z. Chen, and I. Hwang,
    "Deep Koopman-Style Framework for Cross-Temperature State-of-Charge Estimation of Lithium-Ion Batteries,"
    <em>2026 Modeling, Estimation and Control Conference (MECC)</em>, Submitted in March 2026.
  </div></li>


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



