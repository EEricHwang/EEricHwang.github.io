---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- Replace the entire _pages/about.md file with this content. -->
<style>
/* Self-contained About Me styles. */

.about-page { --about-accent: #17675f; --about-ink: #253b40; --about-muted: #58666a; }
.about-page, .about-page * { box-sizing: border-box; }
.about-page a { color: var(--about-accent); text-underline-offset: .18em; }
.about-page a:focus-visible, .about-page summary:focus-visible { outline: 3px solid var(--about-accent); outline-offset: 4px; border-radius: 3px; }
.about-page .about-bio { margin: 0 0 .8rem; font-size: .91em; line-height: 1.75; }
.about-page .about-lead { margin: 0 0 1rem; color: var(--about-ink); font-size: 1.1em; line-height: 1.65; }
.about-actions { display: flex; flex-wrap: wrap; align-items: center; gap: .4rem 1.25rem; }
.about-actions a { display: inline-flex; align-items: center; gap: .45rem; min-height: 44px; font-size: .8em; font-weight: 600; }
.about-page .about-cv { padding: .45rem 1.1rem; border: 1px solid var(--about-accent); border-radius: 4px; color: #fff; background: var(--about-accent); text-decoration: none; }
.about-page .about-cv:hover { background: #114e48; border-color: #114e48; }
.about-page .about-cv-note { margin: .5rem 0 0; color: var(--about-muted); font-size: .67em; line-height: 1.5; }
.about-section { margin-top: 1.75rem; padding-top: 1.3rem; border-top: 1px solid #dce3e2; }
.about-page .about-section-title { margin: 0 0 1rem; padding: 0; border: 0; color: var(--about-ink); font-size: 1.1em; line-height: 1.4; }
.about-themes { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1rem; }
.about-page .about-theme { display: block; min-width: 0; color: var(--about-ink); text-decoration: none; border: 1px solid #e1e8e5; border-radius: 5px; padding: .7rem .65rem .75rem; background: #fff; }
.about-page .about-theme:hover { border-color: var(--about-accent); }
.about-page .about-theme img { display: block; width: 100%; height: 115px; object-fit: contain; margin: 0 0 .6rem; border: 0; border-radius: 0; box-shadow: none; }
.about-page .about-theme:hover img { box-shadow: none; }
.about-theme-title { display: block; color: var(--about-accent); font-size: .78em; line-height: 1.5; font-weight: 700; }
.about-theme-detail { display: block; margin-top: .2rem; color: var(--about-muted); font-size: .66em; line-height: 1.5; }
.about-research-map { margin-top: .65rem; }
.about-research-map > summary { width: fit-content; max-width: 100%; min-height: 40px; padding: .5rem 0; color: var(--about-accent); cursor: pointer; font-size: .72em; }
.about-research-map img { display: block; width: 100%; max-width: 720px; height: auto; margin: .7rem auto; }
.about-page .about-highlights { list-style: none; padding: 0; margin: 0; }
.about-page .about-highlight { display: grid; grid-template-columns: 8rem minmax(0, 1fr); gap: 1rem; margin: 0; padding: .75rem 0; }
.about-highlight + .about-highlight { border-top: 1px solid #edf0ef; }
.about-highlight-label { color: var(--about-accent); font-size: .72em; font-weight: 700; line-height: 1.7; }
.about-page .about-highlight p { margin: 0; color: var(--about-ink); font-size: .82em; line-height: 1.7; }
.about-page .about-news-list { list-style: none; margin: 0; padding: 0; }
.about-page .about-news-item { display: grid; grid-template-columns: 7.4rem minmax(0, 1fr); gap: 1rem; margin: 0; padding: 1rem 0; border-top: 1px solid #e5eae8; }
.about-news-list > .about-news-item:first-child { border-top: 0; padding-top: .2rem; }
.about-news-meta { min-width: 0; padding-top: .1rem; }
.about-news-date { display: block; color: var(--about-ink); font-size: .73em; line-height: 1.6; font-weight: 600; font-variant-numeric: tabular-nums; }
.about-news-category { display: block; color: var(--about-muted); font-size: .64em; line-height: 1.6; margin-top: .2rem; }
.about-page .about-news-body { margin: 0; font-size: .8em; line-height: 1.75; overflow-wrap: anywhere; }
.about-news-body strong { font-weight: 600; }
.about-news-archive { margin-top: .6rem; border-top: 1px solid #dce3e2; }
.about-news-archive > summary { width: fit-content; max-width: 100%; min-height: 44px; padding: .85rem 0; color: var(--about-accent); font-size: .8em; font-weight: 600; cursor: pointer; }
.about-news-archive[open] > summary { margin-bottom: .4rem; }
@media (max-width: 700px) {
  .about-page .about-bio { font-size: .95em; }
  .about-page .about-lead { font-size: 1.07em; }
  .about-actions { gap: .35rem 1rem; }
  .about-actions a { font-size: .85em; }
  .about-page .about-cv-note { font-size: .73em; }
  .about-section { margin-top: 1.4rem; padding-top: 1.2rem; }
  .about-themes { grid-template-columns: minmax(0, 1fr); gap: .65rem; }
  .about-page .about-theme { display: grid; grid-template-columns: 94px minmax(0, 1fr); gap: .9rem; align-items: center; padding: .65rem; }
  .about-page .about-theme img { height: 75px; margin: 0; }
  .about-theme-title { font-size: .86em; }
  .about-theme-detail { font-size: .76em; }
  .about-research-map > summary { font-size: .8em; min-height: 44px; }
  .about-page .about-highlight { grid-template-columns: minmax(0, 1fr); gap: .2rem; padding: .8rem 0; }
  .about-highlight-label { font-size: .78em; }
  .about-page .about-highlight p { font-size: .88em; }
  .about-page .about-news-item { grid-template-columns: minmax(0, 1fr); gap: .35rem; }
  .about-news-meta { display: flex; flex-wrap: wrap; align-items: baseline; gap: .3rem .8rem; }
  .about-news-date { font-size: .82em; }
  .about-news-category { font-size: .73em; margin: 0; }
  .about-page .about-news-body { font-size: .88em; }
  .about-news-archive > summary { font-size: .88em; }
}
@media (max-width: 360px) {
  .about-page .about-theme { grid-template-columns: 76px minmax(0, 1fr); gap: .65rem; }
  .about-page .about-theme img { height: 68px; }
}
@media print { .about-theme, .about-highlight, .about-news-item { break-inside: avoid; } }

</style>

<div class="about-page">
  <div class="about-intro">
    <p class="about-bio">I am a Ph.D. candidate in the <a href="https://engineering.purdue.edu/AAE">School of Aeronautics and Astronautics at Purdue University</a>, advised by Dr. Inseok Hwang.</p>
    <p class="about-lead">I develop control and estimation methods that help autonomous systems operate safely under cyberattacks, uncertainty, and limited energy resources.</p>
    <nav class="about-actions" aria-label="Profile resources">
      <a class="about-cv" href="https://drive.google.com/file/d/1KfoiL3WSCRDaNayPMSjwQfOM4LnIjxmh/view?usp=drive_link" target="_blank" rel="noopener noreferrer" aria-label="View CV (new tab)">View CV <span aria-hidden="true">↗</span></a>
      <a href="/research/">Research <span aria-hidden="true">→</span></a>
      <a href="/publications/">Publications <span aria-hidden="true">→</span></a>
    </nav>
    <p class="about-cv-note">CV updated August 2026</p>
  </div>

  <section class="about-section" aria-labelledby="about-research-title">
    <h2 class="about-section-title" id="about-research-title">Research at a glance</h2>
    <div class="about-themes">
      <a class="about-theme" href="/research/#secure-autonomy" aria-label="Explore resilient autonomy research">
        <img src="/images/resilient-multi-agent-autonomy.png" alt="Concept illustration of cooperating UAVs and cyberattack mitigation." loading="eager" decoding="async">
        <span><span class="about-theme-title">Resilient autonomy</span><span class="about-theme-detail">Cooperation under cyberattacks</span></span>
      </a>
      <a class="about-theme" href="/research/#uav-safety" aria-label="Explore safety-critical control research">
        <img src="/images/safety-critical-uav-control.png" alt="Concept illustration of red reachable sets and a proactive collision-avoidance path." loading="eager" decoding="async">
        <span><span class="about-theme-title">Safety-critical control</span><span class="about-theme-detail">Anticipating and avoiding risk</span></span>
      </a>
      <a class="about-theme" href="/research/#energy-aware-control" aria-label="Explore energy-aware systems research">
        <img src="/images/energy-aware-uav-network.png" alt="Concept illustration of networked UAVs with different battery charge levels." loading="eager" decoding="async">
        <span><span class="about-theme-title">Energy-aware systems</span><span class="about-theme-detail">Coordination with battery constraints</span></span>
      </a>
    </div>
    <details class="about-research-map">
      <summary>View the full research map</summary>
      <a href="/images/Research_Figure.png" target="_blank" rel="noopener noreferrer" aria-label="Open full research map (new tab)"><img src="/images/Research_Figure.png" alt="Overview of research themes in resilient autonomous systems, including control, estimation, safety, and energy constraints." loading="lazy" decoding="async"></a>
    </details>
  </section>

  <section class="about-section" aria-labelledby="about-highlights-title">
    <h2 class="about-section-title" id="about-highlights-title">Experience &amp; recognition</h2>
    <ul class="about-highlights" role="list">
      <li class="about-highlight"><span class="about-highlight-label">Research recognition</span><p>Recipient of Purdue University's <a href="https://engineering.purdue.edu/Engr/People/Awards/Graduate/ptRecipientListing?group_id=237384&amp;show_sub_groups=1" target="_blank" rel="noopener noreferrer">Magoon Award for Research Excellence</a> (2026).</p></li>
      <li class="about-highlight"><span class="about-highlight-label">Industry experience</span><p>Controls research at <a href="/project/#cummins-eco-acc">Cummins</a> and servo-control development at <a href="/project/#pangolin-servo">Pangolin Laser Systems</a>.</p></li>
      <li class="about-highlight"><span class="about-highlight-label">NASA-supported research</span><p>Cyberattack resilience and risk assessment for urban air mobility through the <a href="/project/#nasa-uam">NASA Secure and Safe Assured Autonomy (S2A2) University Leadership Initiative (ULI) project</a>.</p></li>
    </ul>
  </section>

  <section class="about-section" aria-labelledby="about-news-title">
    <h2 class="about-section-title" id="about-news-title">Recent news</h2>
    <ul class="about-news-list" role="list">
    <li class="about-news-item" id="news-1">
      <div class="about-news-meta"><time class="about-news-date" datetime="2026-08">August 2026</time><span class="about-news-category">Publication</span></div>
      <p class="about-news-body">Our paper <strong><a href="https://ieeexplore.ieee.org/document/11663187" target="_blank" rel="noopener noreferrer">Energy-Aware Consensus Control for Multi-Agent Systems with Guaranteed Battery Safety via H-Infinity LMI Design</a></strong> was accepted for publication in IEEE Control Systems Letters!</p>
    </li>
    <li class="about-news-item" id="news-2">
      <div class="about-news-meta"><time class="about-news-date" datetime="2026-06">June 2026</time><span class="about-news-category">Publication</span></div>
      <p class="about-news-body">Our paper <strong><a href="https://asmedigitalcollection.asme.org/lettersdynsys/article-abstract/doi/10.1115/1.4072730/1235540/Koopman-Based-State-of-Charge-Observer-Design-for?redirectedFrom=fulltext" target="_blank" rel="noopener noreferrer">Koopman-Based State-of-Charge Observer Design for Lithium-Ion Batteries: An LMI-Based Framework</a></strong> was accepted for publication in ASME Letters in Dynamic Systems and Control! I look forward to presenting my work in the 2026 Modeling, Estimation and Control Conference (<strong><a href="https://mecc2026.a2c2.org/" target="_blank" rel="noopener noreferrer">MECC 2026</a></strong>).</p>
    </li>
    <li class="about-news-item" id="news-3">
      <div class="about-news-meta"><time class="about-news-date" datetime="2026-04">April 2026</time><span class="about-news-category">Industry</span></div>
      <p class="about-news-body">Summer internship: <strong>Control Systems Servo R&amp;D Intern</strong> at Pangolin Laser Systems, focusing on motion planning and precision control for optical scanning systems.</p>
    </li>
    <li class="about-news-item" id="news-4">
      <div class="about-news-meta"><time class="about-news-date" datetime="2026-03">March 2026</time><span class="about-news-category">Award</span></div>
      <p class="about-news-body">I received the <strong> <a href="https://engineering.purdue.edu/Engr/People/Awards/Graduate/ptRecipientListing?group_id=237384&show_sub_groups=1" target="_blank" rel="noopener noreferrer"> Estus H. and Vashti L. Magoon Award for Research Excellence </a> </strong> from the Purdue University College of Engineering in recognition of my Ph.D. graduate research!</p>
    </li>
    </ul>
    <details class="about-news-archive">
      <summary>Earlier news <span aria-hidden="true">(8)</span></summary>
      <ul class="about-news-list" role="list">
      <li class="about-news-item" id="news-5">
      <div class="about-news-meta"><time class="about-news-date" datetime="2026-01">January 2026</time><span class="about-news-category">Publication</span></div>
      <p class="about-news-body">Our paper <strong> <a href="https://ieeexplore.ieee.org/document/11367661" target="_blank" rel="noopener noreferrer"> LMI-Driven Reachability Analysis for Fuzzy Model-Based Nonlinear Systems Subject to Norm-Bounded Input Perturbations </a> </strong> was accepted for publication in IEEE Control Systems Letters!</p>
    </li>
      <li class="about-news-item" id="news-6">
      <div class="about-news-meta"><time class="about-news-date" datetime="2026-01">January 2026</time><span class="about-news-category">Conference</span></div>
      <p class="about-news-body">Our two papers, <strong> <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-0920" target="_blank" rel="noopener noreferrer"> C-Rate Constrained Path Planning for Battery Pack Health Management in Long-Term eVTOL Operations </a> </strong> and <strong> <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-1584" target="_blank" rel="noopener noreferrer"> LMI-Driven Tracking Control of Fuzzy Nonlinear Cyber-Physical Systems: Application to Quadrotor UAVs in Urban-Like Environment </a> </strong> were presented at 2026 AIAA SciTech Forum!</p>
    </li>
      <li class="about-news-item" id="news-7">
      <div class="about-news-meta"><time class="about-news-date" datetime="2025-12">December 2025</time><span class="about-news-category">Milestone</span></div>
      <p class="about-news-body">I became a <strong>Ph.D. Candidate</strong> at Purdue University School of Aeronautics and Astronautics! My thesis title is <strong>"<i>Toward Secure, Safe, and Resilient Multi Agent Cyber-Physical Systems: A Control-Theoretical Approach</i>"</strong>.</p>
    </li>
      <li class="about-news-item" id="news-8">
      <div class="about-news-meta"><time class="about-news-date" datetime="2025-06">June 2025</time><span class="about-news-category">Publication</span></div>
      <p class="about-news-body">Our paper <strong> <a href="https://ieeexplore.ieee.org/abstract/document/11022616" target="_blank" rel="noopener noreferrer"> Resilient Tracking Control For Leader-Follower Multi-Agent Systems Against Sinusoidal Sensor Attacks: An LMI-Based Framework </a> </strong> was accepted for publication in IEEE Control Systems Letters!</p>
    </li>
      <li class="about-news-item" id="news-9">
      <div class="about-news-meta"><time class="about-news-date" datetime="2025-05">May 2025</time><span class="about-news-category">Industry</span></div>
      <p class="about-news-body">Summer internship: <strong>Controls Research Engineer</strong> at Cummins Inc.</p>
    </li>
      <li class="about-news-item" id="news-10">
      <div class="about-news-meta"><time class="about-news-date" datetime="2025-05">May 2025</time><span class="about-news-category">Book chapter</span></div>
      <p class="about-news-body">Our book chapter abstract <strong>Proactive Risk Assessment of Multi-Vehicle Transportation Systems via Reachability Analysis against Stealthy Attacks</strong> has been accepted for <strong><a href="https://www.worldscientific.com/worldscibooks/10.1142/14831?srsltid=AfmBOooxifJOvsUODYEgH1zLVd5yHf3kU745BUhbFnOn78AC4nLFxLd2#t=aboutBook" target="_blank" rel="noopener noreferrer">Advances in Transportation Cybersecurity and Resilience</a></strong> by World Scientific Publishing!</p>
    </li>
      <li class="about-news-item" id="news-11">
      <div class="about-news-meta"><time class="about-news-date" datetime="2025-02">February 2025</time><span class="about-news-category">Award</span></div>
      <p class="about-news-body">I received the <strong>First place poster award</strong> at the <strong><a href="https://nari.arc.nasa.gov/imaginAviation/" target="_blank" rel="noopener noreferrer">2024 NASA ImaginAviation Annual Conference</a></strong>. The title of my presentation is <strong>"<i>Reactive and Proactive Cyberattack Defense Strategy for Urban Air Mobility (UAM) Applications</i>"</strong>.</p>
    </li>
      <li class="about-news-item" id="news-12">
      <div class="about-news-meta"><time class="about-news-date" datetime="2023-10">October 2023</time><span class="about-news-category">Seminar</span></div>
      <p class="about-news-body">I will give a talk on cybersecurity for UAM systems at North Carolina Agricultural and Technical State University (NCAT). This work is part of the <a href="https://uli.arc.nasa.gov/projects/10/" target="_blank" rel="noopener noreferrer"> <strong>NASA Secure and Safe Assured Autonomy (S2A2)</strong> </a> project.</p>
    </li>
      </ul>
    </details>
  </section>
</div>
