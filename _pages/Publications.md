---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2022]
---

<div class="jumbotron">

### Publications in review
{% bibliography -f inreview -q @*[status!=selected]  %}

### Peer reviewed publications
{% bibliography -f articles %}

### Thesis
{% bibliography -f thesis --query @thesis %}

</div>