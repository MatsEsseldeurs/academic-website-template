---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>3D simulations of AGB stellar winds</h4>
<img src="{{site.url}}{{site.baseurl}}/images/2Dplotrho_orbital.png" style="width:400px; min-width:39%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:5px; margin-top:0px;" align="right"/>

<b>Context.</b> Stars with an initial mass below ∼ 8 Msun will evolve through the Asymptotic Giant Branch (AGB) phase, during which they develop a strong stellar wind, due to radiation pressure on newly formed dust grains. Recent observations have revealed significant morphological complexities in AGB outflows, which are most probably caused by the interaction with a companion.

<b>Aims.</b> We aim for a more accurate description of AGB wind morphologies by accounting for both the radiation force in dust-driven winds and the impact of a companion on the AGB wind morphology.

<b>Methods.</b> We present the implementation of a ray-tracer for radiative transfer in the smoothed particle hydrodynamics (SPH) code Phantom. Our method allows for the creation of a 3D map of the optical depth around the AGB star. The effects of 4 different descriptions of radiative transfer, with different degrees of complexity, are compared: the free-wind approximation, the geometrical approximation, the Lucy approximation, and the attenuation approximation. Finally, we compare the Lucy and attenuation approximation to predictions with the 3D radiative transfer code Magritte.

<b>Results.</b> The effects of the different radiative transfer treatments are analysed considering both a low and high mass-loss rate regime and this both in the case of a single AGB star, as well as for an AGB binary system. For both low and high mass-loss rates, the velocity profile of the outflow is modified when going from the free-wind to the geometrical approximation, also resulting in a different wind morphology for AGB binary systems. In the case of a low mass-loss rate, the effect of the Lucy and attenuation approximation is negligible due to the low densities but morphological differences appear in the high mass-loss rate regime. By comparing the radiative equilibrium temperature and radiation force to the predictions from Magritte, we show that for most of the model the Lucy approximation works best, although close to the companion artificial heating occurs; and that it fails to simulate the shadow cast by the companion. The attenuation approximation leads to a stronger absorption of the radiation field yielding lower equilibrium temperature, weaker radiation force but produces the shadow cast by the companion. From the predictions of the 3D radiative transfer code Magritte, we also conclude that a radially directed radiation force is a reasonable assumption.

<b>Conclusions.</b> The radiation force plays a critical role in dust-driven AGB winds, impacting the velocity profile and morphological structures. For low mass-loss rates, the geometrical approximation suffices, but for high mass-loss rates a more rigorous method is required. Among the studied approaches, the Lucy approximation provides the most accurate results, although it does not account for all effects.
</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12" style="text-align:justify">
<h4>Evolution of planetary systems around evolved stars</h4>

About 95% of all stars in the galaxy have an initial mass lower than 8 solar masses. When these stars evolve off the Main Sequence, they will go through the Asymptotic Giant Branch (AGB) phase, just before turning into a White Dwarf (WD). This evolutionary phase is characterized by significant mass loss, large stellar radii, strong pulsations, and extreme luminosities. It must be studied to get a complete picture of the evolution of planetary systems from the birth to the end of their host stars. Indeed, population synthesis studies indicate that the majority of these stars have at least one (sub)stellar companion, where the abrupt changes in stellar characteristics may completely transform a planetary/binary system. In order to establish whether the planetary/(sub)stellar companion survives this evolutionary phase, and explain the presence of planets orbiting around WDs, one must study their orbital evolution for which both the stellar mass loss rate and mass accretion efficiency onto the companion and tidal interactions between the star and its companion play an important role. In current literature this is only addressed taking into account the simplest equilibrium tide, with mass-loss rate prescriptions and mass accretion efficiencies now considered outdated. For this reason, the treatment of these processes needs to be improved. First, we now study the dynamical tide, which can exceed the dissipation of the equilibrium tide by 3 orders of magnitude, which needs to be studied all along the evolution of stars. Second, we compute complex 3D hydrodynamic simulations that take into account all the complex components of the wind launching mechanism, as well as the gravitational perturbation of the companion. This makes it possible to account for the companion in simulating the mass loss rates, model for wind Roche Lobe overflow determining the mass accretion efficiency on the companion, as well as simulate the morphological structure of the AGB surroundings created by the companion. This allows us to build step by step coherent models of planetary systems orbiting evolved AGB stars.
</div>
</div>
