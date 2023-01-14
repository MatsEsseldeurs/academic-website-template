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
<h4><b>Ray-Tracing Implementation in PHANTOM</b></h4>
<a href="https://github.com/danieljprice/phantom/blob/master/src/main/utils_raytracer.f90" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/Radiation_Pressure.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a> 

<b>Author:</b>
<i>Esseldeurs, Mats</i>

PHANTOM (Price et al. 2018) is a 3D Smoothed Particle Hydrodynamics (SPH) code. In this code, to account for some approximate radiation transfer, a ray tracing algorithm is needed. In this ray-tracing implementation in PHANTOM, the benefits of SPH are exploited, to create an efficient algorithm to trace rays on the fly throughout SPH simulaitons.

</div>
</div>
</div>
