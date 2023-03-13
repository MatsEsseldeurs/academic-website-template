---
title: "Home"
layout: default
sitemap: false
permalink: /
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>


<div id="homeid" class="col-sm-12 col-xs-12">
<figure>
  <img src="{{site.url}}{{site.baseurl}}/images/headshot.jpg" style="width:300px; min-width:25%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:5px; margin-top:25px;" align="right">
</figure>

<div style="text-align:justify">
### Welcome!
I'm Mats Esseldeurs, a PhD student in the [Institute of Astronomy](https://fys.kuleuven.be/ster) at [KU Leuven](https://www.kuleuven.be/kuleuven/). Here I am an active member of the research group lead by [Prof. Dr. Leen Decin](https://fys.kuleuven.be/ster/staff/senior-staff/leen-decin).

My scientific interests cover a variety of subjects that intersect math, physics, and computer science. Currently, I am working on developing efficient techniques for <b>approximating radiative transfer</b> in simulations of <b>3D fluid dynamics</b>. This I am doing in colaboration with [Dr. Frederik De Ceuster](https://freddeceuster.github.io/) ([KU Leuven](https://www.kuleuven.be/kuleuven/)) and [Dr. Lionel Siess](http://www.astro.ulb.ac.be/~siess/) ([ULB](https://www.ulb.be/en/ulb-homepage)).

Alongside this project I am also working on the semi-analytical moddeling of tidal dissipation in Stars, to unravel the complex orbital evolution throughout the entire lifetime of a star. This project is in collaboration with [Dr. Stéphane Mathis](http://sfmathis.free.fr/Home.html) ([CEA Paris-Seclay](https://www.cea.fr/paris-saclay/Pages/Accueil.aspx)).
</div>


<div class="jumbotron">
### Selected Publications
{% bibliography -f inreview %}
</div>