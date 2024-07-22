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
* Ph.D in Engineering Science, Osaka University, March/2025 (Expected)
* M.Sc. in Engineering Science, Osaka University, October/2021
* B.Sc. in Chemical Engineering, University of Sao Paulo (USP), December/2018

Work experience
======
* From September, 2022 until now: Research Assistant (Contract)
  * Osaka University
  * Duties includes: Assisting the professor's research by executing varied tasks, such as conducting experiments, 3D modeling/printing and summarizing state-of-the-art methods.
  * Supervisor: Professor Kensuke Harada

* January, 2018 to July, 2019: General Manager (Contract)
  * Personal Vestibulares
  * Duties included: Managing tutors for class material development and schedules. Tutor for high-school level lessons in Mathematics, Physics and Chemistry. Development of class materials for those subjects. Involved in performance analytics of the company.
  * Supervisor: Gustavo Yolle

*  February, 2017 to April, 2017: IT (Internship)
  * Hexagon AB
  * Duties included: Support to technical areas in a consulting project in Process and Instrumentation using the company's proprietary software, SmartPlant. Update/re-create industrial flowcharts to the newest available version at the time.
  * Supervisor: Ricardo Luna Mourilla
  
Skills
======
* Machine Learning
  * PyTorch
  * Tensorflow
  * Detectron2
* Computer Vision
  * OpenCV
  * Intel RealSense
* Robotics
  * ROS
  * MoveIt!

Publications
======
  ## Journals
---
{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## International Conferences
---
{% for post in site.publications reversed %}
  {% if post.type == 'int-conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Domestic Conferences
---
{% for post in site.publications reversed %}
  {% if post.type == 'domestic-conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
  
