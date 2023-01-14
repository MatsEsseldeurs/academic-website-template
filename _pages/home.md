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


<div id="homeid" style="text-align:justify;" class="col-sm-7 col-xs-12">
{{"### Welcome!
I'm Mats Esseldeurs, a PhD student in the [Institute of Astronomy](https://fys.kuleuven.be/ster) at [KU Leuven](https://www.kuleuven.be/kuleuven/). I am an active member of the research group lead by [Prof. Dr. Leen Decin](https://fys.kuleuven.be/ster/staff/senior-staff/leen-decin).

My scientific interests cover a variety of subjects that intersect math, physics, and computer science. Currently, I am working on developing efficient techniques for <strong>approximating radiative transfer</strong> in simulations of <strong>3D fluid dynamics</strong>."}}
</div>
<div id="newsid" class="col-sm-5 col-xs-12" >
{% include sidebar.html %}
</div>



<div class="jumbotron">
### Selected Publications
{% bibliography --query @thesis %}
</div>