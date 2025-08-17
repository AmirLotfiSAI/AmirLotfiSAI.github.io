---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Full CV as PDF](/files/Amirhossein_Lotfi_CV.pdf)
{: .btn .btn--inverse}

Education
======
* **M.Sc. in Materials Science and Engineering**, 2025 (Expected)
 * Iran University of Science and Technology, Tehran, Iran
 * Specialization: Materials Characterization and Selection
* **B.Sc. in Materials Science and Engineering**, 2023
 * Isfahan University of Technology, Isfahan, Iran

Work experience
======
* **2023 - Present: Graduate Research Student**
  * Iran University of Science and Technology
  * Supervisor: [Supervisor's Name]
  * Duties included:
    * Developing machine learning models for materials property prediction.
    * Aggregating and preprocessing data from scientific literature.
    * Scientific writing and preparation of manuscripts.
  
Skills
======
* **Programming:** Python (Proficient)
* **Machine Learning:** Scikit-learn, Pandas, NumPy, TensorFlow/PyTorch (Beginner)
* **Data & Visualization:** OriginLab, Matplotlib
* **Languages:** Persian (Native), English (Professional)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
