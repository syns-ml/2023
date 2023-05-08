---
layout: page
permalink: /cfsm/
title: Call for Scientific Models
description:
nav: true
nav_order: 1
---

The workshop features two external contributions tracks:
1. [Paper submission](/2023/cfp/)
2. **Scientific model submission**

In the call for scientific models, we invite researchers in all disciplines to share **scientific computational models (a.k.a. scientific simulators)** that could potentially be combined with machine learning.
This is an original component of this workshop that we consider key to fostering interactions between machine learning researchers and domain scientists. It will be open to any types of scientific computational models respecting quality standards such as: code publicity, recognised scientific quality, documentation, etc. All contributions shall clearly discuss the modelling assumptions and their limitations. Accepted submissions will be made publicly available on the workshop webpage and will be presented at the poster session. Our goal is to create a digital library of scientific simulators respecting quality standard and ease the interaction between computational models and machine learning.

Criteria for a successful scientific model submission include:
- **Potential impact:** Will making this simulator more accessible to the research communities lead to impactful research and/or industrial developments?
- **Documentation:** Is the implementation respecting standard coding good practices (e.g. testability and maintainability)? Is there a documentation (the expected minimum is a readme file) to help practioners understand the code organization and/or expected usage.
- **Scientific validity:** Is the simulator grounded on validated scientific models (e.g. associated publication)?
- **Accessibility:** Is there a nice API/toolbox built on top of the simulation code to allow external users to simulate new configurations easily?

The submission will be with an abstract describing such information (and no need for writing a paper); please see the authors instructions below.

#### Awards & contributed talks
Awards shall be attributed to the four most oustanding contributions selected from the call for papers and the call for models with the financial supports of the workshop sponsors. Authors of the recognised contributions will have the opportunity to present their work as 15 minutes-long contributed talks.

#### Posters
Accepted scientific models shall preferably be presented as posters during the workshop. However, in order to facilitate viewing presentations in different time zones, the authors of each accepted scientific model will get the opportunity to submit a 10 minute video that summarizes their work. Authors of submitted papers will be able to indicate their preference for an in-person presentation or a virtual presentation. Instructions to upload videos will follow.

#### Key dates

{% include key_dates_list.md %}

---

## Authors instructions

#### Format
- Our goal is to keep the process to submit the simulator of a scientific model as light as possible while maximizing the positive impact of getting the simulator accepted to the workshop.
- **Anonymization is not mandatory** as we accept simulators already publicly available on github.
- Authors should **describe the simulator in the abstract**. We expect the following information to be present in the description:
    - Scientific or industrial value of the simulator
    - Scientific validity of the model behing the simulator (e.g., link to a peer-reviewed scientific paper)
    - Potential impact of combining the simulator with machine learning (Highly encouraged but optional)
    - Pointer to real-world data associated with the simulator (Highly encouraged but optional)
- A submission is composed of a description of the simulator as above and **the code accompanying it**. The code can be submitted as a link to a public github repository in the abstract field or as a zipped folder.
- Workshop organizers retain the right to reject submissions for editorial reasons.
- Submissions will be kept confidential until they are accepted and until authors confirm that they can be included in the workshop. If a submission is not accepted, or withdrawn for any reason, it will be kept confidential and not made public.

#### Submission platform
Submissions to the Scientific Model Track should be sent via **[Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfbkOco4cfGZ557udp4vfsiyQlHiJsvmU3JUTelWLJ4AxnCYQ/viewform)**.

#### Double submission policy
All accepted works will be made available on the workshop website. This does not constitute an archival publication or formal proceedings; authors retain full copyright of their work and are free to publish their extended work in another journal or conference. We allow submission of works that overlap with papers that are under review or have been recently published in a conference or a journal, including physical science journals. However, we do not accept cross-submissions of the same content to multiple workshops at ICML 2023.

---

## Reviewers instructions
Submissions that follow the submission instructions correctly (i.e., are not rejected due to editorial reasons) are sent for peer-review. Below are some of the key points about this process that are shared with the reviewers and authors alike. Authors are expected to consider these in preparation of their submissions and when deciding to apply for the reviewer role.

{% comment %}
- Papers are 4 pages long. Appendices are accepted but highly discouraged; the reviewers will not be required to read the appendices.
{% endcomment %}
- There will be multiple reviewers for each submission.
- Reviewers will be able to state their confidence in their review.
- We will provide an easy-to-follow template for reviews so that both the pros and the cons of the submission can be highlighted.
- Reviewers are expected to have an up-to-date openreview profil as the paper matching will rely on the openreview matching algorithm.
- Potential conflicts of interest based on institution and author collaboration are addressed through the openreview review system.
- Criteria for a successful scientific model submission include: novelty, correctness, relevance to the field, at the intersection of ML and sciences, and showing promise for future impact. Negative or null results that add value and insight are welcome.
- There will be no rebuttal period. Minor flaws will not be the sole reason for rejection. Incomplete works at an advanced progress stage are welcome.
