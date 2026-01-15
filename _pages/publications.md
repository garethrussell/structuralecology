---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
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

### Color key
<p><span style="color:#d0daf3">Light blue indicates a student under my supervision.</span><br>
<span style="color:#f1c832">Orange indicates a student under a colleague's supervision.</span><br>
<span style="color:#ff5030">Red indicates a faculty colleague at NJIT.</span></p>

<div class="jumbotron">
### Refereed journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Book chapters
{% bibliography --query @inbook %}
</div>

<div class="jumbotron">
### Refereed conference proceedings (selected)
{% bibliography --query @inproceedings %}
</div>

<div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div>

