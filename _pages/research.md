---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

<!-- Self-contained Research page: upload this one file to _pages/research.md. -->
<style>

/* Research-page styles only. Existing site navigation and other pages are unaffected. */
.research-page { --research-accent: #17675f; --research-ink: #253b40; --research-muted: #58666a; }
.research-page, .research-page * { box-sizing: border-box; }
.research-intro { margin: 0 0 1.6rem; }
.research-intro .research-lead { color: var(--research-ink); font-size: 1.12em; line-height: 1.65; margin: 0 0 .7rem; max-width: 52em; }
.research-intro .research-context { color: var(--research-muted); font-size: .88em; margin: 0; }
.research-page a { color: var(--research-accent); text-underline-offset: .18em; }
.research-page a:focus-visible, .research-page summary:focus-visible { outline: 3px solid var(--research-accent); outline-offset: 5px; border-radius: 2px; }
.research-map { margin: 1rem 0 1.8rem; font-size: .85em; }
.research-map > summary { cursor: pointer; color: var(--research-accent); padding: .4rem 0; }
.research-map img { display: block; max-width: 100%; max-height: 520px; width: auto; margin: 1rem auto; }
.research-topic { padding: 2rem 0; border-top: 1px solid #dce3e2; scroll-margin-top: 2rem; }
.research-topic:last-child { border-bottom: 1px solid #dce3e2; }
.research-topic-top { display: grid; grid-template-columns: minmax(0, 34fr) minmax(0, 66fr); gap: 1.5rem; align-items: start; }
.research-topic .research-figure { display: block; margin: 0; min-width: 0; }
.research-figure > a { display: flex; align-items: center; justify-content: center; min-height: 180px; padding: .65rem; border: 1px solid #e2e8e7; border-radius: 6px; background: #fff; }
.research-figure img { display: block; width: 100%; height: 175px; object-fit: contain; }
.research-page .research-figure a:hover img { box-shadow: none; }
.research-figure a:hover { border-color: var(--research-accent); }
.research-page .research-figure figcaption { margin: .55rem 0 0; color: var(--research-muted); font-family: inherit; font-size: .68em; line-height: 1.5; text-align: left; }
.research-copy { min-width: 0; }
.research-page .research-index { margin: 0 0 .4rem; color: var(--research-accent); font-size: .66em; font-weight: 700; letter-spacing: .1em; text-transform: uppercase; }
.research-page .research-title { margin: 0 0 .65rem; padding: 0; border: 0; color: var(--research-ink); font-size: 1.22em; line-height: 1.3; }
.research-page .research-summary { margin: 0 0 .8rem; font-size: .86em; line-height: 1.7; }
.research-page .research-tags { margin: 0 0 .85rem; color: var(--research-muted); font-size: .7em; line-height: 1.6; }
.research-paper { font-size: .76em; display: flex; flex-wrap: wrap; align-items: baseline; gap: .4rem .6rem; }
.research-paper a { font-weight: 700; }
.research-paper span { color: var(--research-muted); }
.research-expand { margin-top: .85rem; }
.research-expand > summary { width: fit-content; max-width: 100%; margin-left: calc((100% - 1.5rem) * .34 + 1.5rem); cursor: pointer; color: var(--research-accent); padding: .35rem 0; font-size: .78em; font-weight: 600; }
.research-expand[open] > summary { margin-bottom: 1.1rem; }
.research-detail-content { padding: 1.35rem; border-left: 3px solid #98bfb9; background: #f7f9f9; font-size: .88em; line-height: 1.75; overflow-wrap: anywhere; }
.research-detail-content > :first-child { margin-top: 0; }
.research-detail-content h3 { margin: 1.7rem 0 .8rem; font-size: 1.1em; line-height: 1.4; }
.research-detail-content img { max-width: 100%; height: auto; }
.research-detail-content video { display: block; max-width: 100%; height: auto; margin: .5rem auto; }
.research-detail-content div[align="center"] { display: flex; flex-wrap: wrap; justify-content: center; align-items: flex-start; gap: 1rem; }
.research-detail-content div[align="center"] > figure { flex: 1 1 240px; min-width: 0; max-width: 100%; margin: 0 !important; }
.research-detail-content div[align="center"] > video { flex: 1 1 240px; min-width: 0; width: min(100%, 470px); }
.research-detail-content figcaption { font-family: inherit !important; font-size: .78em !important; line-height: 1.5; margin-top: .5rem; }
.research-detail-content hr { margin: 1.25rem 0; border-color: #dce3e2; }
@media (max-width: 700px) {
  .research-topic-top { grid-template-columns: minmax(0, 1fr); gap: 1.2rem; }
  .research-figure img { height: 190px; }
  .research-expand > summary { margin-left: 0; min-height: 44px; padding: .6rem 0; }
  .research-topic { padding: 1.5rem 0; }
  .research-page .research-summary { font-size: .94em; }
  .research-page .research-tags, .research-paper { font-size: .82em; }
  .research-detail-content { padding: 1rem; }
}
@media print {
  .research-topic { break-inside: avoid; }
  .research-figure img { height: 130px; }
}

.research-sr-only { position: absolute; width: 1px; height: 1px; padding: 0; margin: -1px; overflow: hidden; clip: rect(0, 0, 0, 0); white-space: nowrap; border: 0; }
</style>

<div class="research-page">
  <div class="research-intro">
    <p class="research-lead">I develop control and estimation methods for autonomous systems that must operate safely under cyberattacks, uncertainty, and limited energy resources.</p>
    <p class="research-context">My Ph.D. research at Purdue University connects resilient multi-agent autonomy, nonlinear UAV control, and battery-aware coordination.</p>
  </div>
  <details class="research-map">
    <summary>View the research overview diagram</summary>
    <a href="/images/Research_Figure.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size research overview diagram (new tab)"><img src="/images/Research_Figure.png" alt="Overview diagram of my research on multi-agent systems, UAV control, and energy-aware autonomy." loading="lazy" decoding="async"></a>
  </details>

<!-- RESEARCH 1: Edit the title and short summary below; detailed content follows. -->
<article class="research-topic" id="secure-autonomy" aria-labelledby="secure-autonomy-title">
  <div class="research-topic-top">
    <figure class="research-figure">
      <a href="/images/MAS.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Resilient Multi-Agent Autonomy (new tab)">
        <img src="/images/MAS.png" alt="Sensor attacks and their propagation through a network of cooperating UAVs." loading="eager" decoding="async">
      </a>
      <figcaption>Cyberattack resilience in networked systems</figcaption>
    </figure>
    <div class="research-copy">
      <p class="research-index">Research area 01</p>
      <h2 class="research-title" id="secure-autonomy-title">Resilient Multi-Agent Autonomy</h2>
      <p class="research-summary">I develop control and estimation methods for cooperating autonomous vehicles under sensor attacks. My work combines reactive attack mitigation with proactive, reachability-based assessment of potential collision risks.</p>
      <p class="research-tags">Resilient control · Sensor fusion · Reachability</p>
      <div class="research-paper">
        <a href="https://ieeexplore.ieee.org/abstract/document/11022616" target="_blank" rel="noopener noreferrer" aria-label="Selected paper on Resilient Multi-Agent Autonomy (new tab)">Selected paper <span aria-hidden="true">↗</span></a>
        <span>IEEE L-CSS, 2025</span>
      </div>
    </div>
  </div>
  <details class="research-expand">
    <summary>Research details &amp; publications<span class="research-sr-only">: Resilient Multi-Agent Autonomy</span></summary>
    <div class="research-detail-content">
<strong> Research Motivation: </strong> <br>
Multi-agent systems (MASs) have gained significant attention for their ability to solve complex engineering problems through cooperative decision-making. The primary objective in MAS operation is to achieve <strong>consensus</strong> among agents (e.g., UAVs, robots, and autonomous vehicles) to accomplish collaborative tasks. For example, urban air mobility (UAM) operations can be modeled as a MAS, where aerial vehicles coordinate their actions—such as formation control or velocity-matching consensus—by exchanging information (e.g., position and velocity) with neighboring agents. However, this communication-based structure also makes MASs inherently <strong>vulnerable</strong> to malicious threats, including cyberattacks, disturbances, and system faults. To address these challenges, my research focuses on developing advanced control and resilience mechanisms that enhance the safety and security of MASs operating in adversarial environments.

<hr>
<div style="text-align:center;">
  <img src="/images/MAS.png" alt="Sensor attacks and their propagation through a network of cooperating UAVs." style="width:60%" loading="lazy" decoding="async">
  <figcaption> Figure: System vulnerability (i.e., sensor disruptions and attack propagation via a network) of MASs under cyberattacks. </figcaption>
</div>
<hr>

The following is the summary of our ongoing research:

<h3> Reactive Multi-Agent System Defense Strategy </h3>

<p> <strong> Research Objective: </strong> <br>
In this research topic, we aim to design <strong> resilient control </strong> and <strong> estimation </strong> algorithms that can directly <strong> mitigate </strong> the impact of adversities. To this end, we developed resilient sensor fusion and estimation algorithms that can filter out the malicious data/information embedded in measurement output. The following videos show the realistic UAM operation in Greater Atlanta with four AVs conducting reference tracking control with formation flight. The left video shows the off-nominal UAM operation with a high risk of collisions. However, the right video shows the resilient UAM operation using our proposed method with high-assured safety.
</p>

<div align="center">
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="450" height="340" autoplay loop muted controls playsinline preload="metadata">
      <source src="/images/FDI_Off_Nominal.mp4" type="video/mp4">
    </video>
    <figcaption style="font-family:'Times New Roman'; font-size:14px;">
      (a) Off-Nominal Flight Scenario
    </figcaption>
  </figure>

  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="450" height="340" autoplay loop muted controls playsinline preload="metadata">
      <source src="/images/FDI_Resilient.mp4" type="video/mp4">
    </video>
    <figcaption style="font-family:'Times New Roman'; font-size:14px;">
      (b) Resilient Control under Sensor Fault
    </figcaption>
  </figure>
</div>

<hr>

<strong>Publications:</strong>
<ul style="margin-top:5px;">
<li> <small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, and Inseok Hwang, "<strong> <a href="https://mwcgt2024.northwestern.edu/posters/" target="_blank" rel="noopener noreferrer"> An Observer-Based Resilient Control Strategy for Leader-Follower Multi-Agent Systems Under False-Data-Injection Attacks </a> </strong>", <i>2024 Midwest Workshop in Control and Game Theory</i>, April 27–28, 2024, Northwestern University, Illinois, USA. </small> </li>

<li> <small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, Guanlin Wu, and Inseok Hwang, "<strong> <a href="https://ieeexplore.ieee.org/abstract/document/11022616" target="_blank" rel="noopener noreferrer"> Resilient Tracking Control For Leader-Follower Multi-Agent Systems Against Sinusoidal Sensor Attacks: An LMI-Based Framework </a> </strong>", <i>IEEE Control Systems Letters (L-CSS)</i>, vol. 9, pp. 1123-1128, June 2025. (Also presented at the 64nd IEEE Conference on Decision and Control.) </small> </li> </ul>

<hr>

<h3> Proactive Multi-Agent System Defense Strategy </h3>

<p> <strong> Research Objective: </strong> <br>
In this research topic, we focus on developing <strong> security metrics </strong> for multi-AVs that can measure the potential risk (e.g., collisions) by stealthy attacks. We specifically utilize an over-approximated ellipsoidal reachable set through the Lyapunov stability criterion. This reachable set (red-shaded ellipsoids) indicates the level of performance degradation (e.g., trajectory deviation) posed by attacks at certain future time steps. If there are overlaps between reachable sets, we can identify that associated AVs may have <strong> potential risks </strong> in terms of collisions during operation.</p>

<div align="center">
  <video width="470" height="360" autoplay loop muted controls playsinline preload="metadata">
  <source src ="/images/Risk_Assessment1.mp4" type="video/mp4">
  </video>
  <video width="470" height="360" autoplay loop muted controls playsinline preload="metadata">
  <source src ="/images/Risk_Assessment2.mp4" type="video/mp4">
  </video>
</div>

<hr>

<strong>Publications:</strong>
<ul style="margin-top:5px; padding-left:20px;">
<li> <small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, Sungsoo Kim, and Inseok Hwang, "<strong> <a href="https://ieeexplore.ieee.org/abstract/document/10153779" target="_blank" rel="noopener noreferrer"> An LMI-Based Risk Assessment of Leader-Follower Multi-Agent System Under Stealthy Cyberattacks </a> </strong>", <i>IEEE Control Systems Letters (L-CSS)</i>, vol. 7, pp. 2419–2424, 2023. (Also presented at the 62nd IEEE Conference on Decision and Control.) </small> </li>

<li> <small> Minhyun Cho, <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, and Inseok Hwang, "<strong> <a href="https://ieeexplore.ieee.org/abstract/document/10644803" target="_blank" rel="noopener noreferrer"> Risk Assessment of Multi-Agent System Under Denial-of-Service Cyberattacks Using Reachable Set Synthesis </a> </strong>", <i>2024 American Control Conference (ACC)</i>, pp. 1293–1298, Toronto, Canada, July 2024. </small> </li>

<li> <small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, and Inseok Hwang, "Proactive Risk Assessment of Multi-Agent Transportation Systems via Reachability Analysis against Stealthy Attacks", Accepted as a book chapter to <i>Advances in Transportation Cybersecurity and Resilience</i>, World Scientific Publishing. </small> </li> </ul>

<hr>
    </div>
  </details>
</article>

<!-- RESEARCH 2: Edit the title and short summary below; detailed content follows. -->
<article class="research-topic" id="uav-safety" aria-labelledby="uav-safety-title">
  <div class="research-topic-top">
    <figure class="research-figure">
      <a href="/images/UAV_Controller.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Safety-Critical UAV Control (new tab)">
        <img src="/images/UAV_Controller.png" alt="Quadrotor control architecture showing GPS spoofing attack channels." loading="lazy" decoding="async">
      </a>
      <figcaption>UAV safety under adversarial conditions</figcaption>
    </figure>
    <div class="research-copy">
      <p class="research-index">Research area 02</p>
      <h2 class="research-title" id="uav-safety-title">Safety-Critical UAV Control</h2>
      <p class="research-summary">I investigate how cyberattacks and model uncertainty affect UAV safety. This work connects reachability-based risk assessment with robust safety-filter design, including studies using Gazebo and PX4-ROS2.</p>
      <p class="research-tags">Safety filters · Control barrier functions · Risk assessment</p>
      <div class="research-paper">
        <a href="https://ieeexplore.ieee.org/abstract/document/11367661" target="_blank" rel="noopener noreferrer" aria-label="Selected paper on Safety-Critical UAV Control (new tab)">Selected paper <span aria-hidden="true">↗</span></a>
        <span>IEEE L-CSS, 2026</span>
      </div>
    </div>
  </div>
  <details class="research-expand">
    <summary>Research details &amp; publications<span class="research-sr-only">: Safety-Critical UAV Control</span></summary>
    <div class="research-detail-content">
<strong> Research Motivation: </strong> <br>
Ensuring the operational safety of Unmanned Aerial Vehicles (UAVs) is a fundamental challenge in modern aerospace systems. UAVs are vulnerable to various <strong>adversarial threats</strong>, including disturbances, wind gusts, and cyberattacks. For instance, GPS sensors can be compromised by spoofing attacks, which may significantly degrade navigation and trajectory-tracking performance. My research aim to develop safety-critical control and assurance algorithms that enhance the safety, reliability, and resilience of UAV systems operating in adversarial environments.

<hr>
<div style="text-align:center;">
  <img src="/images/UAV_Controller.png" alt="Quadrotor control architecture showing GPS spoofing attack channels." style="width:90%" loading="lazy" decoding="async">
  <figcaption> Figure: Control architecture of UAV and potential system vulnerability under cyberattacks. </figcaption>
</div>
<hr>

The following is the summary of our ongoing research:

<h3> Risk Assessment for UAVs under GPS Spoofing Attacks </h3>

<p> <strong> Research Objective: </strong> <br>
In this research, we develop a <strong> model-based risk assessment </strong> methodology for quadrotor UAVs under GPS spoofing attacks. These attacks represent particularly severe cyber threats due to their covert nature, allowing them to significantly degrade system performance without triggering alarms. To address this challenge, we propose a reachability-based security metric to quantify the extent of performance degradation caused by potential stealthy attacks. This methodology can be applicable to UAV tracking control operations in urban-like environments, where GPS sensors are highly susceptible to compromise by attackers.
</p>

<hr>
<div style="text-align:center;">
  <img src="/images/Risk1.png" alt="Reachability-based risk assessment results for a UAV under GPS spoofing." style="width:45%" loading="lazy" decoding="async">
  <img src="/images/Risk2.png" alt="Additional UAV reachability and risk assessment results." style="width:45%" loading="lazy" decoding="async">
</div>

<hr>

<strong>Publication:</strong>
<br>
<small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, and Inseok Hwang, "<strong><a href="https://ieeexplore.ieee.org/abstract/document/11367661" target="_blank" rel="noopener noreferrer">LMI-Driven Reachability Analysis for Fuzzy Model-Based Nonlinear Systems Subject to Norm-Bounded Input Perturbations </a></strong>", <i>IEEE Control System Letters (L-CSS)</i>, vol. 10, pp. 55-60, Jan. 2026. </small>

<hr>

<h3> UAV Safety-Filter Design through Control Barrier Function </h3>

<p> <strong> Research Objective: </strong> <br>
This research propose a safety-critical controller for nonlinear affine systems under actuator cyberattacks and model uncertainties. The approach combines a robust sliding mode-based control barrier function (SM-CBF) to address model uncertainties and an LSTM-based attack detector to identify compromised actuator channels. Conventional CBF controllers are sensitive to model dynamics, leading to safety violations under uncertainties and attacks. The proposed SM-CBF ensures safety despite these challenges, while the LSTM-based detector swiftly identifies compromised inputs. The methodology's effectiveness is demonstrated through quadrotor UAV stabilization in a high-fidelity simulator with Gazebo and PX4-ROS2.
</p>

<hr>
<div style="text-align:center;">
  <img src="/images/PX4.png" alt="Quadrotor safety-filter architecture with an SM-CBF and LSTM attack detector." style="width:55%" loading="lazy" decoding="async">
  <figcaption> Figure: Control architecture for quadrotor UAV using reconfigurable SM-CBF safety filter and LSTM-based attack detector. </figcaption>
</div>

<div align="center">
  <video width="600" height="400" autoplay loop muted controls playsinline preload="metadata">
  <source src ="/images/PX4.mp4" type="video/mp4">
  </video>
</div>

<hr>

<strong>Publication:</strong>
<br>
<small> Sungsoo Kim, Minhyun Cho, <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, and Inseok Hwang, "<strong><a href="https://arc.aiaa.org/doi/abs/10.2514/6.2025-2722" target="_blank" rel="noopener noreferrer">Safety-Critical Control for Nonlinear Affine System With Robustness and Attack Recovery</a></strong>", <i>AIAA SciTech 2025: Cybersecurity</i>, Orlando, Florida, Jan 2025. </small>
<hr>
    </div>
  </details>
</article>

<!-- RESEARCH 3: Edit the title and short summary below; detailed content follows. -->
<article class="research-topic" id="nonlinear-control" aria-labelledby="nonlinear-control-title">
  <div class="research-topic-top">
    <figure class="research-figure">
      <a href="/images/ts_fuzzy.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Nonlinear UAV Tracking Control (new tab)">
        <img src="/images/ts_fuzzy.png" alt="Fuzzy model representation of quadrotor dynamics connected to LMI-based controller design." loading="lazy" decoding="async">
      </a>
      <figcaption>From nonlinear dynamics to controller synthesis</figcaption>
    </figure>
    <div class="research-copy">
      <p class="research-index">Research area 03</p>
      <h2 class="research-title" id="nonlinear-control-title">Nonlinear UAV Tracking Control</h2>
      <p class="research-summary">I use fuzzy models to represent the nonlinear, coupled dynamics of quadrotor UAVs and design tracking controllers through linear matrix inequalities (LMIs). This framework links nonlinear system modeling with optimization-based controller synthesis.</p>
      <p class="research-tags">Fuzzy models · LMI synthesis · Trajectory tracking</p>
      <div class="research-paper">
        <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-1584" target="_blank" rel="noopener noreferrer" aria-label="Selected paper on Nonlinear UAV Tracking Control (new tab)">Selected paper <span aria-hidden="true">↗</span></a>
        <span>AIAA SciTech, 2026</span>
      </div>
    </div>
  </div>
  <details class="research-expand">
    <summary>Research details &amp; publications<span class="research-sr-only">: Nonlinear UAV Tracking Control</span></summary>
    <div class="research-detail-content">
<strong> Research Motivation: </strong> <br>
Unmanned Aerial Vehicles (UAVs) exhibit <strong> highly nonlinear </strong> and <strong>strongly coupled dynamics</strong> among attitude, altitude, and position states, making precise control inherently challenging. Conventional controllers (e.g., PID controllers) often fail to handle such nonlinearities and time-varying flight conditions effectively. To address these challenges, a fuzzy model-based intelligent control framework offers an efficient solution by approximating complex dynamics with a set of local linear models and adaptively blending them through fuzzy inference. This approach enhances robustness and adaptability across various flight modes. The effectiveness of this <strong>human inference-inspired control strategy</strong> is demonstrated through tracking control of a quadrotor UAV.
<br>

<hr>
<div style="text-align:center;">
  <img src="/images/ts_fuzzy.png" alt="Fuzzy model representation of quadrotor dynamics connected to LMI-based controller design." style="width:90%" loading="lazy" decoding="async">
  <figcaption> Figure: Control system architecture of a fuzzy model-based approach. </figcaption>
</div>

<div align="center">
  <!-- 왼쪽 비디오 -->
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="470" height="360" autoplay loop muted controls playsinline preload="metadata">
      <source src="/images/drone_sim.mp4" type="video/mp4">
    </video>
    <figcaption style="font-family:'Times New Roman'; font-size:14px; margin-top:6px;">
      (a) Quadrotor UAV tracking control in 3D representation
    </figcaption>
  </figure>

  <!-- 오른쪽 비디오 -->
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="470" height="360" autoplay loop muted controls playsinline preload="metadata">
      <source src="/images/drone_sim2.mp4" type="video/mp4">
    </video>
    <figcaption style="font-family:'Times New Roman'; font-size:14px; margin-top:6px;">
      (b) 2D representation
    </figcaption>
  </figure>
</div>
<hr>

<strong>Publications:</strong>
<br>
<small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, and Inseok Hwang, "<strong><a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-1584" target="_blank" rel="noopener noreferrer">LMI-Driven Tracking Control of Fuzzy Nonlinear Cyber-Physical Systems: Application to Quadrotor UAVs in Urban-Like Environment</a></strong>", <i>AIAA SciTech 2026: Intelligent Systems: Adaptive and Intelligent Control Systems</i>, Orlando, Florida. </small>

<hr>
    </div>
  </details>
</article>

<!-- RESEARCH 4: Edit the title and short summary below; detailed content follows. -->
<article class="research-topic" id="battery-estimation" aria-labelledby="battery-estimation-title">
  <div class="research-topic-top">
    <figure class="research-figure">
      <a href="/images/Koopman_SOC_Estimation.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Battery Modeling &amp; State Estimation (new tab)">
        <img src="/images/Koopman_SOC_Estimation.png" alt="Battery data transformed into a Koopman model and an LMI-based observer for state-of-charge estimation." loading="lazy" decoding="async">
      </a>
      <figcaption>Koopman-based battery state estimation</figcaption>
    </figure>
    <div class="research-copy">
      <p class="research-index">Research area 04</p>
      <h2 class="research-title" id="battery-estimation-title">Battery Modeling &amp; State Estimation</h2>
      <p class="research-summary">I develop Koopman-based models and LMI-based observers to estimate the state of charge of lithium-ion batteries. My work connects data-driven representations of nonlinear battery dynamics with control-theoretic observer design.</p>
      <p class="research-tags">Koopman operators · Data-driven modeling · SOC estimation · System identification</p>
      <div class="research-paper">
        <a href="https://asmedigitalcollection.asme.org/lettersdynsys/article-abstract/doi/10.1115/1.4072730/1235540/Koopman-Based-State-of-Charge-Observer-Design-for?redirectedFrom=fulltext" target="_blank" rel="noopener noreferrer" aria-label="Selected paper on Battery Modeling &amp; State Estimation (new tab)">Selected paper <span aria-hidden="true">↗</span></a>
        <span>ASME ALDSC, 2026</span>
      </div>
    </div>
  </div>
  <details class="research-expand">
    <summary>Research details &amp; publications<span class="research-sr-only">: Battery Modeling &amp; State Estimation</span></summary>
    <div class="research-detail-content">
<strong> Research Motivation: </strong> <br>
The operation of modern engineering systems such as electric vehicles, renewable energy storage, and electrified aircraft rely heavily on <strong>lithium-ion batteries</strong>. Accurately modeling these battery dynamics is essential for improving their operational safety, reliability, and performance. However, many of these systems exhibit nonlinear behaviors that are difficult to capture using traditional model-based approaches, such as equivalent circuit model. My research is motivated by the need for simple and reliable methods to understand and estimate such complex dynamics. Particularly, I focus on developing data-driven modeling, control, and estimation methods for battery dynamics using the Koopman operator framework.
<hr>

<div style="text-align:center;">
  <img src="/images/Koopman_SOC_Estimation.png" alt="Battery data transformed into a Koopman model and an LMI-based observer for state-of-charge estimation." style="width:95%" loading="lazy" decoding="async">
  <figcaption> Figure: Data-driven Koopman framework enabling stability-guaranteed SOC estimation via LMI-based observer design. </figcaption>
</div>
<hr>

<strong>Publications:</strong>
<ul style="margin-top:5px;">
<li> <small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Guanlin Wu, Minhyun Cho, Vishnu Vijay, and Inseok Hwang, "<strong><a href="https://asmedigitalcollection.asme.org/lettersdynsys/article-abstract/doi/10.1115/1.4072730/1235540/Koopman-Based-State-of-Charge-Observer-Design-for?redirectedFrom=fulltext" target="_blank" rel="noopener noreferrer">Koopman-Based State-of-Charge Observer Design for Lithium-Ion Batteries: An LMI-Based Framework</a></strong>", <i>ASME Letters in Dynamic Systems and Control (ALDSC)</i>, Accepted on June, 2026. </small> </li>

<li> <small> Guanlin Wu, <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Zhou Chen, and Inseok Hwang, "<strong>Deep Koopman-Style Framework for Cross-Temperature State-of-Charge Estimation of Lithium-Ion Batteries</strong>", <i>Modeling, Estimation and Control Conference (MECC 2026)</i>, Accepted on June, 2026. </small> </li>
</ul>

<hr>
    </div>
  </details>
</article>

<!-- RESEARCH 5: Edit the title and short summary below; detailed content follows. -->
<article class="research-topic" id="energy-aware-control" aria-labelledby="energy-aware-control-title">
  <div class="research-topic-top">
    <figure class="research-figure">
      <a href="/images/Energy-Aware.png" target="_blank" rel="noopener noreferrer" aria-label="Open full-size figure: Energy-Aware Multi-Agent Coordination (new tab)">
        <img src="/images/Energy-Aware.png" alt="Energy-aware consensus framework combining battery state of charge, interaction weights, and LMI-based control." loading="lazy" decoding="async">
      </a>
      <figcaption>Cooperative control with battery constraints</figcaption>
    </figure>
    <div class="research-copy">
      <p class="research-index">Research area 05</p>
      <h2 class="research-title" id="energy-aware-control-title">Energy-Aware Multi-Agent Coordination</h2>
      <p class="research-summary">I design cooperative controllers that account for the limited battery resources of multi-agent systems. The framework combines state-of-charge-dependent interaction weights with LMI-based observer and controller synthesis to incorporate battery safety into consensus control.</p>
      <p class="research-tags">Consensus control · Battery safety · Energy constraints</p>
      <div class="research-paper">
        <a href="https://ieeexplore.ieee.org/document/11663187" target="_blank" rel="noopener noreferrer" aria-label="Selected paper on Energy-Aware Multi-Agent Coordination (new tab)">Selected paper <span aria-hidden="true">↗</span></a>
        <span>IEEE L-CSS, 2026</span>
      </div>
    </div>
  </div>
  <details class="research-expand">
    <summary>Research details &amp; publications<span class="research-sr-only">: Energy-Aware Multi-Agent Coordination</span></summary>
    <div class="research-detail-content">
<strong> Research Motivation: </strong>
<br>
Multi-agent systems, such as UAM fleets and multi-robot teams, are typically powered by <strong>onboard batteries</strong> with limited energy capacity. Since each agent must operate within its energy budget to sustain mission-critical tasks, explicitly incorporating energy constraints into the cooperative control design is essential. Ignoring such constraints can lead to premature power depletion, degraded performance, or even mission failure. My research aims to develop energy-aware cooperative control strategies that enable multi-agent systems to accomplish collaborative tasks while ensuring safe and efficient energy consumption across all agents.

<hr>
<div style="text-align:center;">
  <img src="/images/Energy-Aware.png" alt="Energy-aware consensus framework combining battery state of charge, interaction weights, and LMI-based control." style="width:100%" loading="lazy" decoding="async">
  <figcaption> Figure: Energy-aware MAS consensus control framework — SOC-dependent interaction weights combined with LMI-based observer/controller synthesis to guarantee battery safety. </figcaption>
</div>
<hr>

<strong>Publications:</strong>
<br>
<small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Guanlin Wu, Minhyun Cho, and Inseok Hwang, "<strong><a href="https://ieeexplore.ieee.org/document/11663187" target="_blank" rel="noopener noreferrer">Energy-Aware Consensus Control for Multi-Agent Systems with Guaranteed Battery Safety via H-Infinity LMI Design</a></strong>," <i>IEEE Control Systems Letters (L-CSS)</i>, vol. 10, pp. 2293-2298, Aug. 2026. </small>
<hr>
    </div>
  </details>
</article>
</div>
<script data-research-autoplay>
// Start demonstrations when their research section opens; pause when it closes.
document.querySelectorAll('.research-page .research-expand').forEach(function (section) {
  var videos = section.querySelectorAll('video');
  function syncPlayback() {
    videos.forEach(function (video) {
      if (section.open) {
        video.muted = true;
        var playback = video.play();
        if (playback) playback.catch(function () { /* Keep manual controls available. */ });
      } else {
        video.pause();
      }
    });
  }
  section.addEventListener('toggle', syncPlayback);
  syncPlayback();
});
</script>
