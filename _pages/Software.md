---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12" style="margin-top:-20px">
<img src="{{site.url}}{{site.baseurl}}/images/Software/Phantom.png" style="width:100px; min-width:10%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:15px;" align="right"/>
<h4>Ray-Tracing Implementation in Phantom
<a href="https://github.com/danieljprice/phantom/blob/master/src/main/utils_raytracer.f90" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/3D_simulations_of_AGB_stellar_winds___II__Ray_tracer_implementation_and_impact_of_radiation_on_the_outflow_morphology.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> </h4>

<b>Author:</b>
<i>Esseldeurs, Mats</i>

<div style="text-align:justify">
<a href="https://phantomsph.bitbucket.io/">Phantom</a> (<a href="https://ui.adsabs.harvard.edu/abs/2018PASA...35...31P/abstract">Price et al. 2018</a>) is a fast, parallel, modular and low-memory Smoothed Particle Hydrodynamics (SPH) code, able to tackel a large variaty of astrophysical problems in 3D (written in Fortran90). On the topic of simulating cool AGB outflows, <a href="https://ui.adsabs.harvard.edu/abs/2022A%26A...667A..75S/abstract">Siess et al. (2022)</a> implemented a treatment of particle injection and dust nucleation, which is used in studies like <a href="https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..25M/abstract">Maes et al. (2021)</a> and <a href="https://ui.adsabs.harvard.edu/abs/2021A%26A...652A..51M/abstract">Malfait et al. (2021)</a>.

In this code, to account for radiation transfer effects, a ray tracing algorithm is implemented In this ray-tracing implementation, the benefits of SPH are exploited, to create an efficient algorithm to trace rays on the fly throughout SPH simulaitons. More information can be found in <a href="{{ site.url }}{{ site.baseurl }}/papers/3D_simulations_of_AGB_stellar_winds___II__Ray_tracer_implementation_and_impact_of_radiation_on_the_outflow_morphology.pdf">Esseldeurs et al. (2023)</a>, Appendix A.

</div>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12" style="margin-top:-20px">
<img src="{{site.url}}{{site.baseurl}}/images/Software/Magritte.png" style="width:200px; min-width:20%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:5px; margin-top:15px;" align="right"/>
<h4>Magritte
<a href="https://github.com/Magritte-code/Magritte" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a></h4>

<b>Authors:</b>
<i>De Ceuster, Frederik; Ceulemans, Thomas</i>&nbsp;&nbsp;&nbsp;&nbsp;
<b>Contributors:</b>
<i>Esseldeurs, Mats; et al.</i>

<div style="text-align:justify">
<a href="https://magritte.readthedocs.io/en/stable/">Magritte</a> (<a href="https://ui.adsabs.harvard.edu/abs/2020MNRAS.492.1812D/abstract">De Ceuster et al. 2020</a>) is an open-source software library for simulating radiation transport (written in C++). Magritte is currently mainly used for post-processing hydrodynamical simulations by creating synthetic observations, but the techniques could also be applied more general (e.g. <a href="https://ui.adsabs.harvard.edu/abs/2023arXiv230206221C/abstract">Coenegrachts et al. subm.</a>). Magritte uses a deterministic ray-tracer with a formal solver that currently focusses on line radiative transfer. The algorithms of Magritte form the basis of the ray-tracing implementation in Phantom (<a href="{{ site.url }}{{ site.baseurl }}/papers/3D_simulations_of_AGB_stellar_winds___II__Ray_tracer_implementation_and_impact_of_radiation_on_the_outflow_morphology.pdf">Esseldeurs et al. 2023.</a>).
</div>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12" style="margin-top:-20px">
<img src="{{site.url}}{{site.baseurl}}/images/Software/plons_v2.png" style="width:100px; min-width:10%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:10px;" align="right"/>
<h4>Plons
<a href="https://github.com/Ensor-code/plons" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a></h4>

<b>Author:</b>
<i>Malfait, Jolien; Esseldeurs, Mats; Maes, Silke; et al.</i>

<div style="text-align:justify">
<a href="https://anaconda.org/Ensor/plons">Plons</a> (PLOtting tool for Nice Simulations) is a plotting tool designed for for plotting wind simulations in the SPH code Phantom. It is desinged to load phantom_dump files and phantom_ev files to analyse and visualise morphological structures in outflow simulations, as well as the time evolution of properties like the orbital parameters.
</div>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12" style="margin-top:-20px">
<img src="{{site.url}}{{site.baseurl}}/images/Software/SideKicks.png" style="width:140px; min-width:14%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:10px;" align="right"/>
<h4>SideKicks.jl
<a href="https://github.com/orlox/SideKicks.jl" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a></h4>

<b>Author:</b>
<i>Marchant, Pablo; Esseldeurs, Mats</i>

<div style="text-align:justify">
<a href="https://juliahub.com/ui/Packages/SideKicks/OZCI1/0.2.0">SideKicks</a> (Statistical Inference to DEtermine KICKS on compact objects) is a Julia package which provides tools to perform MCMC sampling of a system composed of a star and a compact object in order to determine kicks received on the compact object at birth. This tool allows to statistically determin the initial pre-SN binary properties from observed post-SN binary properties. 
</div>
</div>
</div>
</div>