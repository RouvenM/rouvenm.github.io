---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Statistics (summa cum laude), Bielefeld University, October 2020 - June 2024
* MSc in Business Mathematics, Bielefeld University, October 2016 - March 2019
* BSc in Business Mathematics, Bielefeld University, October 2013 - September 2016

Work experience
======
* Since October 2024: Research Associate in the Statistical Methods for Big Data group at Technical University of Dortmund, Dortmund

* October 2020 – present: Research Associate in the Statistics and Data Analysis group at Bielefeld University, Bielefeld
* October 2020 – September 2024: Research Associate in the Sports Science AB V group at Bielefeld University, Bielefeld

* May 2019 – September 2020: Associate in (Quantitative) Risk Management at KPMG AG, Bielefeld

* February 2018 – December 2018: Working Student and Intern in Credit Risk at KPMG AG, Frankfurt am Main

* October 2015 – March 2019: Student/Research Assistant and Academic Advisor at Bielefeld University, Bielefeld

* August 2015 – September 2015: Intern in Actuarial Department at Zurich AG, Bonn

Publications
======
{% capture publications_content %}
  {% include_relative publications.md %}
{% endcapture %}

{% assign content_array = publications_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}
  
Talks
======
{% capture talks_content %}
  {% include_relative talks.md %}
{% endcapture %}
  
Teaching
======
{% capture teaching_content %}
  {% include_relative teaching.md %}
{% endcapture %}

{% assign content_array = teaching_content | split: "---" %}
{% assign content_without_frontmatter = content_array[2] %}

{{ content_without_frontmatter | markdownify }}
  
