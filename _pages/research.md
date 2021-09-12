---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<style>
p { margin-bottom: -10px; }
</style>

<font face="helvetica" size="3"> <p>In my research career, I have worked on the following topics till now.</p><br>

<font face="helvetica" color="#A93226" size="4.5">
          <p>Current Research: Computational MRI</p></font>

<font face="helvetica" size="3"> 
<ul>
<li> Working on using deep learning methods correct the arbritrary contrasts created using synthetic MRI maps. The current sequences used to estimate MRI parameter maps cannot include all the underlying physics or accounting them would result in a very long sequence. The aim of my current work is to translate the synthetic generated contrasts to clinically relevant contrasts.  </li>

<li> In parallel, I am also looking at estimating the tissue parameter maps directly from the undersampled k-space data using physics-based modeling techniques. 
</li>

</ul>
</font>

<font face="helvetica" color="#A93226" size="4.5">
          <p>Millimeter-Wave Multicasting with Low-resolution transceivers</p></font>

<font face="helvetica" size="3"> 
<ul>
<li> Designed frequency domain precoding for multicasting with low resolution digital to analog convertors (DACs).</li>

<li> Numerically evaluated proposed beamforming algorithm for different mmWave channel realizations.
</li>
</ul>
</font>

<font face="helvetica" color="#A93226" size="4.5">
          <p>System Design for wireless power transfer using capacitive coupling methods</p></font>

<font face="helvetica" size="3"> 
<ul>
<li> Investigated the feasibility of capacitive power transfer for IoT devices by conducting extensive simulations in Ansys Maxwell and Simplorer for different geometrical configurations. </li>

<li> Proposed compensation network topologies for both the transmitter and receiver to maximize power transfer. Built an experimental setup to corroborate simulation results.
</li>

</ul>
</font>
<font face="helvetica" color="#A93226" size="4.5">
          <p>Wireless communication and networking system design for UAV-enabled base station</p></font>

<font face="helvetica" size="3"> 
<ul>
<li>Proposed framework for evaluating the optimal UAV deployment altitude satisfying the coverage, load traffic constraints and backhaul limitations. </li>

<li> Solved the mixed-integer non-convex power and subcarrier allocation problem using  Lagrangian dual decomposition method.
</li>

</ul>
</font>
<font face="helvetica" color="#A93226" size="4.5">
          <p>UAV based wireless energy transfer to make sensor networks sustainable</p></font>

<font face="helvetica" size="3"> 
<ul>
<li> Presented new channel model for low altitude UAV platforms, suitable for wireless RF energy transfer. Introduced notion of RFET zone and calculated effective power available based on shadow statistics of new channel.</li>

<li> Proposed two novel strategies for charging of sensors by UAV mounted RF transmitter. Charging time was evaluated by solving optimization problem under practical UAV energy constraints.
</li>

<li>Developed a super-capacitor charging and discharging model suitable for constant power stimulus given by RF-to-DC power converter circuit.  </li>
</ul>
</font>


<font face="helvetica" color="#A93226" size="4.5">
          <p>Wireless Channel Propagation Model for RF Energy Transfer</p></font>

<font face="helvetica" size="3"> 
<ul>
<li> Proposed a novel channel model for accurately characterizing harvested DC power at receiver in wireless RFET, further experimentally verified model by carrying out extensive experiments in anechoic chamber.</li>

<li> Formulated an optimization problem by accounting for effect of NLOS component to maximize RFET efficiency, moreover presented a computationally-efficient golden section based iterative algorithm.
</li>

<li> Evaluated the statistical parameters for Rician and path loss with shadowing based wireless channel model for RFET through extensive energy measurements in real life scenarios. </li>
</ul>
</font>
