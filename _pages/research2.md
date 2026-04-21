---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Lab Core Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Movement and Dispersal</h4>

Our research group defines structural ecology as a subset of spatial ecology that focuses on the dynamic interaction between individual organisms and the structure and pattern of their surroundings. We ask: What do they perceive? If they can move, how do they navigate? Find each other? Avoid risk?

We ask these questions because much of spatial ecology, such as biogeography and metapopulation theory, contains rather implausible assumptions about how individuals disperse in their environment. This makes predictions based on these theories suspect, even as they are the foundation for a lot of conservation activity.

In practice, our lab studies animal movements in relation to their environment, patterns and how these, as well as different models of dispersal, translate into broader population and species-level dynamics.

</div>
</div>

## Undergraduate Research Opportunities

These are often in areas outside the core topics described above.

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

