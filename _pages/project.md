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
  <details class="project-expand">
    <summary>Project details &amp; flight simulation<span class="projects-sr-only">: Battery-Aware eVTOL Modeling &amp; Simulation</span></summary>
    <div class="project-details">
      <p class="project-official-title"><strong>Full project title:</strong> Development of Advanced Air Mobility Battery Management System</p>
      <p>Within the advanced air mobility battery management project, my work centers on the design and analysis of tilt-rotor eVTOL aircraft. I combine aerodynamic modeling, power-system simulation, and control design to study flight from vertical takeoff through forward cruise and the return to hover.</p>
      <p>The connection to battery management is the flight-to-powertrain model: flight maneuvers and controller commands determine motor demand, which in turn affects battery current, voltage, and energy consumption. Trim analysis, robust control, and battery-aware estimation support the study of mode transitions and mission-level electrical performance.</p>
      <p><a href="/research/#battery-estimation">Explore the related battery research</a></p>
      <figure class="project-large-figure">
        <img src="/images/Simulink.png" alt="Integrated tilt-rotor eVTOL simulation linking aerodynamic analysis, flight control, motors, battery, and aircraft motion." loading="lazy" decoding="async">
        <figcaption>Integrated eVTOL flight and powertrain simulation.</figcaption>
      </figure>
      <figure class="project-demo">
        <video width="900" height="550" autoplay loop muted controls playsinline preload="metadata" aria-label="Tilt-rotor eVTOL flight and electrical performance simulation">
          <source src="/images/ABMS_Video.mp4" type="video/mp4">
          <a href="/images/ABMS_Video.mp4">Open the flight simulation video</a>
        </video>
        <figcaption>Electrical performance of a tilt-rotor eVTOL over a flight profile.</figcaption>
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
