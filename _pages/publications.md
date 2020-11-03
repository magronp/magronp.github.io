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

## Preprints

{% for post in site.publi_preprint reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journals

{% for post in site.publi_journal reversed %}
  {% include archive-single.html %}
{% endfor %}

## International Conferences

{% for post in site.publi_conf reversed %}
  {% include archive-single.html %}
{% endfor %}

## National Conference (in French)

{% for post in site.publi_confnat reversed %}
  {% include archive-single.html %}
{% endfor %}

## Technical reports

{% for post in site.publi_techrep reversed %}
  {% include archive-single.html %}
{% endfor %}

## Thesis (in French)

{% for post in site.publi_thesis reversed %}
  {% include archive-single.html %}
{% endfor %}

