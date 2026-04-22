---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Lab Core Research: Movement and Dispersal

Our research group defines structural ecology as a subset of spatial ecology that focuses on the dynamic interaction between individual organisms and the structure and pattern of their surroundings. We ask: What do they perceive? If they can move, how do they navigate? Find each other? Avoid risk? And ultimately, how do these translate into broader population and species-level dynamics?

We ask these questions because much of spatial ecology, such as biogeography and metapopulation theory, contains rather implausible assumptions about how individuals disperse in their environment. This makes predictions based on these theories suspect, even as they are the foundation for a lot of conservation activity.

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Combined social and environmental drivers of movement</h4>

We fit integrated step selection functions to animal movement data to build models of their response to their surrondings, including both traditional environmental features (vegetation, water, etc.) and social features (the location of nearby conspecifics). Over the years the lab has looked at data on elephants, bears, humpback whales, sheep, goats and baboons.

</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">

<h4>Patterns in disperal limitations, and thus community composition, among islands</h4>

PhD student Grant Bowers is censusing the mammal communities on the coastal islands of Maine and showing that the different distribution limitations of different species lead to non-nested mammal communities not necessarily found on the mainland.

</div>
</div>

## Undergraduate Research Opportunities

These are often in areas outside the core topics described above. If you are interested contact the lab PI, Dr. Gareth Russell, at <a href="mailto:russell@njit.edu">russell@njit.edu</a>.

{% for project in site.data.projects %}
<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>{{ project.name }}</h4>

DESCRIPTION: {{ project.desc }}

SUITABILITY: {{ project.suitability }}

EXPERIENCE REQUIRED: {{ project.experience }}
</div>
</div>
{% endfor %}

