---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
show_footer: true
---

{% include base_path %}

<a href="/files/cv.pdf" target="_blank" class="btn btn--success">Download CV (PDF)</a>

Education
======
*   **Ph.D. in Mathematics**, University of Maryland, College Park (Expected Spring 2027)
    *   Advisor: Chris Laskowski 
*   **B.S. in Mathematics**, University of Chicago, [2017-2021]

Research Interests
======
*   **Mathematics:** Model theory, probability, statistics, geometry, combinatorics, type theory.
*   **Quantitative Finance:** Alpha Generation from alternative data sources, rigorous applications of AI and formal methods, derivatives pricing.
*   **Machine Learning:** LLM Benchmarking via Formal Methods, Graph Neural Networks, Predictive Modeling and Time Series Forecasting. 

Experience
======
*   **Graduate Teaching Assistant**, University of Maryland
    *   [2021] - Present
    *   Courses: 

*   **Research Assistant**, University of Maryland
    *   [2021] - Present
    *   Conducted research in...

Skills
======
*   **Programming:** Python (Pandas, NumPy, Scikit-learn, TensorFlow/PyTorch), SQL, LaTeX, Haskell, Lean4.
*   **Mathematics:** Stochastic Processes, Real Analysis, Probability Theory, Statistics.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == 'talks' %}
      {% include archive-single-talk-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>