---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---
<style>
.fade-in-section {
  opacity: 1 !important;
  transform: none !important;
  transition: none !important;
}
</style>
## Publications
<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">
<div class="section-card" id="pubList">
<h3>Preprints</h3>
{% bibliography --query @unpublished %}
<h3>Refereed Journal Articles</h3>
{% bibliography --query @article %}
<h3>Refereed Conference Proceedings</h3>
{% bibliography --query @inproceedings %}
</div>
