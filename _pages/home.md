---
layout: home
title: Home
hometitle: Synergy of Scientific and Machine Learning Modeling
permalink: /
subtitle: ICML 2023 Workshop, 28 or 29 (TBD) July 2023, Hawaii, USA

news: false
---

-----

## Introduction

The Synergy of Scientific and Machine Learning Modeling Workshop ("SynS & ML") is an interdisciplinary forum for researchers and practitioners interested in the challenges of combining scientific and machine-learning models.
The goal of the workshop is to gather together machine learning researchers eager to include scientific models into their pipelines, domain experts working on augmenting their scientific models with machine learning, and researchers looking for opportunities to incorporate ML in widely-used scientific models.

The power of machine learning (ML), its ability to build models by leveraging real-world data is also a big limitation; the quality and quantity of training data bound the validity domain of ML models.
On the other hand, expert models are designed from first principles or experiences and labelled scientific if validated on curated real-world data, often even harvested for this specific purpose, as advised by the scientific method since Galileo.
Expert models only describe idealized versions of the world which may hinder their deployment for important tasks such as accurate forecasting or parameter inference.
This workshop focuses on **the combination of two modelling paradigms: scientific and ML modelling**.
Sometimes called hybrid learning or grey-box modelling, this combination should 1) unlock new applications for expert models, and 2) leverage the data compressed within scientific models to improve the quality of modern ML models.
In this spirit, the workshop focuses on the symbiosis between these two complementary modelling approaches; it aims to be a "rendezvous" between the involved communities, spanning sub-fields of science, engineering and health, and encompassing ML, to allow them to present their respective problems and solutions and foster new collaborations.
The workshop invites researchers to contribute to such topics; see [Call for Papers](cfp/) and [Call for Scientific Models](cfsm/) for more details.

This workshop will be an **in-person event** (with some virtual components such as online talks and videos by authors) at ICML 2023. The exact date and room are to be announced.

**We are looking for your help in making SynS & ML a great venue! Feel that you might help reviewing one or a few papers? You are awesome! Show interest by filling in [this form](https://docs.google.com/forms/d/e/1FAIpQLSe8uGGI7PNZbqS7KrYgHDgAJ6Y_XWvwApganOmCsWmhBtUc1A/viewform?usp=sf_link).**

## Key dates

- Submission Deadline: **{{ site.data.keydates.submission }}**
- Review Deadline: **{{ site.data.keydates.review }}**
- Decision: **{{ site.data.keydates.decision }}**
- Camera-ready: **{{ site.data.keydates.camera_ready }}**
- Poster deadline: **{{ site.data.keydates.poster }}**
- Workshop: **{{ site.data.keydates.workshop }}**


## Call for sponsors

**Support our effort to merge scientific models and machine learning by sponsoring the SynS & ML workshop!**
Your donation will provide financial supports to guest speakers and authors of accepted publications. Interested organisations can confirm their interest and the amount of their support (minimum 500$) by email to synsandml@gmail.com. In exchange of the sponsor’s generosity we provide the following list of acknowledgments and services:

- The donation will support the travel costs and/or the conference fees of speakers and/or main authors of accepted publications. Each of these grants will be attributed by the organizing committee by priorizing profiles from underrepresented communities.
- Sponsoring one or many best paper award(s). The sponsoring entity can also offer to provide goodies to give to the best paper awards.
- The sponsoring entity can express its preference on how it would like money to be attributed by the organising committee (travel costs _vs_ conferences fees _vs_ best paper award(s)).
- Each grant will be tied to one sponsor and the name of the sponsor will be explicitly mentioned to the awardee(s).
- Company logo on website
- Company logo on the acknowledgements slide presented at the end of the workshop (ranked by amount of the support) and a word on the number and types of supports it allowed the workshop to provide.


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

## Schedule
**More information coming soon!**


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

## Contact

Please contact the organizers at: [synsandml@gmail.com](mailto:synsandml@gmail.com)
