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
  <img src="{{site.url}}{{site.baseurl}}/images/headshot.jpg" style="width:350px; min-width:30%; max-width:100%; margin-left:20px; margin-right:0px; margin-bottom:0px; margin-top:0px;" align="right">
</figure>

<div style="text-align:justify">
### Welcome to my personal website!
I'm Mats Esseldeurs, a PhD student at [KU Leuven](https://www.kuleuven.be/kuleuven/)'s [Institute of Astronomy](https://fys.kuleuven.be/ster), in the team of [Prof. Dr. Leen Decin](https://fys.kuleuven.be/ster/staff/senior-staff/leen-decin). My research lies at the intersection of math, physics, and computer science, where I explore some of the most complex phenomena in the universe.

My primary research project involves developing efficient techniques for <b>approximating radiative transfer</b> in simulations of <b>3D fluid dynamics</b>. This is an exciting area of research because it has the potential to improve our understanding of a wide range of astrophysical processes, where I focus on the cool outflows of AGB stars. My collaborators on this project include [Dr. Frederik De Ceuster](https://freddeceuster.github.io/) at [KU Leuven](https://www.kuleuven.be/kuleuven/) and [Dr. Lionel Siess](http://www.astro.ulb.ac.be/~siess/) at [ULB](https://www.ulb.be/en/ulb-homepage).

In addition to my work on radiative transfer, I'm also exploring the semi-analytical modeling of <b>tidal dissipation in binary systems</b>. This project aims to unravel the complex orbital evolution throughout a star's lifetime, which has important implications for instance in the formation and evolution of planetary systems. My collaborator on this project is [Dr. Stéphane Mathis](http://sfmathis.free.fr/Home.html) at [CEA Paris-Seclay](https://www.cea.fr/paris-saclay/Pages/Accueil.aspx).

Apart from my research, I am also passionate about sharing my knowledge with others. I strongly believe that it is important for researchers to share their knowledge and expertise with others, both within and outside of academia. Throughout my academic journey, I have gained valuable experience as a tutor in mathematics and physics, a teaching assistant at KU Leuven, and a supervisor of a Master's students thesis.

When I'm not working on my research, you can find me cycling in the beautiful Belgian countryside, listening to science fiction audiobooks, or watching nature documentaries. I also enjoy spending time with my friends and family, trying out new recipes in the kitchen, and enjoying the vibrant city Leuven.

Thanks for visiting my website, and please don't hesitate to get in touch if you have any questions or comments!
</div>


<div class="jumbotron">
### Selected Publications
{% bibliography -f articles -q @*[selected=True]  %}
</div>