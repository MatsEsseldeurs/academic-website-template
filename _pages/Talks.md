---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

<style>
.btn{
    margin-bottom:5px;
    padding-top:1px;
    padding-bottom:1px;
    padding-left:15px;
    padding-right:15px;
}
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Upcoming Talks
{% bibliography -f conferences --query @upposter %}
</div>


<div class="jumbotron">
### Conference Talks
{% bibliography -f conferences --query @conferencepres %}
</div>

