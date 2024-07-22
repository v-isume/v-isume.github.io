---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Journals
{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## International Conferences
{% for post in site.publications reversed %}
  {% if post.type == 'int-conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Domestic Conferences
{% for post in site.publications reversed %}
  {% if post.type == 'domestic-conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
