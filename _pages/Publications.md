---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2022]
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Publications
<div class="jumbotron">

### Publications in review
{% bibliography -f inreview %}

### Peer reviewed publications
{% bibliography -f articles %}

### Thesis
{% bibliography -f thesis --query @thesis %}
</div>