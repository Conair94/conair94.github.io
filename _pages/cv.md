---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/cv.pdf" target="_blank" class="btn btn--success">Download CV (PDF)</a>

Education
======
*   **Ph.D. in Mathematics**, University of Maryland, College Park, 2025 (Expected)
    *   Advisor: [Advisor Name]
    *   Thesis: [Thesis Title/Topic in Model Theory]
*   **B.S. in Mathematics**, [Previous University], [Year]

Research Interests
======
*   **Quantitative Finance:** Market microstructure, stochastic calculus, derivatives pricing.
*   **Machine Learning:** Deep learning, reinforcement learning, predictive modeling.
*   **Mathematics:** Model theory, probability, geometry, combinatorics.

Experience
======
*   **Graduate Teaching Assistant**, University of Maryland
    *   [Year] - Present
    *   Courses: Calculus I, II, III, Linear Algebra, etc. (Update as needed)

*   **Research Assistant**, University of Maryland
    *   [Year] - Present
    *   Conducted research in...

Skills
======
*   **Programming:** Python (Pandas, NumPy, Scikit-learn, TensorFlow/PyTorch), C++, SQL, LaTeX.
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