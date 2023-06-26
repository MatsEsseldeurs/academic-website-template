---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>3D simulations of AGB stellar winds</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/2Dplotrho_orbital2.png" style="width:400px; min-width:39%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:0px;" align="right"/>

In my research, I focus on understanding the behavior of stars during the Asymptotic Giant Branch (AGB) phase, which is a crucial stage in their evolution. During this phase, stars with an initial mass below approximately 8 solar masses develop a strong stellar wind due to radiation pressure on newly formed dust grains.

Recent observations have shown that AGB outflows display significant morphological complexities, which are most likely caused by the interaction with a companion. In order to better understand and describe these morphologies, I have developed a 3D simulation of AGB stellar winds.

My simulation takes into account both the radiation force in dust-driven winds and the impact of a companion on the AGB wind morphology. To achieve this, I have implemented a ray-tracer for radiative transfer in the smoothed particle hydrodynamics (SPH) code Phantom. This method allows for the creation of a 3D map of the optical depth around the AGB star.

I have compared the effects of four different descriptions of radiative transfer, with different degrees of complexity, including the free-wind approximation, the geometrical approximation, the Lucy approximation, and the attenuation approximation. By comparing the results to predictions from the 3D radiative transfer code Magritte, I have found that the Lucy approximation provides the most accurate results for most of the model, although it does not account for all effects.

Overall, my research highlights the critical role of the radiation force in dust-driven AGB winds, impacting the velocity profile and morphological structures. These findings provide important insights into the behavior of stars during the AGB phase and contribute to our understanding of the evolution of stars.

{% bibliography -f articles -q @*[selected=True]  %}
</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>Planetary systems around evolved stars</h4>
<img src="{{site.url}}{{site.baseurl}}/images/Research/Planet_v2.jpg" style="width:380px; min-width:34%; max-width:100%; margin-left:0px; margin-right:20px; margin-bottom:0px; margin-top:5px;" align="left"/>

Studying the same AGB stars, I also investigate any planets or companions orbiting around them. Their significant mass-loss and changes in their physical characteristics can have a significant impact on any companions orbiting around them. To fully understand the evolution of planetary systems, we need to study the AGB phase and the role that companions play in this process.

Most AGB stars have at least one companion, and the sudden changes in the star's characteristics can completely transform the planetary or binary system. To understand whether the companion survives this phase and explain the presence of planets orbiting around White Dwarfs, we need to study their orbital evolution. This involves taking into account the stellar mass-loss rate, mass accretion efficiency onto the companion, and tidal interactions between the star and its companion.

Previous research has only addressed these processes by using simple models that are now considered outdated. Our research focuses on improving this treatment by studying the dynamical tide, which can exceed the dissipation of the equilibrium tide by three orders of magnitude, and by using complex 3D hydrodynamic simulations that account for all components of the wind launching mechanism and the gravitational perturbation of the companion. This enables us to accurately model the mass-loss rates, mass accretion efficiency, and morphological structure of the AGB surroundings created by the companion.

Our research will help build coherent models of planetary systems orbiting evolved AGB stars, shedding light on the fate of planetary systems and their companions as stars evolve.
</div>
</div>
