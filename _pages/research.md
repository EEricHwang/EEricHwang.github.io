---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on developing advanced control and estimation algorithms for aerospace systems, considering operational <strong>safety</strong>, <strong>optimality</strong>, and <strong>performance</strong> in adversarial environments. The following are my research topics during my Ph.D. studies:



<h2> Secure Autonomy and Control for Multi-Agent System </h2>
<hr>  
<div id="dots" style="display:inline"> This research aims to enhance the safety and security of the operation of multi-agent systems. </div>
<div id="more" style="display:none"> <strong> Introduction: </strong> Multi-agent systems (MASs) have recently gained significant attention for their ability to solve complex engineering problems. The main goal in operating MASs is to achieve <strong> consensus </strong> among agents (e.g., UAVs, robots, autonomous vehicles) to satisfy their collaborative objectives. For instance, the vehicle dynamics for urban air mobility (UAM) operation can be represented through MAS, where UAM aerial vehicles (AVs) can achieve their UAM missions (e.g., formation control and velocity-matching consensus) by exchanging their information (position and velocity) with neighbors. Therefore, the communication between agents plays a significant role in the operation of MASs. However, this communication-based structure results in MASs being <strong> vulnerable </strong> to various malicious entities, such as cyberattacks, disturbances, and system faults. Therefore, it is important to develop advanced control algorithms to enhance the safety and security of MASs despite those threats.

<hr>  
<div style="text-align:center;">
  <img src="/images/MAS.png" alt="MAS" style="width:60%">
  <figcaption> Figure: A system vulnerability (i.e., sensor disruptions and attack propagation via a network) of MASs under cyberattacks. </figcaption>
</div>
<hr>  

The following is the summary of our ongoing research:

<h2> Reactive Multi-Agent Defense Strategy </h2>

<p> <strong> Objective: </strong> In this research topic, we aim to design <strong> resilient control </strong> and <strong> estimation </strong> algorithms that can directly <strong> mitigate </strong> the impact of adversities. To this end, we developed resilient sensor fusion and estimation algorithms that can filter out the malicious data/information embedded in measurement output. The following videos show the realistic UAM operation in Greater Atlanta with four AVs conducting reference tracking control with formation flight. The left video shows the off-nominal UAM operation with a high risk of collisions. However, the right video shows the resilient UAM operation using our proposed method with high-assured safety. 
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
<small> <strong>S. Hwang</strong>, M. Cho, and I. Hwang, "An Observer-Based Resilient Control Strategy for Leader-Follower Multi-Agent Systems Under False-Data-Injection Attacks", <i>2024 Midwest Workshop in Control and Game Theory</i>, April 27-28, 2024, Northwestern University, Illinois, USA. </small>
<hr>  


<h2> Proactive Multi-Agent Defense Strategy </h2>

<p> <strong> Objective: </strong> In this research topic, we focus on developing <strong> security metrics </strong> for multi-AVs that can measure the potential risk (e.g., collisions) by stealthy attacks. We specifically utilize an over-approximated ellipsoidal reachable set through the Lyapunov stability criterion. This reachable set (red-shaded ellipsoids) indicates the level of performance degradation (e.g., trajectory deviation) posed by attacks at certain future time steps. If there are overlaps between reachable sets, we can identify that associated AVs may have <strong> potential risks </strong> in terms of collisions during operation.</p>

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
<small> <strong>S. Hwang</strong>, M. Cho, S. Kim, and I. Hwang, "An LMI-Based Risk Assessment of Leader-Follower Multi-Agent System Under Stealthy Cyberattacks." <i>IEEE Control Systems Letters</i>, vol. 7, pp. 419-2424, 2023 (also presented at the 62nd IEEE Conference on Decision and Control). </small>
<br>
<small> M, Cho, <strong>S. Hwang</strong>, and I. Hwang, "Risk Assessment of Multi-Agent System Under Denial-of-Service Cyberattacks Using Reachable Set Synthesis." <i>2024 American Control Conference (ACC)</i>, pp. 1293-1298. IEEE, Toronto, Canada, July. 2024.</small>
<hr>  

<!-- 
<h2> [3] Multi-Vehicle Coordination with Network Connectivity </h2>

<p> <strong> Objective: </strong> In this research topic, TBD... </p>
-->

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn"><strong>Read more +</strong></btn> 

 
<h2> Safety-Critical Control and Assurance for Unmanned Aerial Vehicle </h2>
<hr>  
<div id="dot2" style="display:inline"> This research aims to enhance the operational safety of UAVs under adversarial environments. </div>
<div id="mor2" style="display:none"> <strong> Introduction: </strong> One of the key aspects of researching Unmanned Aerial Vehicles (UAVs) is <strong> <i> how to enhance or fully guarantee their operational safety? </i> </strong> UAVs are particularly vulnerable to various malicious threats, such as disturbances, wind gusts, and cyberattacks. For example, in terms of cybersecurity, GPS sensors on UAVs can be easily compromised by cyberattacks, leading to significant degradation in operational performance, such as tracking a destination. To address this challenge, we aim to develop safety-critical control and assurance algorithms to enhance the operational safety of UAVs.

<hr>  
<div style="text-align:center;">
  <img src="/images/UAV_Controller.png" alt="MAS" style="width:75%">
  <figcaption> Figure: A control architecture of UAV and potential system vulnerability under cyberattacks. </figcaption>
</div>
<hr>

The following is the summary of our ongoing research:

<h2> Risk Assessment for UAVs under GPS Stealthy Attacks </h2>

<p> <strong> Objective: </strong> In this research, we aim to develop a <strong> model-based risk assessment </strong> methodology for quadrotor UAVs under GPS stealthy attacks. These attacks represent particularly severe cyber threats due to their covert nature, allowing them to significantly degrade system performance without triggering alarms. To address this challenge, we propose a reachability-based security metric to quantify the extent of performance degradation caused by potential stealthy attacks. This methodology can be applicable to UAV tracking control operations in urban-like environments, where GPS sensor values are highly susceptible to compromise by attackers. 
</p>

<hr>  
<div style="text-align:center;">
  <img src="/images/Risk1.png" alt="MAS" style="width:40%">
  <img src="/images/Risk2.png" alt="MAS" style="width:40%">
</div>
<br>

<strong>Publication:</strong>
<br>
<small> <strong>S. Hwang</strong>, M. Cho, S. Kim, and I. Hwang, "An LMI-Based Risk Assessment of Leader-Follower Multi-Agent System Under Stealthy Cyberattacks." <i>IEEE Control Systems Letters</i>, vol. 7, pp. 419-2424, 2023 (also presented at the 62nd IEEE Conference on Decision and Control). </small>
<hr>  

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction2()" id="myBt2"><strong>Read more +</strong></btn> 



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
  
</script>

{% include base_path %}



