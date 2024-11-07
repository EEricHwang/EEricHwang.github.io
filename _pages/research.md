---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on developing advanced control and estimation algorithms for aerial systems, considering operational <strong>safety</strong>, <strong>optimality</strong>, and <strong>performance</strong> in adversarial environments. The following are my research topics during my Ph.D. studies:

<h2> Cybersecurity of Multi-Agent System </h2>
<hr>  

<div id="dots" style="display:inline">The general idea of estimation is to derive the 'best estimate' for the true value of the state of some system from an incomplete, potentially noisy set of observations on that system. Distributed estimation extends this idea to obtain a state estimate using a network of communication-capable sensors, where the sensors can now correct each others' estimates and achieve overall improvement. My research in this area focuses on deriving 'optimal' target state estimates, applicable to both linear and hybrid state evolutions.</div>
<div id="more" style="display:none">The general idea of estimation is to derive the 'best estimate' for the true value of the state of some system from an incomplete, potentially noisy set of observations on that system. Distributed estimation extends this idea to obtain a state estimate using a network of communication-capable sensors, where the sensors can now correct each others' estimates and achieve overall improvement. In a founding consensus-based distributed estimation <a href="https://ieeexplore.ieee.org/abstract/document/5399678">article</a>, Olfati introduced a novel consensus-based update architecture for distributed estimation, albeit developing a sub-optimal version owing to the mathematical and implementational complexity involved in developing an optimal version. I devoted my time to research an <a href="https://ieeexplore.ieee.org/abstract/document/7963859" title="Optimal discrete-time Kalman consensus filter @ ACC2017">optimal form</a> of this Kalman consensus filter (OKCF), where the optimal gains resulted in the best possible MMSE estimate of the target. To improve the applicability of the optimal distributed estimator, I subsequently worked to enhance the algorithm to estimate the <a href="https://digital-library.theiet.org/content/journals/10.1049/iet-cta.2017.1208" title="Distributed State Estimation for a Stochastic Linear Hybrid System over a Sensor Network @ IET">hybrid states</a> of target evolving in a hybrid fashion using the Interacting Multiple Model concept.

During recent months, I have been involved in an investigation to modify the algorithm to allow the sensors to be '<a href="https://ieeexplore.ieee.org/abstract/document/9030070" title="Optimal Kalman Consensus Filter for Weighted Directed Graphs @ CDC2019">naïve</a>', in the sense that some sensors may not be able to obtain measurements from the target, but are relying just on communicated information.</div>
<hr style="height:1pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn">Read more +</btn> 

<h2> Safety-Critical Control for Unmanned Aerial Vehicle </h2>
<hr>  

<h2> Fuzzy Inference-Based Nonlinear System Identification & Control </h2>
<hr>  

The aerospace control systems necessitate advanced solutions due to the importance of safety considerations. 
Numerous safety violations (e.g., crashes and collisions) would occur without these solutions. For instance, aerial control systems for Urban Air Mobility (UAM) heavily rely on the uninterrupted flow of information enabled by vehicle-level communication networks (e.g., 5G, Wi-Fi, etc.) between Aerial Vehicles (AVs). 
However, these networks could be vulnerable to cyberattacks, potentially resulting in detrimental scenarios. 
Given the dynamic nature of urban environments, UAM AVs are also exposed to signal jamming, disturbances, and unexpected system failures. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Diagram.png" alt="MAS" style="width:40%">
  <figcaption> Figure: A balance between the system's performance, robustness, and resilience. </figcaption>
</div>

As a control engineer, my research objective is to achieve 1) robustness and 2) resiliency with high-assured system performance. 
I'm committed to addressing the challenges posed by the intricate interplay between technology, safety, and performance along with control theory and aerial engineering. 

<hr>
<h2> Reactive Multi-Vehicle Defense Strategy </h2>

<p> <strong> Objective: </strong> In this research topic, we aim to design resilient control/estimation algorithms that can directly mitigate the impact of adversities. To this end, we developed resilient sensor fusion and estimation algorithms that can filter out the malicious data/information embedded in measurement output. The following videos show the realistic UAM operation in Greater Atlanta with four AVs conducting reference tracking control with formation flight. The left video shows the off-nominal UAM operation with a high risk of collisions. However, the right video shows the resilient UAM operation using our proposed method with high-assured safety. 
</p>

<div align="center">
  <video width="450" height="340" autoplay loop muted>
  <source src ="/images/FDI_Off_Nominal.mp4" type="video/mp4">
  </video>
  <video width="450" height="340" autoplay loop muted>
  <source src ="/images/FDI_Resilient.mp4" type="video/mp4">
  </video>
</div>

<hr>
<h2> Proactive Multi-Vehicle Defense Strategy </h2>

<p> <strong> Objective: </strong> In this research topic, we focus on developing security metrics for multi-AVs that can measure the potential risk (e.g., collisions) by stealthy attacks. We specifically utilize an over-approximated ellipsoidal reachable set through the Lyapunov stability criterion. This reachable set (red-shaded ellipsoids) indicates the level of performance degradation (e.g., trajectory deviation) posed by attacks at certain future time steps. If there are overlaps between reachable sets, we can identify that associated AVs may have potential risks in terms of collisions during operation.

<div align="center">
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment1.mp4" type="video/mp4">
  </video>
  <video width="470" height="360" autoplay loop muted>
  <source src ="/images/Risk_Assessment2.mp4" type="video/mp4">
  </video>
</div>

<hr>
<h2> Secured Multi-Vehicle Coordination with Distributed Optimization </h2>

<p> <strong> Objective: </strong> TBD...



<script>
function myFunction1() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more +"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less -"; 
    moreText.style.display = "inline";
  }
}
</script>

{% include base_path %}



