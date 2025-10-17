---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on developing advanced control and estimation algorithms for aerospace systems, considering operational <strong>safety</strong>, <strong>optimality</strong>, and <strong>performance</strong> in adversarial environments. The following are my research topics during my PhD studies:

<!-- 
Section 1
-->

<h2> Secure Autonomy and Control for Multi-Agent Systems </h2>
<hr>  
<div id="dots" style="display:inline"> This research aims to enhance the safety and security of the operation of multi-agent systems. </div>
<div id="more" style="display:none"> <strong> Research Motivation: </strong> <br> 
Multi-agent systems (MASs) have recently gained significant attention for their ability to solve complex engineering problems. The main goal in operating MASs is to achieve <strong> consensus </strong> among agents (e.g., UAVs, robots, autonomous vehicles) to satisfy their collaborative objectives. For instance, the vehicle dynamics for urban air mobility (UAM) operation can be represented through MAS, where UAM aerial vehicles (AVs) can achieve their UAM missions (e.g., formation control and velocity-matching consensus) by exchanging their information (position and velocity) with neighbors. Therefore, the communication between agents plays a significant role in the operation of MASs. However, this communication-based structure results in MASs being <strong> vulnerable </strong> to various malicious entities, such as cyberattacks, disturbances, and system faults. Therefore, it is important to develop advanced control algorithms to enhance the safety and security of MASs despite those threats.

<hr>  
<div style="text-align:center;">
  <img src="/images/MAS.png" alt="MAS" style="width:60%">
  <figcaption> Figure: A system vulnerability (i.e., sensor disruptions and attack propagation via a network) of MASs under cyberattacks. </figcaption>
</div>
<hr>  

The following is the summary of our ongoing research:

<h2> Reactive Multi-Agent System Defense Strategy </h2>

<p> <strong> Objective: </strong> <br>
In this research topic, we aim to design <strong> resilient control </strong> and <strong> estimation </strong> algorithms that can directly <strong> mitigate </strong> the impact of adversities. To this end, we developed resilient sensor fusion and estimation algorithms that can filter out the malicious data/information embedded in measurement output. The following videos show the realistic UAM operation in Greater Atlanta with four AVs conducting reference tracking control with formation flight. The left video shows the off-nominal UAM operation with a high risk of collisions. However, the right video shows the resilient UAM operation using our proposed method with high-assured safety. 
</p>

<div align="center">
  <video width="450" height="340" autoplay loop muted>
  <source src ="/images/FDI_Off_Nominal.mp4" type="video/mp4">
  </video>
  <video width="450" height="340" autoplay loop muted>
  <source src ="/images/FDI_Resilient.mp4" type="video/mp4">
  </video>
</div>
<br>

<strong>Publication:</strong>
<br>
<small> <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, M. Cho, and I. Hwang, "An Observer-Based Resilient Control Strategy for Leader-Follower Multi-Agent Systems Under False-Data-Injection Attacks", <i>2024 Midwest Workshop in Control and Game Theory</i>, April 27-28, 2024, Northwestern University, Illinois, USA. </small>
<br>
<small> <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, M. Cho, G, Wu, and I. Hwang, "Resilient Tracking Control For Leader-Follower Multi-Agent Systems Against Sinusoidal Sensor Attacks: An LMI-Based Framework", <i>IEEE Control Systems Letters</i>, June. 2025. </small>
<hr>  


<h2> Proactive Multi-Agent System Defense Strategy </h2>

<p> <strong> Objective: </strong> <br>
In this research topic, we focus on developing <strong> security metrics </strong> for multi-AVs that can measure the potential risk (e.g., collisions) by stealthy attacks. We specifically utilize an over-approximated ellipsoidal reachable set through the Lyapunov stability criterion. This reachable set (red-shaded ellipsoids) indicates the level of performance degradation (e.g., trajectory deviation) posed by attacks at certain future time steps. If there are overlaps between reachable sets, we can identify that associated AVs may have <strong> potential risks </strong> in terms of collisions during operation.</p>

<div align="center">
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment1.mp4" type="video/mp4">
  </video>
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment2.mp4" type="video/mp4">
  </video>
</div>
<br>

<strong>Publication:</strong>
<br>
<small> <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, M. Cho, S. Kim, and I. Hwang, "An LMI-Based Risk Assessment of Leader-Follower Multi-Agent System Under Stealthy Cyberattacks." <i>IEEE Control Systems Letters</i>, vol. 7, pp. 419-2424, 2023 (also presented at the 62nd IEEE Conference on Decision and Control). </small>
<br>
<small> M, Cho, <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, and I. Hwang, "Risk Assessment of Multi-Agent System Under Denial-of-Service Cyberattacks Using Reachable Set Synthesis." <i>2024 American Control Conference (ACC)</i>, pp. 1293-1298. IEEE, Toronto, Canada, July. 2024.</small>
<br>
<small> <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, M. Cho, and I. Hwang, "Proactive Risk Assessment of Multi-Agent Transportation
Systems via Reachability Analysis against Stealthy Attacks." Submitted to the book chapter for <i>Advances in Transportation Cybersecurity and Resilience</i> in World Scientific Publishing.</small>
<hr>  

<!-- 
<h2> [3] Multi-Vehicle Coordination with Network Connectivity </h2>

<p> <strong> Objective: </strong> In this research topic, TBD... </p>
-->

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn"><strong>Read more +</strong></btn> 

<!-- 
Section 2
-->
 
<h2> Safety-Critical Control and Assurance for Unmanned Aerial Vehicles </h2>
<hr>  
<div id="dot2" style="display:inline"> This research aims to enhance the operational safety of unmanned aerial vehicles (UAVs) under adversarial environments. </div>
<div id="mor2" style="display:none"> <strong> Research Motivation: </strong> <br>
One of the key aspects of researching Unmanned Aerial Vehicles (UAVs) is <strong> <i> how to enhance or fully guarantee their operational safety? </i> </strong> UAVs are particularly vulnerable to various malicious threats, such as disturbances, wind gusts, and cyberattacks. For example, in terms of cybersecurity, GPS sensors on UAVs can be easily compromised by cyberattacks, leading to significant degradation in operational performance, such as tracking a destination. To address this challenge, we aim to develop safety-critical control and assurance algorithms to enhance the operational safety of UAVs.

<hr>  
<div style="text-align:center;">
  <img src="/images/UAV_Controller.png" alt="MAS" style="width:75%">
  <figcaption> Figure: A control architecture of UAV and potential system vulnerability under cyberattacks. </figcaption>
</div>
<hr>

The following is the summary of our ongoing research:

<h2> Risk Assessment for UAVs under GPS Spoofing Attacks </h2>

<p> <strong> Objective: </strong> <br>
In this research, we aim to develop a <strong> model-based risk assessment </strong> methodology for quadrotor UAVs under GPS stealthy attacks. These attacks represent particularly severe cyber threats due to their covert nature, allowing them to significantly degrade system performance without triggering alarms. To address this challenge, we propose a reachability-based security metric to quantify the extent of performance degradation caused by potential stealthy attacks. This methodology can be applicable to UAV tracking control operations in urban-like environments, where GPS sensor values are highly susceptible to compromise by attackers. 
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/Risk1.png" alt="MAS" style="width:40%">
  <img src="/images/Risk2.png" alt="MAS" style="width:40%">
</div>
<br>

<strong>Publication:</strong> To be appear
<br>
<hr>  

<h2> UAV Safety-Filter Design through Control Barrier Function </h2>

<p> <strong> Objective: </strong> <br>
This research aims to propose a safety-critical controller for nonlinear affine systems under actuator cyberattacks and model uncertainties. The approach combines a robust sliding mode-based control barrier function (SM-CBF) to address model uncertainties and an LSTM-based attack detector to identify compromised actuator channels. Conventional CBF controllers are sensitive to model dynamics, leading to safety violations under uncertainties and attacks. The proposed SM-CBF ensures safety despite these challenges, while the LSTM-based detector swiftly identifies compromised inputs. The methodology's effectiveness is demonstrated through quadrotor UAV stabilization in a high-fidelity simulator with Gazebo and PX4-ROS2.
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/PX4.png" alt="MAS" style="width:55%">
  <figcaption> Figure: A control architecture for quadrotor UAV using reconfigurable SM-CBF safety filter and LSTM-based attack detector. </figcaption>
</div>

<div align="center">
  <video width="600" height="400" autoplay loop muted>
  <source src ="/images/PX4.mp4" type="video/mp4">
  </video>
</div>
<br>

<strong>Publication:</strong>
<br>
<small> S. Kim, M. Cho, <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, and I. Hwang, "Safety-Critical Control for Nonlinear Affine System With Robustness and Attack Recovery." <i>AIAA SciTech 2025 Forum</i>, Orlando, Florida, Jan 2025. </small>
<hr>  

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction2()" id="myBt2"><strong>Read more +</strong></btn> 

<!-- 
Section 3
-->

<h2> Tracking Control for Unmanned Aerial Vehicles using Fuzzy Model-Based Intelligent Control </h2>
<hr>  
<div id="dot2" style="display:inline"> This research aims to develop an advanced tracking control framework for UAVs using a fuzzy model–based intelligent control strategy. </div>
<div id="mor2" style="display:none"> <strong> Research Motivation: </strong> <br>
One of the key aspects of researching Unmanned Aerial Vehicles (UAVs) is <strong> <i> how to enhance or fully guarantee their operational safety? </i> </strong> UAVs are particularly vulnerable to various malicious threats, such as disturbances, wind gusts, and cyberattacks. For example, in terms of cybersecurity, GPS sensors on UAVs can be easily compromised by cyberattacks, leading to significant degradation in operational performance, such as tracking a destination. To address this challenge, we aim to develop safety-critical control and assurance algorithms to enhance the operational safety of UAVs.

<hr>  
<div style="text-align:center;">
  <img src="/images/UAV_Controller.png" alt="MAS" style="width:75%">
  <figcaption> Figure: A control architecture of UAV and potential system vulnerability under cyberattacks. </figcaption>
</div>
<hr>

The following is the summary of our ongoing research:

<h2> Risk Assessment for UAVs under GPS Stealthy Attacks </h2>

<p> <strong> Objective: </strong> <br>
In this research, we aim to develop a <strong> model-based risk assessment </strong> methodology for quadrotor UAVs under GPS stealthy attacks. These attacks represent particularly severe cyber threats due to their covert nature, allowing them to significantly degrade system performance without triggering alarms. To address this challenge, we propose a reachability-based security metric to quantify the extent of performance degradation caused by potential stealthy attacks. This methodology can be applicable to UAV tracking control operations in urban-like environments, where GPS sensor values are highly susceptible to compromise by attackers. 
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/Risk1.png" alt="MAS" style="width:40%">
  <img src="/images/Risk2.png" alt="MAS" style="width:40%">
</div>
<br>

<strong>Publication:</strong> To be appear
<br>
<hr>  

<h2> UAV Safety-Filter Design through Control Barrier Function </h2>

<p> <strong> Objective: </strong> <br>
This research aims to propose a safety-critical controller for nonlinear affine systems under actuator cyberattacks and model uncertainties. The approach combines a robust sliding mode-based control barrier function (SM-CBF) to address model uncertainties and an LSTM-based attack detector to identify compromised actuator channels. Conventional CBF controllers are sensitive to model dynamics, leading to safety violations under uncertainties and attacks. The proposed SM-CBF ensures safety despite these challenges, while the LSTM-based detector swiftly identifies compromised inputs. The methodology's effectiveness is demonstrated through quadrotor UAV stabilization in a high-fidelity simulator with Gazebo and PX4-ROS2.
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/PX4.png" alt="MAS" style="width:55%">
  <figcaption> Figure: A control architecture for quadrotor UAV using reconfigurable SM-CBF safety filter and LSTM-based attack detector. </figcaption>
</div>

<div align="center">
  <video width="600" height="400" autoplay loop muted>
  <source src ="/images/PX4.mp4" type="video/mp4">
  </video>
</div>
<br>

<strong>Publication:</strong>
<br>
<small> S. Kim, M. Cho, <span style="text-decoration: underline;"><strong>S. Hwang</strong></span>, and I. Hwang, "Safety-Critical Control for Nonlinear Affine System With Robustness and Attack Recovery." <i>AIAA SciTech 2025 Forum</i>, Orlando, Florida, Jan 2025. </small>
<hr>  

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction3()" id="myBt3"><strong>Read more +</strong></btn> 

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

  
</script>

{% include base_path %}



