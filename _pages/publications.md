---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2022]
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

# Publications
<div class="jumbotron">

### Peer reviewed publications
{% bibliography -f articles %}

### Thesis
{% bibliography -f thesis --query @thesis %}
</div>