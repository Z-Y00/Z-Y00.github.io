---
layout: about
title: About
permalink: /
subtitle: They/Them | PhD | Viterbi School of Engineering, USC

profile:
  align: right
  image: prof_pic.jpg
  # address: >
    # <p>Los Angeles</p>

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
years: [2022,2021, 2020]
---

I am currently a PhD at [University of Southern California](https://usc.edu/), advised by [Xuehai Qian](http://alchem.usc.edu/~xuehaiq/).

Please refer to [our group's webpage](http://alchem.usc.edu/portal/index.html) for my research.

My [Resume](https://z-y00.github.io/academic/assets/pdf/Rao_CV.pdf).

## Publications

<div class="publications">

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
