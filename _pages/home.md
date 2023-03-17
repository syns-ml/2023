---
layout: home
title: Home
hometitle: Synergy of Scientific and Machine Learning Modeling
permalink: /
subtitle: ICML 2023 Workshop

news: true
---

<span style="color: red; font-weight: bold;">TESTING.</span>
<span style="color: blue; font-weight: bold;">@Organizers, please share your photo in the google drive! Thank you.</span>

The Synergy of Scientific and Machine Learning Modeling Workshop ("SynS & ML") aims to be an interdisciplinary forum for world-recognized and interested researchers in the challenges of combining scientific and machine-learning (ML) models.
While the interaction between Science and ML is a hot topic in recent years, a venue focused on the unification of scientific and ML modelling is missing.
Based on this observation, the goal of this workshop is to gather together ML researchers eager to include scientific models into their pipelines, domain experts working on augmenting their scientific models with ML, and researchers looking for opportunities to incorporate ML in widely-used scientific models.

## Key Dates

- Paper submission deadline: **dd MM 2023**
- Acceptance notification: **dd MM 2023**
- ...

## Speakers & Panelists

<div class="projects">
  {%- assign sorted_people = site.data.speakers | sort: "last" -%}
  {%- assign col_width = "25%" -%}
  <div class="container mt-3 mb-3 overflow-hidden">
    <div class="row gx-5">
    {%- for person in sorted_people -%}
      {% include people.html %}
    {%- endfor %}
    </div>
  </div>
</div>

## Organizers

<div class="projects">
  {%- assign sorted_people = site.data.organizers | sort: "last" -%}
  {%- assign col_width = "20%" -%}
  <div class="container mt-3 mb-3 overflow-hidden">
    <div class="row gx-5">
    {%- for person in sorted_people -%}
      {% include people.html %}
    {%- endfor %}
    </div>
  </div>
</div>
