---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on developing advanced control and estimation algorithms for aerospace systems, considering operational <strong>safety</strong>, <strong>optimality</strong>, and <strong>performance</strong> in adversarial environments. The following are my research topics during my Ph.D. studies:

<h2> Secure Autonomy for Multi-Agent System </h2>
<hr>  
<div id="dots" style="display:inline"> This research aims to enhance the safety and security of the operation of multi-agent systems. </div>
<div id="more" style="display:none"> <strong> Introduction: </strong> Multi-agent systems (MASs) have recently gained significant attention for their ability to solve complex engineering problems. The main goal in operating MASs is to achieve <strong> consensus </strong> among agents (e.g., UAVs, robots, autonomous vehicles) to satisfy their collaborative objectives. For instance, the vehicle dynamics for urban air mobility (UAM) operation can be represented through MAS, where UAM aerial vehicles (AVs) can achieve their UAM missions (e.g., formation control and velocity-matching consensus) by exchanging their information (position and velocity) with neighbors. Therefore, the communication between agents plays a significant role in the operation of MASs. However, this communication-based structure results in MASs being <strong> vulnerable </strong> to various malicious entities, such as cyberattacks, disturbances, and system faults. Therefore, it is important to develop advanced control algorithms to enhance the safety and security of MASs despite those threats.

<hr>  
<div style="text-align:center;">
  <img src="/images/MAS.png" alt="MAS" style="width:50%">
  <figcaption> Figure: A system vulnerability (i.e., sensor disruptions and attack propagation via a network) of MASs under cyberattacks. </figcaption>
</div>
<hr>  

The following is the summary of our ongoing research:

<h2> [1] Reactive Multi-Agent Defense Strategy </h2>

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

<h2> [2] Proactive Multi-Agent Defense Strategy </h2>

<p> <strong> Objective: </strong> In this research topic, we focus on developing <strong> security metrics </strong> for multi-AVs that can measure the potential risk (e.g., collisions) by stealthy attacks. We specifically utilize an over-approximated ellipsoidal reachable set through the Lyapunov stability criterion. This reachable set (red-shaded ellipsoids) indicates the level of performance degradation (e.g., trajectory deviation) posed by attacks at certain future time steps. If there are overlaps between reachable sets, we can identify that associated AVs may have <strong> potential risks </strong> in terms of collisions during operation.</p>

<div align="center">
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment1.mp4" type="video/mp4">
  </video>
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment2.mp4" type="video/mp4">
  </video>
</div>

<h2> [3] Multi-Vehicle Coordination with Network Connectivity </h2>

<p> <strong> Objective: </strong> In this research topic, TBD... </p>

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn"><strong>Read more +</strong></btn> 




 
<h2> Safety-Critical Control for Unmanned Aerial Vehicle </h2>
<hr>  
<div id="dot2" style="display:inline"> Providing intelligent algorithms to manage the ever-increasing demand of air traffic and airspace congestion is critical to the efficiency and economic viability of air transportation systems. My research in the air traffic management domain involved applying machine learning tools to detect anomalous behvior (through unsupervised learning) and subsequently detect their precursors (through supervised learning). The algorithms were deployed on a testbed, and demonstrated as an online anomaly monitoring and mitigation tools for real air-traffic surveillance data from the terminal airspace operations of the New York metroplex.
</div>

<div id="mor2" style="display:none"> Providing intelligent algorithms to manage the ever-increasing demand of air traffic and airspace congestion is critical to the efficiency and economic viability of air transportation systems. During my masters program, I undertook research in this domain for a project titled 'Intent-Based Data Mining for Identifying and Classifying Conflict Detection and Resolution from Historical Aircraft Track Data', which coupled together the concepts of machine learning and air traffic management. The project involved applying machine learning techniques to find patterns in trajectory-based operations, and mimic the responses of air traffic controllers and pilots to en-route conflicts. Initially starting with off-the-shelf toolboxes to analyze the aviation datasets, we realized that basic toolboxes like Support Vector Machines and Neural Networks were incapable of learning the intricacies and variabilities of human responses in this context. Therefore, we developed a novel feature-weighted approach to learning, which improved the performance of the supervised learning process. This project exposed me to the inherent challenges of implementing mathematical techniques to such practical systems and motivated me to delve deeper into this field.
<br>

During my Ph.D., I researched anomaly detection in aviation datasets, where the anomalies are closely tied to operational or safety issues in the terminal airspace. Inspired by the <a href="http://icrat.org/ICRAT/seminarContent/2018/papers/ICRAT_2018_paper_39.pdf">work</a> of a colleague, I developed a human-interpretable anomaly detection algorithm — called <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2019-0682" title="Anomaly Detection Using Temporal Logic Based Learning for Terminal Airspace Operations @ SciTech 2019">TempAD</a> — relying on unsupervised machine learning techniques to aid the visualization of anomaly detection models in the physical space. Considering that aviation operations are periodic, I developed a recursive data-driven anomaly detection algorithm — called <a href="https://arc.aiaa.org/doi/10.2514/1.I010711" title="Incremental-Learning-Based Unsupervised Anomaly Detection Algorithm for Terminal Airspace Operations @ JAIS">TempAD-OU</a> (for Overnight Update) — that was capable of maintaining an anomaly detection model library and incrementally adapting it to newly recorded data. This research focused on finding abnormal behavior in the terminal airspace; a complementary problem and a natural next-step is prognosis, i.e., determining the causes — called precursors — for these behaviors in the same dataset. For this purpose, I developed a precursor detection algorithm — called <a href="https://arc.aiaa.org/doi/10.2514/1.D0182" title="Reactive Temporal Logic-Based Precursor Detection Algorithm for Terminal Airspace Operations @ JAT">reactive TempAD</a> — through a supervised learning approach. During recent months, I have been focusing on enhancing these algorithms to be applied to real-time streaming data, so that they can potentially be used as online anomaly monitoring and mitigation tools.

</div>

<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction2()" id="myBt2">Read more +</btn> 

<h2> Fuzzy Inference-Based Nonlinear System Identification & Control </h2>
<hr>  


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
    btnText2.innerHTML = "Read more +"; 
    moreText2.style.display = "none";
  } else {
    dots2.style.display = "none";
    btnText2.innerHTML = "Read less -"; 
    moreText2.style.display = "inline";
  }
}
  
</script>

{% include base_path %}



