---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

## Software

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Ray-Tracing Implementation in Phantom</b></h4>
<a href="https://github.com/danieljprice/phantom/blob/master/src/main/utils_raytracer.f90" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/3D_simulations_of_AGB_stellar_winds___II__Ray_tracer_implementation_and_impact_of_radiation_on_the_outflow_morphology.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> 

<b>Author:</b>
<i>Esseldeurs, Mats</i>

<div style="text-align:justify">
<a href="https://phantomsph.bitbucket.io/">Phantom</a> (<a href="https://ui.adsabs.harvard.edu/abs/2018PASA...35...31P/abstract">Price et al. 2018</a>) is a fast, parallel, modular and low-memory Smoothed Particle Hydrodynamics (SPH) code, able to tackel a large variaty of astrophysical problems in 3D. On the topic of simulating cool AGB outflows, <a href="https://ui.adsabs.harvard.edu/abs/2022A%26A...667A..75S/abstract">Siess et al. (2022)</a> implemented a treatment of particle injection and dust nucleation, which is used in studies like <a href="https://ui.adsabs.harvard.edu/abs/2021A%26A...653A..25M/abstract">Maes et al. (2021)</a> and <a href="https://ui.adsabs.harvard.edu/abs/2021A%26A...652A..51M/abstract">Malfait et al. (2021)</a>.

In this code, to account for radiation transfer effects, a ray tracing algorithm is implemented In this ray-tracing implementation, the benefits of SPH are exploited, to create an efficient algorithm to trace rays on the fly throughout SPH simulaitons. More information can be found in <a href="{{ site.url }}{{ site.baseurl }}/papers/3D_simulations_of_AGB_stellar_winds___II__Ray_tracer_implementation_and_impact_of_radiation_on_the_outflow_morphology.pdf">Esseldeurs et al. (submitted)</a>, Appendix A.

</div>
</div>
</div>
</div>
