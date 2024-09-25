---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research aims to develop control algorithms for Cyber-Physical Systems (CPSs) for aerospace systems. I'm particularly interested in how to enhance their <strong> robustness </strong> and <strong> resilience </strong> in adversarial environments. 

The control systems for aerospace systems necessitate advanced solutions due to the importance of safety considerations. Without these solutions, numerous safety violations (e.g., crashes and collisions) would highly occur. For instance, modern aerial control systems like Urban Air Mobility (UAM) place heavy reliance on the uninterrupted flow of information enabled by communication networks (e.g., 5G, Wi-Fi, etc.), which connect Aerial Vehicles (AVs) to ground control stations. However, these communication networks could be vulnerable to cyberattacks, potentially resulting in detrimental scenarios. Furthermore, given the dynamic nature of urban environments, UAM AVs are exposed to signal jamming, disturbances, and unexpected system failures. 

As a control engineer, my research objective is how to achieve 1) robustness and 2) resiliency with high-assured system performance. I'm committed to addressing the challenges posed by the intricate interplay between technology, safety, and performance in the context of control theory and aerial engineering. 

<hr>  
<div style="text-align:center;">
  <img src="/images/Diagram.png" alt="MAS" style="width:40%">
  <figcaption> Figure: A balance between the system's performance, robustness, and resilience. </figcaption>
</div>

<hr>
Reactive Defense Strategy
------
<p> <strong> Objective: </strong> In this research topic, we aim to design advanced control algorithms that can directly mitigate the impact of adversities. To this end, a resilient sensor fusion technique is needed that can filter out the malicious data/information embedded in measurement output.  </p>



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



