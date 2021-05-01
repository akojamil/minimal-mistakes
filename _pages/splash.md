---
layout: archive
title: "Splash"
permalink: /splash/
author_profile: true

feature_row2:
  - image_path: assets/exo.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'The [Enriched Xenon Observatory (EXO)](https://www-project.slac.stanford.edu/exo/) is an experiment searching for the neutrino-less double beta decay $(0\nu\beta\beta)$ of ${}^{136}\mathrm{Xe}$. It's a hypothetical decay that can only occur if neutrinos are Majorana fermions, i.e. if the neutrinos are their own anti-particles. The detector technology is a (LXe) time projection chamber (TPC) filled with ~150kg of liquid xenon. While current experimental limits have excluded the existence of $0\nu\beta\beta$ with half-lifes shorter than $\sim 10^{26}$ years, the next generation experiment at the tonne scale is already being planned ...'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/nexo.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}