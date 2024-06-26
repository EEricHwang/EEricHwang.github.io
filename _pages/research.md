---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on the development of control strategies for cyber-physical systems (CPSs) within the aerial engineering domain. I'm particularly interested in augmenting the <strong> robustness </strong> and <strong> resilience </strong> of these systems, recognizing their critical role in ensuring overall system safety. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Diagram.png" alt="MAS" style="width:40%">
  <figcaption> Figure: A balance between the system's performance, robustness, and resilience. </figcaption>
</div>
<hr>  

The design of aerial engineering control systems necessitates sophisticated solutions owing to their heightened intricacy and the paramount importance of safety considerations. Absent these solutions, a multitude of risks to human life and property damage would ensue. For instance, modern aerial control systems, like those utilized in Urban Air Mobility (UAM), place substantial reliance on the uninterrupted flow of information enabled by communication networks (e.g., 5G, 6G, Wi-Fi, etc.), which connect aerial vehicles (AVs) to ground control stations. Nonetheless, these communication networks could be vulnerable to cyberattacks, potentially resulting in detrimental scenarios, such as collisions and accidents involving AVs.

As a control engineer, my objective throughout my Ph.D. studies is to ensure the safety and optimal performance of these aerial systems. I'm committed to addressing the challenges posed by the intricate interplay between technology, safety, and performance in the context of control theory and aerial engineering. 

<hr>
A Proactive Risk Assessment Methodology based on Reachability and its Application to Multi-Agent Systems
------
<div id="dots" style="display:inline"> <strong> Multi-agent systems (MASs) </strong> have received great attention thanks to their capabilities to perform difficult/complex missions compared to single-agent systems. Each agent of a MAS has a distributed control protocol based on the local information obtained from its neighbors, which allows the MAS to be scalable and efficient. These advantages have led to the prosperous development of MAS engineering applications, such as multi-robots, autonomous vehicles, and unmanned aerial vehicles (UAVs). Nevertheless, system <strong> vulnerability </strong> of MASs to malicious threats, particularly in the form of cyberattacks, can pose a substantial concern. These threats have the potential to compromise the performance and overall safety of MASs. As such, there arises a need to develop a risk assessment methodology for MASs operating in the presence of cyberattacks. Such an approach is critical for enhancing the <strong> security </strong> and <strong> safety </strong> of MASs. </div>

<div id="more" style="display:none">
In contrast to single-agent systems, MASs exhibit a distinctive feature wherein the functionality and mission execution of MASs are profoundly reliant on inter-agent communication. For instance, in the context of UAM, the major tasks of aerial vehicles (AVs) in an urban environment would be cargo delivery, passenger transportation, and medical service. To increase operational efficiency, AVs will maintain formation control by sharing their vehicle's information (e.g., position and velocity) to achieve it.

<hr>  
<div style="text-align:center;">
  <img src="/images/Multi-Agent-System.png" alt="MAS" style="width:60%">
  <figcaption> Figure 1: An illustration of the operation of MAS in an urban environment. </figcaption>
</div>
<hr>  

Nevertheless, strong reliance on communication between AVs could give rise to system vulnerabilities toward cyberattacks (e.g., denial-of-service (DoS), false-data-injection (FDI), stealthy attacks, etc.). These malicious incursions may disrupt the integrity of information exchange among AVs, potentially jeopardizing their abilities to achieve their designed tasks. Consequently, in the MAS, computer science, and control communities, numerous research have been conducted to reactively mitigate/reduce the detrimental effects of cyber threats. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Attack.png" alt="MAS" style="width:60%">
  <figcaption> Figure 2: An impact of cyberattacks during the operation of MAS. </figcaption>
</div>
<hr>  

One of the drawbacks of the previous studies, from a defender's perspective, lies in the fact that mitigation strategies are triggered after the detection of an attack occurrence. However, these reactive strategies may not fully guarantee the system's safety in the presence of attacks. Since the safety of aerial systems, like UAM, is critically related to human lives and properties, focusing on mitigation/defense strategies that operate 
preemptively, before the identification of attack occurrence, is necessary.  

<hr>  
Building upon the above discussion, this research focuses on the development of a reachability-based proactive risk assessment strategy under cyberattacks. Based on the assumptions regarding the attack scenarios (e.g., types of attack vectors, norm-bounded condition, etc.) and reachability concept, we can mathematically measure how much cyberattacks can potentially impact the performance of MASs within a certain time window. The measurement from our methodology can be represented by an over-approximated ellipsoid, where this technique is well-aligned with control theory and applications of optimization. For graphical illustrations, please refer to Figure 3. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Reach.png" alt="MAS" style="width:60%">
  <figcaption> Figure 3: A proactive risk assessment with an over-approximated ellipsoidal-based reachable set. </figcaption>
</div>
<hr>  

In conclusion, our proactive risk assessment method can be applied to practical MASs, like UAM. To summarize the main contributions of our research, it enables the evaluation of potential risks associated with missions, including both individual agents and entire MAS levels. In detail, if there are overlaps between the over-approximated reachable sets, certain agents (as illustrated in Figure 4, AV 1 and AV 2) may encounter collision risks. Furthermore, when taking into account the composite union of all over-approximated reachable sets, this MAS configuration could potentially be susceptible to collisions with urban structures. A graphical illustration depicts this operation within the specific airspace, which is depicted as A in Figure 4.

<hr>  
<div style="text-align:center;">
  <img src="/images/Overview_new.png" alt="MAS_New" style="width:60%">
  <figcaption> Figure 4: An application of the proposed method to the UAM scenario. </figcaption>
</div>
<hr>  

Finally, this reachability-based risk assessment method would allow us to enhance to safety and security of MAS in a proactive manner. The next question of this topic would be: 1) How can we integrate this security metric into the design of the safety controller?, 2) What strategies can be employed to implement this metric in real-world systems with hardware components?, and 3) How can we effectively reduce the size of the over-approximated reachable sets? For more technical details of this research, please refer to our <a href="https://ieeexplore.ieee.org/abstract/document/10153779">work</a>.


</div>

<hr style="height:2pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn">Read more +</btn> 

<hr>
Resilient Control for Urban Air Mobility Applications under Cyberattacks
------
<div id="dots" style="display:inline"> The <strong> Urban Air Mobility </strong> (UAM) has received great attention since it can ease urban traffic congestion, offer faster and greener transportation, connect remote areas, and drive economic growth in urban areas. With the rapid advancement of UAM systems, including electric vertical takeoff and landing (eVTOL) vehicles, there is an escalating need to confront the system vulnerabilities regarding cybersecurity threats. UAM aerial vehicles (AVs) operating within urban environments could be susceptible to a range of cyber threats, such as denial-of-service (DoS) attacks and false-data-injection (FDI) attacks while they are in operation. These cyber-threats can lead to severe consequences, potentially leading to hazardous situations, such as accidents and collisions between AVs and obstacles. To address this issue, this research aims to develop resilient control algorithms to ensure the safety/security of UAM operations under cyberattacks. </div>
<div id="more" style="display:none"> 
TBD
</div>


<hr>
A Safety-Critical-Control for Mechanical Systems through Control Barrier Functions
------
One of the most critical questions in control systems is how to guarantee the <strong> safety </strong> of a system.

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



