---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2022]
---

<div class="jumbotron">

### Peer reviewed publications
{% bibliography -f articles -q @*[selected!=True] %}

### Thesis
{% bibliography -f thesis --query @thesis %}

</div>