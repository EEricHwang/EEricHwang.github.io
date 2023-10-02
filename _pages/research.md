---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research endeavors focus on the development of control strategies tailered for cyber-physical systems (CPSs) within the realm of aerial engineering. I'm dedicated to enhancing the <strong> robustness </strong> and <strong> resilience </strong> of control systems in aerial engineering applications. These systems are of paramount importance since they bear direct implications for human safety. 

The design and implementation of aerial engineering control systems necessitate sophisticated solutions owing to their heightened intricacy and the paramount importance of safety considerations. Absent these solutions, a multitude of risks to human life and property damage would ensue. For instance, modern aerial control systems, like those utilized in Urban Air Mobility (UAM), place a substantial reliance on the uninterrupted flow of information enabled by communication networks (such as 5G, 6G, Wi-Fi, etc.), which connect aerial vehicles (AVs) to ground control stations. Nonetheless, these communication networks could be vulnerable to cyberattacks, potentially resulting in detrimental scenarios, such as collisions and accidents involving AVs.

As a devoted control engineer, my overarching objective throughout my Ph.D. studies is to ensure the safety and optimal performance of these aerial systems, in the presence of malicious threats. I'm committed to addressing the challenges posed by intricate interplay between technology, safety, and performance in the context of control theory and aerial engineering. 

<hr>
A Proactive Risk Assessment Methodology based on Reachability and its Application to Multi-Agent Systems
------
<div id="dots" style="display:inline"> <strong> Multi-agent systems (MASs) </strong> have received great attention thanks to their capabilities to perform difficult/complext missions compared to single-agent systmes (SASs). Each agent of a MAS has a distributed control protocol based on the local information obtained from its neighbors, which allows the MAS to be scalable and efficient. Therefore, these advantages have led to the prosperous development of MAS engineering applications, such as multi-robots, autonomous vehicles, and unmanned aerial vehicles (UAVs). Nevertheless, system <strong> vulnerability </strong> of MASs to malicious threats, particularly in the form of cyberattacks, can pose a substantial concern. These threats have the potential to compromise the performance and overall safety of MASs. As such, there arises a need to develop a risk assessment methodology tailored to MASs operating in the presence of cyberattacks. Such an approach is critical for enhancing the <strong> security </strong> and <strong> safety </strong> of MASs.

</div>
<div id="more" style="display:none">
In contrast to single-agent systems (SASs), multi-agent systems (MASs) exhibit a distinctive feature wherein the functionality and mission execution of MASs are profoundly reliant on inter-agent communication. For example, 

 <figure>
  <img src="/images/Multi-Agent-System.png" alt="MAS" style="width:40%">
  <figcaption>An illustration of the operation of MAS in an urban environment.</figcaption>
</figure>

</div>

<hr style="height:2pt; visibility:hidden;" />
<btn onclick="myFunction1()" id="myBtn">Read more +</btn> 

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



