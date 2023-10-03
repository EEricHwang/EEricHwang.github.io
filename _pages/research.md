---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on the development of control strategies tailered for cyber-physical systems (CPSs) within the realm of aerial engineering. I'm dedicated to enhancing the system's <strong> robustness </strong> and <strong> resilience </strong>. These systems are of paramount importance since they bear direct implications for human safety. 

The design of aerial engineering control systems necessitate sophisticated solutions owing to their heightened intricacy and the paramount importance of safety considerations. Absent these solutions, a multitude of risks to human life and property damage would ensue. For instance, modern aerial control systems, like those utilized in Urban Air Mobility (UAM), place a substantial reliance on the uninterrupted flow of information enabled by communication networks (such as 5G, 6G, Wi-Fi, etc.), which connect aerial vehicles (AVs) to ground control stations. Nonetheless, these communication networks could be vulnerable to cyberattacks, potentially resulting in detrimental scenarios, such as collisions and accidents involving AVs.

As a control engineer, my objective throughout my Ph.D. studies is to ensure the safety and optimal performance of these aerial systems. I'm committed to addressing the challenges posed by intricate interplay between technology, safety, and performance in the context of control theory and aerial engineering. 

<hr>
A Proactive Risk Assessment Methodology based on Reachability and its Application to Multi-Agent Systems
------
<div id="dots" style="display:inline"> <strong> Multi-agent systems (MASs) </strong> have received great attention thanks to their capabilities to perform difficult/complext missions compared to single-agent systmes. Each agent of a MAS has a distributed control protocol based on the local information obtained from its neighbors, which allows the MAS to be scalable and efficient. Therefore, these advantages have led to the prosperous development of MAS engineering applications, such as multi-robots, autonomous vehicles, and unmanned aerial vehicles (UAVs). Nevertheless, system <strong> vulnerability </strong> of MASs to malicious threats, particularly in the form of cyberattacks, can pose a substantial concern. These threats have the potential to compromise the performance and overall safety of MASs. As such, there arises a need to develop a risk assessment methodology tailored to MASs operating in the presence of cyberattacks. Such an approach is critical for enhancing the <strong> security </strong> and <strong> safety </strong> of MASs. </div>

<div id="more" style="display:none">
In contrast to single-agent systems, MASs exhibit a distinctive feature wherein the functionality and mission execution of MASs are profoundly reliant on inter-agent communication. For instance, in the context of UAM, the major tasks of aerial vehicles (AVs) in an urbain environment would be cargo delivery, passenger transporation, and medical service. To increase the operational efficiency, AVs will maintain formation control by sharing their vehicle's information (e.g., position and velocity) to achieve it.

<hr>  
<div style="text-align:center;">
  <img src="/images/Multi-Agent-System.png" alt="MAS" style="width:60%">
  <figcaption> Figure 1: An illustration of the operation of MAS in an urban environment. </figcaption>
</div>
<hr>  

Nevertheless, strong reliance of communication between AVs could give rise to the system vulnerabilities toward cyberattacks (e.g., denial-of-sertive (DoS), false-data-injection (FDI), stealthy attacks, etcs.). These malicious incursions may disrupt the integrity of information exchange among AVs, potentially jeopardizing their abilities to achieve their designed tasks. Consequently, in the MAS, computer science, and control communities, numerous research have been studied to reactively mitigate/reduce the detrimental effects of cyber threats. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Attack.png" alt="MAS" style="width:60%">
  <figcaption> Figure 2: An impact of cyberattacks during the operation of MAS. </figcaption>
</div>
<hr>  

One of the drawback of the previous studies, from a defender's perspective, lies in the fact that mitigation strategies are triggered after the detection of an attack occurence. However, these reactive strategies may not fully guarantee the system's safety in the presence of attacks. Since the safety of aerial systems, like UAM, is critically related to human's lives and properties, focusing on mitigation/defense strategies that operate 
preemtively, before the identification of attack occurrence, is necessary.  

<hr>  
Building upon the above discussion, this research focuses on the development of reachability-based proactive risk assessment strategy under cyberattacks. Based on the assumptions regarding the attack sceanrios (e.g., types of attack vectors, norm-bounded condition, etc.) and reachability concept, we can mathematically measure how much cyberattacks can potentially impact the performance of MASs within a certain time window. The measurement from our methodology can be represented by an over-approximated ellipsoid, where this technique is well-aligned with control theory and application of optimizations. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Reach.png" alt="MAS" style="width:60%">
  <figcaption> Figure 3: A proactive risk assessment with an over-approximated ellipsoidal-based reachable set. </figcaption>
</div>
<hr>  

</div>

<hr style="height:2pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn">Read more +</btn> 

<hr>
Resilient Control for Urban Air Mobility Applications against Cyberattacks
------

<hr>
Safety-Critical-Control via Control Barrier Functions (CBFs)
------


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



