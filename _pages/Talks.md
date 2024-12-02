---
title: "Presentations & Posters"
layout: gridlay
sitemap: false
permalink: /talks/
---

<!-- <div class="jumbotron">
### Upcoming Talks
{% bibliography -f conferences --query @upposter %}
</div> -->


<div class="jumbotron">
### Invited talks
{% bibliography -f conferences --query @conferencepres -q @*[invited=True] %}

### Contributed talks
{% bibliography -f conferences --query @conferencepres -q @*[invited!=True && poster_pres!=True] %}

### Posters
{% bibliography -f conferences --query @conferencepres -q @*[poster_pres=True]%}
</div>

