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

P.-H. Vial, P. Magron, T. Oberlin, C. Févotte, **Phase retrieval with Bregman divergences and application to audio signal recovery**, submitted to the IEEE Journal on Selected Topics in Signal Processing, January 2021.
[Paper](https://arxiv.org/abs/2010.00392) [Demo](/demos/jstsp21.html)

P. Magron, C. Févotte, **Leveraging the structure of musical preference in content-aware music recommendation**, submitted to IEEE ICASSP, June 2021.
[Paper](https://arxiv.org/abs/2010.10276)

P. Magron, P.-H. Vial, T. Oberlin, C. Févotte, **Phase recovery with Bregman divergences for audio source separation**, submitted to IEEE ICASSP, June 2021.
[Paper](https://arxiv.org/abs/2010.10255)

## Journals

P. Magron, T. Virtanen, **Online Spectrogram Inversion for Low-Latency Audio Source Separation**, IEEE Signal Processing Letters, Vol. 27, pp. 306-310, 2020.
[Paper](https://arxiv.org/abs/1911.03128) [Demo](/demos/spl20_omisi.html) [Code](https://github.com/magronp/omisi)

P. Magron, T. Virtanen, **Complex ISNMF: a phase-aware model for monaural audio source separation**, IEEE/ACM Transactions on Audio, Speech and Language Processing, Vol.27, no. 1, pp. 20-31, January 2019.
[Paper](https://arxiv.org/abs/1802.03156) [Demo](/demos/taslp19_cisnmf.html) [Code](https://github.com/magronp/complex-isnmf)

P. Magron, R. Badeau, B. David, **Model-based STFT phase recovery for audio source separation**, IEEE/ACM Transactions on Audio, Speech and Language Processing, Vol.26, no. 6, pp. 1095-1105, June 2018.
[Paper](https://arxiv.org/abs/1608.01953) [Demo](/demos/taslp18_puiter.html) [Code](https://github.com/magronp/pu-iter)


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

