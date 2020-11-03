---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Preprint

{% for post in site.publications.preprint reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal

{% for post in site.publications.journal reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference

{% for post in site.publications.conference reversed %}
  {% include archive-single.html %}
{% endfor %}

