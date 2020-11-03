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

P. Magron, T. V, **Complex ISNMF: a phase-aware model for monaural audio source separation**, IEEE/ACM Transactions on Audio, Speech and Language Processing, Vol.27, no. 1, pp. 20-31, January 2019.
[Paper](https://arxiv.org/abs/1802.03156) [Code](https://github.com/magronp/complex-isnmf)

P. Magron, T. V, **Complex ISNMF: a phase-aware model for monaural audio source separation**, IEEE/ACM Transactions on Audio, Speech and Language Processing, Vol.27, no. 1, pp. 20-31, January 2019.
[Paper](https://arxiv.org/abs/1802.03156) [Code](https://github.com/magronp/complex-isnmf)

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

