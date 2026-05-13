---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My Ph.D. research focuses on developing advanced control and estimation algorithms for multi-agent systems, with an emphasis on operational <strong>safety</strong>, <strong>energy efficiency</strong>, <strong>optimality</strong>, and <strong>performance</strong> in adversarial environments in the context of aerospace applications. My Ph.D. research focuses on the following topics:

<div style="text-align:center;">
  <img src="/images/Research_New.png" alt="MAS" style="width:45%">
</div>

<!-- 
============================== Section 1 ==============================
-->

<h2> 1. Secure Autonomy and Control for Multi-Agent Systems </h2>
<hr>  
<div id="dots" style="display:inline"> This research aims to enhance the safety and security of the operation of multi-agent systems. </div>
<div id="more" style="display:none"> <strong> Research Motivation: </strong> <br> 
Multi-agent systems (MASs) have gained significant attention for their ability to solve complex engineering problems through cooperative decision-making. The primary objective in MAS operation is to achieve <strong>consensus</strong> among agents (e.g., UAVs, robots, and autonomous vehicles) to accomplish collaborative tasks. For example, urban air mobility (UAM) operations can be modeled as a MAS, where aerial vehicles coordinate their actions—such as formation control or velocity-matching consensus—by exchanging information (e.g., position and velocity) with neighboring agents. However, this communication-based structure also makes MASs inherently <strong>vulnerable</strong> to malicious threats, including cyberattacks, disturbances, and system faults. To address these challenges, my research focuses on developing advanced control and resilience mechanisms that enhance the safety and security of MASs operating in adversarial environments.

<hr>  
<div style="text-align:center;">
  <img src="/images/MAS.png" alt="MAS" style="width:60%">
  <figcaption> Figure: System vulnerability (i.e., sensor disruptions and attack propagation via a network) of MASs under cyberattacks. </figcaption>
</div>
<hr>  

The following is the summary of our ongoing research:

<h2> Reactive Multi-Agent System Defense Strategy </h2>

<p> <strong> Research Objective: </strong> <br>
In this research topic, we aim to design <strong> resilient control </strong> and <strong> estimation </strong> algorithms that can directly <strong> mitigate </strong> the impact of adversities. To this end, we developed resilient sensor fusion and estimation algorithms that can filter out the malicious data/information embedded in measurement output. The following videos show the realistic UAM operation in Greater Atlanta with four AVs conducting reference tracking control with formation flight. The left video shows the off-nominal UAM operation with a high risk of collisions. However, the right video shows the resilient UAM operation using our proposed method with high-assured safety. 
</p>

<div align="center">
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="450" height="340" autoplay loop muted>
      <source src="/images/FDI_Off_Nominal.mp4" type="video/mp4">
    </video>
    <figcaption style="font-family:'Times New Roman'; font-size:14px;">
      (a) Off-Nominal Flight Scenario
    </figcaption>
  </figure>

  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="450" height="340" autoplay loop muted>
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

<h2> Proactive Multi-Agent System Defense Strategy </h2>

<p> <strong> Research Objective: </strong> <br>
In this research topic, we focus on developing <strong> security metrics </strong> for multi-AVs that can measure the potential risk (e.g., collisions) by stealthy attacks. We specifically utilize an over-approximated ellipsoidal reachable set through the Lyapunov stability criterion. This reachable set (red-shaded ellipsoids) indicates the level of performance degradation (e.g., trajectory deviation) posed by attacks at certain future time steps. If there are overlaps between reachable sets, we can identify that associated AVs may have <strong> potential risks </strong> in terms of collisions during operation.</p>

<div align="center">
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment1.mp4" type="video/mp4">
  </video>
  <video width="470" height="360" autoplay loop muted>
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

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn"><strong>Read more +</strong></btn> 

<!-- 
============================== Section 2 ==============================
-->
 
<h2> 2. Safety-Critical Control and High-Assured Safety for Unmanned Aerial Vehicles </h2>
<hr>  
<div id="dot2" style="display:inline"> This research aims to enhance the operational safety of unmanned aerial vehicles (UAVs) under adversarial environments. </div>
<div id="mor2" style="display:none"> <strong> Research Motivation: </strong> <br>
Ensuring the operational safety of Unmanned Aerial Vehicles (UAVs) is a fundamental challenge in modern aerospace systems. UAVs are vulnerable to various <strong>adversarial threats</strong>, including disturbances, wind gusts, and cyberattacks. For instance, GPS sensors can be compromised by spoofing attacks, which may significantly degrade navigation and trajectory-tracking performance. My research aim to develop safety-critical control and assurance algorithms that enhance the safety, reliability, and resilience of UAV systems operating in adversarial environments.

<hr>  
<div style="text-align:center;">
  <img src="/images/UAV_Controller.png" alt="MAS" style="width:90%">
  <figcaption> Figure: Control architecture of UAV and potential system vulnerability under cyberattacks. </figcaption>
</div>
<hr>

The following is the summary of our ongoing research:

<h2> Risk Assessment for UAVs under GPS Spoofing Attacks </h2>

<p> <strong> Research Objective: </strong> <br>
In this research, we develop a <strong> model-based risk assessment </strong> methodology for quadrotor UAVs under GPS spoofing attacks. These attacks represent particularly severe cyber threats due to their covert nature, allowing them to significantly degrade system performance without triggering alarms. To address this challenge, we propose a reachability-based security metric to quantify the extent of performance degradation caused by potential stealthy attacks. This methodology can be applicable to UAV tracking control operations in urban-like environments, where GPS sensors are highly susceptible to compromise by attackers. 
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/Risk1.png" alt="MAS" style="width:45%">
  <img src="/images/Risk2.png" alt="MAS" style="width:45%">
</div>

<hr>

<strong>Publication:</strong> 
<br>
<small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, and Inseok Hwang, "<strong><a href="https://ieeexplore.ieee.org/abstract/document/11367661" target="_blank" rel="noopener noreferrer">LMI-Driven Reachability Analysis for Fuzzy Model-Based Nonlinear Systems Subject to Norm-Bounded Input Perturbations </a></strong>", <i>IEEE Control System Letters (L-CSS)</i>, vol. 10, pp. 55-60, Jan. 2026. </small>

<hr>  

<h2> UAV Safety-Filter Design through Control Barrier Function </h2>

<p> <strong> Research Objective: </strong> <br>
This research propose a safety-critical controller for nonlinear affine systems under actuator cyberattacks and model uncertainties. The approach combines a robust sliding mode-based control barrier function (SM-CBF) to address model uncertainties and an LSTM-based attack detector to identify compromised actuator channels. Conventional CBF controllers are sensitive to model dynamics, leading to safety violations under uncertainties and attacks. The proposed SM-CBF ensures safety despite these challenges, while the LSTM-based detector swiftly identifies compromised inputs. The methodology's effectiveness is demonstrated through quadrotor UAV stabilization in a high-fidelity simulator with Gazebo and PX4-ROS2.
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/PX4.png" alt="MAS" style="width:55%">
  <figcaption> Figure: Control architecture for quadrotor UAV using reconfigurable SM-CBF safety filter and LSTM-based attack detector. </figcaption>
</div>

<div align="center">
  <video width="600" height="400" autoplay loop muted>
  <source src ="/images/PX4.mp4" type="video/mp4">
  </video>
</div>

<hr>

<strong>Publication:</strong>
<br>
<small> Sungsoo Kim, Minhyun Cho, <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, and Inseok Hwang, "<strong><a href="https://arc.aiaa.org/doi/abs/10.2514/6.2025-2722" target="_blank" rel="noopener noreferrer">Safety-Critical Control for Nonlinear Affine System With Robustness and Attack Recovery</a></strong>", <i>AIAA SciTech 2025 Forum</i>, Orlando, Florida, Jan 2025. </small>
<hr>  

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction2()" id="myBt2"><strong>Read more +</strong></btn> 

<!-- 
============================== Section 3 ==============================
-->

<h2> 3. Tracking Control for Unmanned Aerial Vehicles using Fuzzy Model-Based Intelligent Control </h2>
<hr>  
<div id="dot3" style="display:inline"> This research aims to develop an advanced control algorithm for UAVs using fuzzy model-based intelligent control. </div>
<div id="mor3" style="display:none"> <strong> Research Motivation: </strong> <br> 
Unmanned Aerial Vehicles (UAVs) exhibit <strong> highly nonlinear </strong> and <strong>strongly coupled dynamics</strong> among attitude, altitude, and position states, making precise control inherently challenging. Conventional controllers (e.g., PID controllers) often fail to handle such nonlinearities and time-varying flight conditions effectively. To address these challenges, a fuzzy model-based intelligent control framework offers an efficient solution by approximating complex dynamics with a set of local linear models and adaptively blending them through fuzzy inference. This approach enhances robustness and adaptability across various flight modes. The effectiveness of this <strong>human inference-inspired control strategy</strong> is demonstrated through tracking control of a quadrotor UAV.
<br>
  
<hr> 
<div style="text-align:center;">
  <img src="/images/ts_fuzzy.png" alt="MAS" style="width:90%">
  <figcaption> Figure: Control system architecture of a fuzzy model-based approach. </figcaption>
</div>

<div align="center">
  <!-- 왼쪽 비디오 -->
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="470" height="360" autoplay loop muted>
      <source src="/images/drone_sim.mp4" type="video/mp4">
    </video>
    <figcaption style="font-family:'Times New Roman'; font-size:14px; margin-top:6px;">
      (a) Quadrotor UAV tracking control in 3D representation
    </figcaption>
  </figure>

  <!-- 오른쪽 비디오 -->
  <figure style="display:inline-block; text-align:center; margin:10px;">
    <video width="470" height="360" autoplay loop muted>
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
<small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Minhyun Cho, and Inseok Hwang, "<strong><a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-1584" target="_blank" rel="noopener noreferrer">LMI-Driven Tracking Control of Fuzzy Nonlinear Cyber-Physical Systems: Application to Quadrotor UAVs in Urban-Like Environment</a></strong>", <i>AIAA SciTech 2026 Forum</i>, Orlando, Florida. </small>

<hr>

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction3()" id="myBt3"><strong>Read more +</strong></btn> 

<!-- 
============================== Section 4 ==============================
-->

<h2> 4. Data-Driven Dynamics Modeling, Control, and Estimation for Battery Systems</h2>
<hr>  
<div id="dot4" style="display:inline"> This research aims to develop data-driven modeling, control, and estimation methods based on the Koopman approach, with a particular focus on battery dynamics. </div>
<div id="mor4" style="display:none"> <strong> Research Motivation: </strong> <br> 
The operation of modern engineering systems such as electric vehicles, renewable energy storage, and electrified aircraft rely heavily on <strong>lithium-ion batteries</strong>. Accurately modeling these battery dynamics is essential for improving their operational safety, reliability, and performance. However, many of these systems exhibit nonlinear behaviors that are difficult to capture using traditional model-based approaches, such as equivalent circuit model. My research is motivated by the need for simple and reliable methods to understand and estimate such complex dynamics. Particularly, I focus on developing data-driven modeling, control, and estimation methods for battery dynamics using the Koopman operator framework.
<hr>

<div style="text-align:center;">
  <img src="/images/Koopman_SOC_Estimation.png" alt="MAS" style="width:95%">
  <figcaption> Figure: Data-driven Koopman framework enabling stability-guaranteed SOC estimation via LMI-based observer design. </figcaption>
</div>
<hr>

<strong>Publications:</strong>
<ul style="margin-top:5px;">
<li> <small> <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Guanlin Wu, Minhyun Cho, Vishnu Vijay, and Inseok Hwang, "<strong>Koopman-Based State-of-Charge Observer Design for Lithium-Ion Batteries: An LMI-Based Framework</strong>", ASME Letters in Dynamic Systems and Control (with MECC 2026 option), (Submitted on March 14, 2026, under review) </small> </li>

<li> <small> Guanlin Wu, <span style="text-decoration: underline;"><strong>Sounghwan Hwang*</strong></span>, Z. Chen, and Inseok Hwang, "<strong>Deep Koopman-Style Framework for Cross-Temperature State-of-Charge Estimation of Lithium-Ion Batteries</strong>", Modeling, Estimation and Control Conference (MECC 2026), (Submitted on April 20, 2026, under review) </small> </li>
</ul>

<hr>

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction4()" id="myBt4"><strong>Read more +</strong></btn> 

<!-- 
============================== Section 5 ==============================
-->

<h2> 5. Energy-Aware and Cooperative Constrained Control for Multi-Agent Systems </h2>
<hr>  
<div id="dot5" style="display:inline"> This research aims to develop energy-aware control and coordination strategies for multi-agent systems with limited energy resources (e.g., onboard batteries). </div>
<div id="mor5" style="display:none"> 
<strong> Research Motivation: </strong> 
<br>
Multi-agent systems, such as UAM fleets and multi-robot teams, are typically powered by <strong>onboard batteries</strong> with limited energy capacity. Since each agent must operate within its energy budget to sustain mission-critical tasks, explicitly incorporating energy constraints into the cooperative control design is essential. Ignoring such constraints can lead to premature power depletion, degraded performance, or even mission failure. My research aims to develop energy-aware cooperative control strategies that enable multi-agent systems to accomplish collaborative tasks while ensuring safe and efficient energy consumption across all agents.

<hr>  
<div style="text-align:center;">
  <img src="/images/Constrained_MAS.png" alt="MAS" style="width:60%">
  <figcaption> Figure: Conceptual illustration of energy-aware and constraint-aware cooperative control for multi-agent systems. </figcaption>
</div>
<hr>  
  
</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction5()" id="myBt5"><strong>Read more +</strong></btn> 

<!-- 
Script...
-->

<script>
  
function myFunction1() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "<strong>Read more +</strong>"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "<strong>Read less -</strong>"; 
    moreText.style.display = "inline";
  }
}

function myFunction2() {
  var dots2 = document.getElementById("dot2");
  var moreText2 = document.getElementById("mor2");
  var btnText2 = document.getElementById("myBt2");

  if (dots2.style.display === "none") {
    dots2.style.display = "inline";
    btnText2.innerHTML = "<strong>Read more +</strong>"; 
    moreText2.style.display = "none";
  } else {
    dots2.style.display = "none";
    btnText2.innerHTML = "<strong>Read less -</strong>"; 
    moreText2.style.display = "inline";
  }
}

function myFunction3() {
  var dots3 = document.getElementById("dot3");
  var moreText3 = document.getElementById("mor3");
  var btnText3 = document.getElementById("myBt3");

  if (dots3.style.display === "none") {
    dots3.style.display = "inline";
    btnText3.innerHTML = "<strong>Read more +</strong>"; 
    moreText3.style.display = "none";
  } else {
    dots3.style.display = "none";
    btnText3.innerHTML = "<strong>Read less -</strong>"; 
    moreText3.style.display = "inline";
  }
}

function myFunction4() {
  var dots4 = document.getElementById("dot4");
  var moreText4 = document.getElementById("mor4");
  var btnText4 = document.getElementById("myBt4");

  if (dots4.style.display === "none") {
    dots4.style.display = "inline";
    btnText4.innerHTML = "<strong>Read more +</strong>"; 
    moreText4.style.display = "none";
  } else {
    dots4.style.display = "none";
    btnText4.innerHTML = "<strong>Read less -</strong>"; 
    moreText4.style.display = "inline";
  }
}

function myFunction5() {
  var dots5 = document.getElementById("dot5");
  var moreText5 = document.getElementById("mor5");
  var btnText5 = document.getElementById("myBt5");

  if (dots5.style.display === "none") {
    dots5.style.display = "inline";
    btnText5.innerHTML = "<strong>Read more +</strong>"; 
    moreText5.style.display = "none";
  } else {
    dots5.style.display = "none";
    btnText5.innerHTML = "<strong>Read less -</strong>"; 
    moreText5.style.display = "inline";
  }
}
  
</script>

{% include base_path %}



