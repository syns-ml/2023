---
layout: home
title: Home
hometitle: Synergy of Scientific and Machine Learning Modeling
permalink: /
subtitle: ICML 2023 Workshop, July 28 2023, Room 320 of the Hawai‘i Convention Center

ne:ws: false
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

This workshop will be an **in-person event** (with some virtual components such as online talks and videos by authors) at ICML 2023.

{% comment %}
<div style="padding: 8px; margin: 0 auto; margin-bottom: 20px; border: 1px dotted #333333; background-color: #DDDDDD; width: 97%;">
  We are looking for your help in making SynS & ML a great venue! Feel that you might help reviewing one or a few papers? You are awesome! Show interest by filling in <a href="https://docs.google.com/forms/d/e/1FAIpQLSe8uGGI7PNZbqS7KrYgHDgAJ6Y_XWvwApganOmCsWmhBtUc1A/viewform?usp=sf_link" style="font-weight: bold;" target="_blank">this form</a> to nominate yourself as a reviewer.
</div>
{% endcomment %}

## Schedule

Please check [Accepted Contributions](contributions/) for poster session assignment.

<table class="schedule">
<tbody>
  <tr class="tobedone">
    <td>09:00</td>
    <td>Opening remarks</td>
  </tr>
  <tr class="tobedone">
    <td>09:00&ndash;09:30</td>
    <td>Talk: <i>Two for One: Diffusion Models and Force Fields for Coarse-Grained Molecular Dynamics</i> by Rianne van den Berg</td>
  </tr>
  <tr class="tobedone">
    <td>09:30&ndash;10:00</td>
    <td>Talk: <i>The Domain Generalization Issue in Data-Based Dynamical Models</i> by Patrick Gallinari</td>
  </tr>
  <tr class="tobedone">
    <td>10:00&ndash;10:30</td>
    <td>Break</td>
  </tr>
  <tr class="tobedone">
    <td>10:30&ndash;11:00</td>
    <td>Talk: <i>Climate modeling with AI: Hype or Reality?</i> by Laure Zanna</td>
  </tr>
  <tr class="tobedone">
    <td>11:00&ndash;12:00</td>
    <td>Poster session <abbr class="badge" style="background-color:{{ site.data.venues.AM.color }};">AM</abbr> (<a href="poster/">Poster Instruction</a>; <a href="contributions/">Session Assignment</a>)</td>
  </tr>
  <tr class="tobedone">
    <td>12:00&ndash;<strong>13:00</strong></td>
    <td>Lunch (on your own)</td>
  </tr>
  <tr class="tobedone">
    <td><strong>13:00</strong>&ndash;13:30</td>
    <td>Talk: <i>AI-Augmented Epidemiology for Covid-19</i> by Sercan Ö. Arık</td>
  </tr>
  <tr class="tobedone">
    <td>13:30&ndash;14:00</td>
    <td>Talk: <i>Underspecification, Inductive Bias, and Hybrid Modeling</i> by Andrew Miller</td>
  </tr>
  <tr class="tobedone">
    <td>14:00&ndash;15:00</td>
    <td>Contributed oral presentations</td>
  </tr>
  <tr class="tobedone">
    <td>15:00&ndash;15:30</td>
    <td>Break</td>
  </tr>
  <tr class="tobedone">
    <td>15:30&ndash;16:00</td>
    <td>Contributed oral presentations</td>
  </tr>
  <tr class="tobedone">
    <td>16:00&ndash;17:00</td>
    <td>Poster session <abbr class="badge" style="background-color:{{ site.data.venues.PM.color }};">PM</abbr> (<a href="poster/">Poster Instruction</a>; <a href="contributions/">Session Assignment</a>)</td>
  </tr>
</tbody>
</table>

{% comment %}
---

## Key dates

{% include key_dates_list.md %}
{% endcomment %}

{% comment %}
<div style="padding: 8px; margin: 0 auto; margin-bottom: 20px; border: 1px dotted #333333; background-color: #f0f8ff; width: 60%;">
  <p style="text-align: center; margin-bottom: 0px;">
    Submission to Paper Track: <strong><a href="https://openreview.net/group?id=ICML.cc/2023/Workshop/SynS_and_ML" target="_blank">OpenReview</a></strong><br />
    Submission to Scientific Model Track: <strong><a href="https://docs.google.com/forms/d/e/1FAIpQLSfbkOco4cfGZ557udp4vfsiyQlHiJsvmU3JUTelWLJ4AxnCYQ/viewform" target="_blank">Google Form</a></strong>
  </p>
</div>
{% endcomment %}

---

## Sponsors

<div class="projects sponsors">
  {%- assign sorted_sponsors = site.data.sponsors | sort: "order" -%}
  {%- assign col_size = "large" -%}
  <div class="container" style="margin-bottom: 20px;">
    <div class="row">
    {%- for sponsor in sorted_sponsors -%}
      {% include sponsors.html %}
    {%- endfor %}
    </div>
  </div>
</div>

---

## Speakers & Panelists

<div class="projects people">
  {%- assign sorted_people = site.data.speakers | sort: "last" -%}
  {%- assign col_size = "large" -%}
  <div class="container" style="margin-bottom: 20px;">
    <div class="row">
    {%- for person in sorted_people -%}
      {% include people.html %}
    {%- endfor %}
    </div>
  </div>
</div>

---

## Organizers

<div class="projects people">
  {%- assign sorted_people = site.data.organizers | sort: "last" -%}
  {%- assign col_size = "small" -%}
  <div class="container" style="margin-bottom: 20px;">
    <div class="row">
    {%- for person in sorted_people -%}
      {% include people.html %}
    {%- endfor %}
    </div>
  </div>
</div>

## Contact

Please contact the organizers at: [synsandml@gmail.com](mailto:synsandml@gmail.com)
