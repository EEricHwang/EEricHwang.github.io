---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
---

<!-- Replace the entire _pages/project.md file with this content. -->
<style>
/* Scoped to this page, so this single Markdown file can be copied to GitHub. */

.projects-page { --project-accent: #17675f; --project-ink: #253b40; --project-muted: #58666a; }
.projects-page, .projects-page * { box-sizing: border-box; }
.projects-page a { color: var(--project-accent); text-underline-offset: .2em; }
.projects-page a:focus-visible, .projects-page summary:focus-visible { outline: 3px solid var(--project-accent); outline-offset: 4px; border-radius: 2px; }
.projects-intro { margin: 0 0 1.8rem; }
.projects-intro p { max-width: 54em; margin: 0 0 1rem; font-size: 1.05em; line-height: 1.7; color: var(--project-ink); }
.projects-jump { display: flex; flex-wrap: wrap; gap: .65rem 1.5rem; font-size: .8em; }
.projects-jump a { padding: .4rem 0; font-weight: 600; }
.projects-group { scroll-margin-top: 1.5rem; margin-top: 2.2rem; }
.projects-page .projects-group-title { margin: 0; padding: 0 0 .7rem; border-bottom: 2px solid var(--project-accent); font-size: 1.1em; line-height: 1.4; color: var(--project-accent); }
.project-entry { border-bottom: 1px solid #dce3e2; padding: 1.75rem 0 2rem; scroll-margin-top: 1.5rem; }
.project-meta { display: flex; flex-wrap: wrap; justify-content: space-between; gap: .45rem 1rem; margin-bottom: .6rem; font-size: .72em; color: var(--project-muted); }
.project-category { color: var(--project-accent); font-weight: 700; letter-spacing: .045em; text-transform: uppercase; }
.project-heading { display: grid; grid-template-columns: minmax(0, 1fr) 132px; align-items: center; gap: 1.4rem; }
.project-heading-copy { min-width: 0; }
.project-heading-without-logo { grid-template-columns: minmax(0, 1fr); }
.project-brand { display: flex; align-items: center; justify-content: center; width: 132px; min-height: 92px; padding: .35rem; }
.projects-page .project-brand img { display: block; max-width: 100%; height: auto; margin: 0; border: 0; box-shadow: none; }
.project-brand-nasa img { width: 88px; }
.project-brand-cummins img { width: 65px; }
.project-brand-scannermax img { width: 132px; }
.project-brand-kencoa img { width: 132px; }
.projects-page .project-title { color: var(--project-ink); font-size: 1.28em; line-height: 1.35; margin: 0 0 .65rem; }
.project-organization, .project-role { font-size: .78em; line-height: 1.6; margin: .3rem 0; overflow-wrap: anywhere; }
.project-organization strong, .project-role strong { color: var(--project-ink); }
.project-body { display: grid; grid-template-columns: minmax(0, 1.1fr) minmax(0, 1fr); gap: 1.5rem; align-items: start; margin-top: 1.25rem; }
.project-highlights { min-width: 0; }
.project-outcome { background: #f1f7f5; border-left: 3px solid #82b3a9; padding: .9rem 1rem; margin-bottom: 1rem; }
.project-outcome-label { display: block; color: var(--project-accent); font-size: .65em; letter-spacing: .065em; text-transform: uppercase; font-weight: 700; margin-bottom: .3rem; }
.project-outcome strong { display: block; color: var(--project-ink); font-size: 1em; line-height: 1.4; margin: 0 0 .4rem; }
.project-outcome p { font-size: .75em; line-height: 1.65; margin: 0; }
.projects-page .project-contributions-title { margin: 0 0 .5rem; color: var(--project-ink); font-size: .78em; font-weight: 700; }
.projects-page .project-contributions { padding-left: 1.15em; margin: 0; font-size: .8em; line-height: 1.7; }
.project-contributions li { margin-bottom: .5rem; }
.projects-page .project-methods { color: var(--project-muted); font-size: .7em; line-height: 1.6; margin: .85rem 0 0; }
.projects-page .project-figure { display: block; margin: 0; min-width: 0; }
.project-figure > a { display: flex; justify-content: center; align-items: center; min-height: 220px; padding: .5rem; border: 1px solid #dce3e2; border-radius: 5px; background: #fff; }
.project-figure > a:hover { border-color: var(--project-accent); }
.projects-page .project-figure a:hover img { box-shadow: none; }
.project-figure img { display: block; width: 100%; height: 210px; object-fit: contain; }
.projects-page .project-figure figcaption { font-size: .68em; line-height: 1.5; color: var(--project-muted); margin: .55rem 0 0; text-align: left; font-family: inherit; }
.project-expand { margin-top: 1.1rem; }
.project-expand > summary { cursor: pointer; color: var(--project-accent); font-weight: 600; font-size: .78em; padding: .5rem 0; min-height: 40px; width: fit-content; max-width: 100%; }
.project-details { padding: 1.25rem; background: #f7f9f9; border-left: 3px solid #98bfb9; font-size: .86em; line-height: 1.75; overflow-wrap: anywhere; margin-top: .75rem; }
.project-details p { margin: 0 0 1rem; }
.project-details .project-official-title { font-size: .88em; color: var(--project-muted); }
.projects-page .project-large-figure { display: block; margin: 1.2rem 0 0; }
.project-large-figure img { display: block; width: 100%; max-width: 100%; height: auto; background: white; }
.projects-page .project-large-figure figcaption { font-family: inherit; font-size: .78em; line-height: 1.5; color: var(--project-muted); margin-top: .6rem; }
.projects-page .project-demo { display: block; margin: 1.5rem 0 0; }
.project-demo video { display: block; width: 100%; max-width: 100%; height: auto; background: #17292f; border-radius: 4px; }
.projects-page .project-demo figcaption { font-family: inherit; font-size: .78em; line-height: 1.5; margin-top: .6rem; }
.projects-sr-only { position: absolute; width: 1px; height: 1px; padding: 0; margin: -1px; overflow: hidden; clip: rect(0,0,0,0); white-space: nowrap; border: 0; }
@media (max-width: 760px) {
  .project-heading { grid-template-columns: minmax(0, 1fr); gap: .9rem; }
  .project-heading-copy { display: contents; }
  .project-heading .project-title { grid-row: 1; margin-bottom: 0; }
  .project-heading .project-brand { grid-row: 2; justify-content: flex-start; min-height: 0; width: 132px; padding: 0; }
  .project-brand-nasa img { width: 72px; }
  .project-brand-cummins img { width: 52px; }
  .project-heading .project-organization, .project-heading .project-role { margin: 0; }
  .project-heading { gap: .65rem; }
  .project-body { grid-template-columns: minmax(0, 1fr); gap: 1.15rem; }
  .project-figure { grid-row: 1; }
  .project-figure img { height: 210px; }
  .project-meta { font-size: .8em; }
  .project-organization, .project-role, .projects-page .project-contributions { font-size: .88em; }
  .project-outcome p { font-size: .86em; }
  .project-expand > summary { min-height: 44px; font-size: .85em; }
  .project-details { padding: 1rem; }
}
@media print { .project-entry { break-inside: avoid; } .projects-jump { display: none; } }


/* K-UAM demonstration: video above the geographic route. */
.project-mission { margin: 1.8rem 0 1.5rem; border: 1px solid #dce5e2; border-radius: 8px; overflow: hidden; background: #fff; }
.project-mission-header { padding: 1.1rem 1.25rem 1rem; background: #f1f7f5; }
.projects-page .project-mission-kicker { margin: 0 0 .35rem; font-size: .62em; line-height: 1.5; letter-spacing: .08em; font-weight: 700; text-transform: uppercase; color: var(--project-accent); }
.projects-page .project-mission-title { margin: 0 0 .45rem; font-size: 1.1em; line-height: 1.4; color: var(--project-ink); }
.projects-page .project-mission-description { margin: 0; font-size: .76em; line-height: 1.6; color: var(--project-muted); }
.projects-page .project-mission-video { display: block; margin: 0; }
.project-mission-video video { display: block; width: 100%; height: auto; aspect-ratio: 16 / 9; background: #17292f; }
.projects-page .project-mission-video figcaption { margin: 0; padding: .7rem 1.25rem; font-family: inherit; font-size: .68em; line-height: 1.6; color: var(--project-muted); }
.projects-page .project-route { display: block; margin: 0; border-top: 1px solid #dce5e2; }
.project-route-heading { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: .5rem; padding: 1rem 1.25rem .8rem; }
.projects-page .project-route-title { margin: 0; padding: 0; font-size: .85em; line-height: 1.5; color: var(--project-ink); }
.project-route-distance { font-size: .63em; color: var(--project-accent); background: #edf5f2; border-radius: 20px; padding: .35rem .65rem; white-space: nowrap; }
.project-route-map { height: 390px; width: 100%; isolation: isolate; background: #e9eeeb; font-family: inherit; }
.projects-page .project-route-map img { max-width: none !important; max-height: none !important; margin: 0; border: 0; border-radius: 0; box-shadow: none; }
.project-route-map .leaflet-tooltip { font-family: inherit; font-size: 12px; line-height: 1.5; padding: 6px 10px; color: #253b40; box-shadow: 0 2px 8px #253b4015; border: 1px solid #dce5e2; }
.project-route-map .leaflet-tooltip strong { display: block; }
.project-route-map .leaflet-tooltip small { color: #58666a; font-size: 10px; }
.project-route-map .leaflet-control-attribution { font-size: 10px; }
.project-route-map a.leaflet-control-zoom-in, .project-route-map a.leaflet-control-zoom-out { color: #253b40; text-decoration: none; }
.project-route-arrow { display: flex; align-items: center; justify-content: center; border: 2px solid white; border-radius: 50%; background: #17675f; color: #fff; font: 700 19px/1 sans-serif; box-shadow: 0 2px 6px #253b4030; }
.project-route-fallback { padding: 1.4rem 1.25rem; background: #f4f7f5; font-size: .76em; line-height: 1.7; color: var(--project-ink); }
.project-route-fallback p { margin: .4rem 0; }
.project-route-fallback small { color: var(--project-muted); }
.projects-page .project-route-status { margin: 0; padding: .55rem 1.25rem; color: var(--project-muted); font-size: .7em; }
.project-route-points { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; padding: 1rem 1.25rem .8rem; }
.project-route-point { border-left: 2px solid #82b3a9; padding-left: .65rem; min-width: 0; }
.project-route-point span { display: block; font-size: .58em; font-weight: 700; letter-spacing: .07em; text-transform: uppercase; color: var(--project-accent); }
.project-route-point a { display: inline-block; margin: .3rem 0 .2rem; font-size: .73em; font-weight: 600; line-height: 1.4; }
.project-route-point small { display: block; font-size: .58em; line-height: 1.6; color: var(--project-muted); }
.projects-page .project-route figcaption { margin: 0; padding: 0 1.25rem 1rem; font-family: inherit; font-size: .64em; line-height: 1.6; color: var(--project-muted); }
.project-mission [hidden] { display: none !important; }
@media (max-width: 600px) {
  .project-mission-header, .project-route-heading { padding-left: .9rem; padding-right: .9rem; }
  .projects-page .project-mission-title { font-size: 1em; }
  .project-route-map { height: 360px; }
  .project-route-map .leaflet-tooltip { font-size: 11px; padding: 5px 7px; }
  .project-route-points { grid-template-columns: 1fr; gap: .8rem; padding: .9rem; }
  .project-route-point a { font-size: .82em; }
  .project-route-point small { font-size: .7em; }
  .projects-page .project-route figcaption, .projects-page .project-mission-video figcaption { padding-left: .9rem; padding-right: .9rem; font-size: .74em; }
}
@media print { .project-route-map { display: none; } }

</style>

<div class="projects-page">
  <div class="projects-intro">
    <p>I apply control and estimation methods to aerial autonomy, electrified flight, heavy-duty vehicles, and precision motion systems. These projects connect my research with system modeling, controller development, and simulation.</p>
    <nav class="projects-jump" aria-label="Project categories">
      <a href="#research-projects">Research projects</a>
      <a href="#industry-projects">Industry R&amp;D</a>
    </nav>
  </div>
  <section class="projects-group" id="research-projects" aria-labelledby="research-projects-title">
    <h2 class="projects-group-title" id="research-projects-title">Research projects</h2>
<!-- nasa-uam: edit this project's role, contributions, and outcome here. -->
<article class="project-entry" id="nasa-uam" aria-labelledby="nasa-uam-title">
  <header>
    <div class="project-meta"><span class="project-category">Aerial autonomy</span><span>Aug 2021 – Aug 2025</span></div>
    <div class="project-heading">
      <div class="project-heading-copy">
        <h3 class="project-title" id="nasa-uam-title">Secure Autonomy for Urban Air Mobility</h3>
        <p class="project-organization"><strong>Research sponsor:</strong> National Aeronautics and Space Administration (NASA)</p>
        <p class="project-role"><strong>My focus:</strong> Cyber threat management for cooperating aerial vehicles</p>
      </div>
      <div class="project-brand project-brand-nasa">
        <img src="/images/logo-nasa.png" alt="NASA" loading="eager" decoding="async">
      </div>
    </div>
  </header>
  <div class="project-body">
    <div class="project-highlights">
      <div class="project-outcome">
        <span class="project-outcome-label">Contribution</span>
        <strong>Attack mitigation &amp; risk assessment</strong>
        <p>Control-theoretic methods for multi-vehicle autonomy under cyberattacks and uncertainty.</p>
      </div>
      <h4 class="project-contributions-title">Key contributions</h4>
      <ul class="project-contributions">
        <li>Developed cyber threat management algorithms for multiple aerial vehicles.</li>
        <li>Applied estimation and stability-based analysis to mitigate attacks and assess operational risk.</li>
      </ul>
      <p class="project-methods">State estimation · Resilient control · Safety analysis</p>
    </div>
    <figure class="project-figure">
      <a href="/images/Research_Diagram.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Secure Autonomy for Urban Air Mobility (new tab)">
        <img src="/images/Research_Diagram.png" alt="Urban air mobility cybersecurity framework showing networked aerial vehicles, attack mitigation, and risk assessment." loading="eager" decoding="async">
      </a>
      <figcaption>Cyber threat management for urban air mobility.</figcaption>
    </figure>
  </div>
  <details class="project-expand">
    <summary>Project details &amp; research framework<span class="projects-sr-only">: Secure Autonomy for Urban Air Mobility</span></summary>
    <div class="project-details">
      <p class="project-official-title"><strong>Full project title:</strong> Secure and Safe Assured Autonomy for Urban Air Mobility</p>
      <p>This project investigated vehicle-level control methods for safer and more secure urban air mobility (UAM). My work focused on cyber threat management for multiple aerial vehicles exposed to disturbances, model uncertainty, and cyberattacks.</p>
      <p>I used control-theoretic tools, including Kalman filtering, control barrier functions, and Lyapunov stability analysis, to develop attack-mitigation and risk-assessment methods. The work connected cooperative flight control with the analysis of adversarial effects on vehicle operation.</p>
      <p><a href="/research/#secure-autonomy">Explore the related research</a></p>
      <figure class="project-large-figure">
        <img src="/images/Research_Diagram.png" alt="Urban air mobility cybersecurity framework showing networked aerial vehicles, attack mitigation, and risk assessment." loading="lazy" decoding="async">
        <figcaption>Cyber threat management for urban air mobility.</figcaption>
      </figure>

    </div>
  </details>
</article>

<!-- evtol-battery: edit this project's role, contributions, and outcome here. -->
<article class="project-entry" id="evtol-battery" aria-labelledby="evtol-battery-title">
  <header>
    <div class="project-meta"><span class="project-category">Electrified flight</span><span>Oct 2024 – Dec 2026</span></div>
    <div class="project-heading">
      <div class="project-heading-copy">
        <h3 class="project-title" id="evtol-battery-title">Battery-Aware eVTOL Modeling &amp; Simulation</h3>
        <p class="project-organization"><strong>Research sponsor:</strong> Ministry of Trade, Industry and Energy, Republic of Korea</p>
        <p class="project-role"><strong>My focus:</strong> Tilt-rotor modeling, flight control, and power-system simulation</p>
      </div>
      <div class="project-brand project-brand-kencoa">
        <img src="/images/logo-kencoa-enertech.png" alt="KENCOA ENERTECH" loading="lazy" decoding="async">
      </div>
    </div>
  </header>
  <div class="project-body">
    <div class="project-highlights">
      <div class="project-outcome">
        <span class="project-outcome-label">Ongoing work</span>
        <strong>Linking flight behavior to battery demand</strong>
        <p>An integrated view of aircraft dynamics, control commands, and electrical performance.</p>
      </div>
      <h4 class="project-contributions-title">My work</h4>
      <ul class="project-contributions">
        <li>Integrate aerodynamic modeling, flight-controller design, and electric powertrain simulation.</li>
        <li>Analyze energy consumption and stability across vertical flight, transition, and forward cruise.</li>
      </ul>
      <p class="project-methods">Trim analysis · Robust control · MATLAB/Simulink</p>
    </div>
    <figure class="project-figure">
      <a href="/images/Simulink.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Battery-Aware eVTOL Modeling &amp; Simulation (new tab)">
        <img src="/images/Simulink.png" alt="Integrated tilt-rotor eVTOL simulation linking aerodynamic analysis, flight control, motors, battery, and aircraft motion." loading="lazy" decoding="async">
      </a>
      <figcaption>Integrated eVTOL flight and powertrain simulation.</figcaption>
    </figure>
  </div>
  <section class="project-mission" aria-labelledby="evtol-dynamics-demo-title">
    <div class="project-mission-header">
      <p class="project-mission-kicker">Integrated flight &amp; powertrain simulation</p>
      <h4 class="project-mission-title" id="evtol-dynamics-demo-title">Flight Motion &amp; Battery Performance</h4>
      <p class="project-mission-description">Simulation of tilt-rotor eVTOL flight motion and the corresponding battery response.</p>
    </div>
    <figure class="project-mission-video">
      <video id="evtol-dynamics-video" width="1920" height="1080" controls muted loop playsinline preload="metadata" aria-label="Tilt-rotor eVTOL flight motion and battery performance simulation" aria-describedby="evtol-dynamics-caption">
        <source src="/images/ABMS_Video.mp4" type="video/mp4">
        <a href="/images/ABMS_Video.mp4">Open the flight and battery simulation video</a>
      </video>
      <figcaption id="evtol-dynamics-caption">Flight motion and battery electrical response across a simulated flight profile.</figcaption>
    </figure>
  </section>
  <section class="project-mission" aria-labelledby="kuam-demo-title">
    <div class="project-mission-header">
      <p class="project-mission-kicker">Example application · Unreal Engine visualization</p>
      <h4 class="project-mission-title" id="kuam-demo-title">K-UAM Mission Example</h4>
      <p class="project-mission-description">As one example application of the simulator, flight-simulator outputs are integrated with Unreal Engine to visualize an eVTOL mission from Seoul Olympic Park to Bundang Central Park.</p>
    </div>
    <figure class="project-mission-video">
      <video id="kuam-demo-video" width="1920" height="1080" controls muted loop playsinline preload="none" poster="/images/k-uam-demo-poster.jpg" aria-label="K-UAM eVTOL flight simulation from Seoul Olympic Park to Bundang Central Park" aria-describedby="kuam-video-caption">
        <source src="/images/k-uam-demo.mp4" type="video/mp4">
        <a href="/images/k-uam-demo.mp4">Open the K-UAM simulation video</a>
      </video>
      <figcaption id="kuam-video-caption">A 70-second visualization of this example mission. Use the player controls to pause or view full-screen.</figcaption>
    </figure>
    <figure class="project-route" aria-labelledby="kuam-route-title">
      <div class="project-route-heading">
        <h5 class="project-route-title" id="kuam-route-title">Flight route</h5>
        <span class="project-route-distance">≈ 16.0 km · straight line</span>
      </div>
      <div id="kuam-route-fallback" class="project-route-fallback">
        <p><strong>Seoul Olympic Park</strong><br>↓ Straight-line simulation route<br><strong>Bundang Central Park</strong></p>
        <small>The interactive map loads here. You can also open either location using the links below.</small>
      </div>
      <div id="kuam-route-map" class="project-route-map" role="region" aria-label="Interactive map: straight flight route from Seoul Olympic Park to Bundang Central Park" hidden></div>
      <p id="kuam-route-status" class="project-route-status" role="status" hidden></p>
      <div class="project-route-points">
        <div class="project-route-point">
          <span>01 · Departure</span>
          <a href="https://www.google.com/maps/search/?api=1&amp;query=37.52070%2C127.12270" target="_blank" rel="noopener noreferrer">Seoul Olympic Park ↗</a>
          <small>37.52070° N, 127.12270° E</small>
        </div>
        <div class="project-route-point">
          <span>02 · Arrival</span>
          <a href="https://www.google.com/maps/search/?api=1&amp;query=37.37706%2C127.12442" target="_blank" rel="noopener noreferrer">Bundang Central Park ↗</a>
          <small>37.37706° N, 127.12442° E</small>
        </div>
      </div>
      <figcaption>Straight-line route between the simulation’s departure and arrival coordinates. Map: © <a href="https://www.openstreetmap.org/copyright">OpenStreetMap contributors</a>.</figcaption>
    </figure>
  </section>

  <details class="project-expand">
    <summary>Project details &amp; simulation framework<span class="projects-sr-only">: Battery-Aware eVTOL Modeling &amp; Simulation</span></summary>
    <div class="project-details">
      <p class="project-official-title"><strong>Full project title:</strong> Development of Advanced Air Mobility Battery Management System</p>
      <p>Within the advanced air mobility battery management project, my work centers on the design and analysis of tilt-rotor eVTOL aircraft. I combine aerodynamic modeling, power-system simulation, and control design to study flight from vertical takeoff through forward cruise and the return to hover.</p>
      <p>The connection to battery management is the flight-to-powertrain model: flight maneuvers and controller commands determine motor demand, which in turn affects battery current, voltage, and energy consumption. Trim analysis, robust control, and battery-aware estimation support the study of mode transitions and mission-level electrical performance.</p>
      <p><a href="/research/#battery-estimation">Explore the related battery research</a></p>
      <figure class="project-large-figure">
        <img src="/images/Simulink.png" alt="Integrated tilt-rotor eVTOL simulation linking aerodynamic analysis, flight control, motors, battery, and aircraft motion." loading="lazy" decoding="async">
        <figcaption>Integrated eVTOL flight and powertrain simulation.</figcaption>
      </figure>

    </div>
  </details>
</article>
  </section>
  <section class="projects-group" id="industry-projects" aria-labelledby="industry-projects-title">
    <h2 class="projects-group-title" id="industry-projects-title">Industry R&amp;D</h2>
<!-- cummins-eco-acc: edit this project's role, contributions, and outcome here. -->
<article class="project-entry" id="cummins-eco-acc" aria-labelledby="cummins-eco-acc-title">
  <header>
    <div class="project-meta"><span class="project-category">Heavy-duty vehicles</span><span>May 2025 – Aug 2025</span></div>
    <div class="project-heading">
      <div class="project-heading-copy">
        <h3 class="project-title" id="cummins-eco-acc-title">Predictive Eco-ACC for Class 8 Heavy-Duty Trucks</h3>
        <p class="project-organization"><strong>Company:</strong> Cummins Inc. · Cummins Technical Center</p>
        <p class="project-role"><strong>My role:</strong> Controls Research Engineer Intern · Connected and Intelligent Systems</p>
      </div>
      <div class="project-brand project-brand-cummins">
        <img src="/images/logo-cummins.png" alt="Cummins" loading="lazy" decoding="async">
      </div>
    </div>
  </header>
  <div class="project-body">
    <div class="project-highlights">
      <div class="project-outcome">
        <span class="project-outcome-label">Validated result</span>
        <strong>2–5% improvement in fuel economy</strong>
        <p>Compared with an existing PID-based method that relies only on instantaneous information.</p>
      </div>
      <h4 class="project-contributions-title">Key contributions</h4>
      <ul class="project-contributions">
        <li>Led the design and implementation of real-time, MPC-based Eco-Adaptive Cruise Control for Class 8 semi-trucks.</li>
        <li>Incorporated road-grade preview and preceding-vehicle interactions to balance fuel efficiency with safety margins.</li>
      </ul>
      <p class="project-methods">Model predictive control (MPC) · Road-grade preview · Safe following distance</p>
    </div>
    <figure class="project-figure">
      <a href="/images/Cummins.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Predictive Eco-ACC for Class 8 Heavy-Duty Trucks (new tab)">
        <img src="/images/Cummins.png" alt="Eco-Adaptive Cruise Control for a Class 8 truck using road-grade preview and preceding-vehicle information." loading="lazy" decoding="async">
      </a>
      <figcaption>Predictive speed control with road and traffic information.</figcaption>
    </figure>
  </div>
  <details class="project-expand">
    <summary>Project details &amp; evaluation<span class="projects-sr-only">: Predictive Eco-ACC for Heavy-Duty Trucks</span></summary>
    <div class="project-details">
      <p class="project-official-title"><strong>Full project title:</strong> Design and Implementation of Eco-Adaptive Cruise Control for Class 8 Semi-Trucks</p>
      <p>As a Controls Research Engineer Intern in Cummins’ Connected and Intelligent Systems group, I led the development of an Eco-Adaptive Cruise Control (Eco-ACC) system for Class 8 semi-trucks powered by Cummins power systems. The controller used model predictive control (MPC) to account for upcoming road grade and interactions with preceding vehicles.</p>
      <p><strong>Evaluation:</strong> MATLAB/Simulink-based simulations, using an existing PID-based method as the comparison baseline. The evaluated scenarios showed a <strong>2–5% improvement in fuel economy</strong> while maintaining the specified safety margins.</p>
      <figure class="project-large-figure">
        <img src="/images/Cummins.png" alt="Eco-Adaptive Cruise Control for a Class 8 truck using road-grade preview and preceding-vehicle information." loading="lazy" decoding="async">
        <figcaption>Predictive speed control with road and traffic information.</figcaption>
      </figure>

    </div>
  </details>
</article>

<!-- pangolin-servo: edit this project's role, contributions, and outcome here. -->
<article class="project-entry" id="pangolin-servo" aria-labelledby="pangolin-servo-title">
  <header>
    <div class="project-meta"><span class="project-category">Precision motion control</span><span>Jun 2026 – Aug 2026</span></div>
    <div class="project-heading">
      <div class="project-heading-copy">
        <h3 class="project-title" id="pangolin-servo-title">Actuator-Aware Control for Laser Scanners</h3>
        <p class="project-organization"><strong>Company:</strong> Pangolin Laser Systems · ScannerMAX Division</p>
        <p class="project-role"><strong>My role:</strong> Control Systems Servo R&D Intern · Servo Control Group</p>
      </div>
      <div class="project-brand project-brand-scannermax">
        <img src="/images/logo-scannermax.jpg" alt="ScannerMAX, a division of Pangolin Laser Systems" loading="lazy" decoding="async">
      </div>
    </div>
  </header>
  <div class="project-body">
    <div class="project-highlights">
      <div class="project-outcome">
        <span class="project-outcome-label">Outcome</span>
        <strong>No amplitude-specific tuning</strong>
        <p>Real-time motion profiling that adapts to available actuator acceleration.</p>
      </div>
      <h4 class="project-contributions-title">Key contributions</h4>
      <ul class="project-contributions">
        <li>Developed a motion profiler and tracking controller for high-performance galvanometer scanners.</li>
        <li>Combined bang-bang switching-curve control with a digital-twin voltage/current estimator to compute available acceleration at each control step.</li>
      </ul>
      <p class="project-methods">Motion profiling · Actuator constraints · Digital-twin estimation</p>
    </div>
    <figure class="project-figure">
      <a href="/images/Figure_Scanner.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Actuator-Aware Control for Laser Scanners (new tab)">
        <img src="/images/Figure_Scanner.png" alt="Galvanometer scanner control architecture, actuator constraints, motion profiling, and representative tracking results." loading="lazy" decoding="async">
      </a>
      <figcaption>Actuator-aware motion profiling and tracking control.</figcaption>
    </figure>
  </div>
  <details class="project-expand">
    <summary>Project details &amp; control architecture<span class="projects-sr-only">: Actuator-Aware Control for Laser Scanners</span></summary>
    <div class="project-details">
      <p class="project-official-title"><strong>Full project title:</strong> Motion Profiler and Controller Design for High-Performance Galvanometer Scanners</p>
      <p>In the Servo Control Group at Pangolin Laser Systems, I developed a real-time motion profiler and controller for galvanometer scanner systems. The design combined classical bang-bang switching-curve control with a digital-twin voltage/current estimator.</p>
      <p>By computing available acceleration at each control step, the controller adapted the motion profile to actuator capabilities. This eliminated amplitude-specific tuning while enabling consistent full-voltage utilization across a wide range of motion amplitudes.</p>
      <figure class="project-large-figure">
        <img src="/images/Figure_Scanner.png" alt="Galvanometer scanner control architecture, actuator constraints, motion profiling, and representative tracking results." loading="lazy" decoding="async">
        <figcaption>Actuator-aware motion profiling and tracking control.</figcaption>
      </figure>

    </div>
  </details>
</article>
  </section>
</div>

<script data-project-autoplay>
document.querySelectorAll('.projects-page .project-expand').forEach(function (section) {
  var videos = section.querySelectorAll('video');
  function syncPlayback() {
    videos.forEach(function (video) {
      if (section.open) {
        video.muted = true;
        var playback = video.play();
        if (playback) playback.catch(function () { /* Manual controls remain available. */ });
      } else {
        video.pause();
      }
    });
  }
  section.addEventListener('toggle', syncPlayback);
  syncPlayback();
});
</script>

<script data-kuam-showcase>
(function () {
  'use strict';
  var section = document.querySelector('.project-mission');
  if (!section) return;
  var videos = document.querySelectorAll('.project-mission-video video');
  /* Start each demonstration once when visible. Manual pause remains respected. */
  var reducedMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  function startVideo(video) {
    if (reducedMotion || (navigator.connection && navigator.connection.saveData)) return;
    video.muted = true;
    var play = video.play();
    if (play) play.catch(function () { /* Native controls remain available. */ });
  }
  if ('IntersectionObserver' in window) {
    var videoObserver = new IntersectionObserver(function (entries) {
      entries.forEach(function (entry) {
        if (entry.isIntersecting) {
          videoObserver.unobserve(entry.target);
          startVideo(entry.target);
        }
      });
    }, { threshold: 0.3 });
    videos.forEach(function (video) { videoObserver.observe(video); });
  }

  var container = document.getElementById('kuam-route-map');
  var fallback = document.getElementById('kuam-route-fallback');
  var status = document.getElementById('kuam-route-status');
  /* Coordinates supplied for this simulation. No road-routing service is used. */
  var departure = [37.52070, 127.12270];
  var arrival = [37.37706, 127.12442];
  function showMapError() {
    status.textContent = 'The interactive map is unavailable. Open the departure or arrival location using the links below.';
    status.hidden = false;
  }
  function initializeMap() {
    if (!window.L) return showMapError();
    container.hidden = false;
    var map = L.map(container, { scrollWheelZoom: false, zoomControl: false, zoomSnap: 0.25 });
    L.control.zoom({ position: 'topright' }).addTo(map);
    var tiles = L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);
    tiles.on('tileerror', function () {
      status.textContent = 'Some map tiles could not load. The route and location links remain available.';
      status.hidden = false;
    });
    tiles.on('tileload', function () { status.hidden = true; });
    L.polyline([departure, arrival], { color: '#fff', weight: 8, opacity: 0.95, interactive: false }).addTo(map);
    var route = L.polyline([departure, arrival], { color: '#17675f', weight: 4, opacity: 1, interactive: false }).addTo(map);
    var midpoint = [(departure[0] + arrival[0]) / 2, (departure[1] + arrival[1]) / 2];
    L.marker(midpoint, {
      icon: L.divIcon({ className: 'project-route-arrow', html: '<span aria-hidden="true">↓</span>', iconSize: [28, 28], iconAnchor: [14, 14] }),
      interactive: false, keyboard: false
    }).addTo(map);
    function endpoint(coords, title, subtitle, direction) {
      return L.circleMarker(coords, { radius: 7, color: '#fff', weight: 3, fillColor: '#17675f', fillOpacity: 1 })
        .addTo(map).bindTooltip('<strong>' + title + '</strong><small>' + subtitle + '</small>', {
          permanent: true, direction: direction, offset: [0, 0]
        });
    }
    endpoint(departure, 'Seoul Olympic Park', '01 · Departure', 'top');
    endpoint(arrival, 'Bundang Central Park', '02 · Arrival', 'bottom');
    function fitRoute() {
      map.invalidateSize();
      map.fitBounds(route.getBounds(), { padding: [40, 70], maxZoom: 13, animate: false });
    }
    fitRoute();
    fallback.hidden = true;
    if ('ResizeObserver' in window) new ResizeObserver(fitRoute).observe(container);
  }
  function loadMap() {
    if (window.L) return initializeMap();
    /* Pin Leaflet and verify CDN files. No API key is needed. */
    var css = document.createElement('link');
    css.rel = 'stylesheet';
    css.href = 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.css';
    css.integrity = 'sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY=';
    css.crossOrigin = '';
    var js = document.createElement('script');
    js.src = 'https://unpkg.com/leaflet@1.9.4/dist/leaflet.js';
    js.integrity = 'sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=';
    js.crossOrigin = '';
    var cssReady = false;
    var jsReady = false;
    function ready() { if (cssReady && jsReady) initializeMap(); }
    css.onload = function () { cssReady = true; ready(); };
    js.onload = function () { jsReady = true; ready(); };
    css.onerror = js.onerror = showMapError;
    document.head.appendChild(css);
    document.head.appendChild(js);
  }
  if ('IntersectionObserver' in window) {
    var mapObserver = new IntersectionObserver(function (entries) {
      if (entries.some(function (entry) { return entry.isIntersecting; })) {
        mapObserver.disconnect();
        loadMap();
      }
    }, { rootMargin: '250px' });
    mapObserver.observe(fallback);
  } else {
    loadMap();
  }
}());

</script>
