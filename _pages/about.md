---
layout: about
title: About
permalink: /
description: He/Him/His | PhD Student | Viterbi School of Engineering, USC

profile:
  align: right
  image: prof_pic.jpg
  address: >
    <p>Los Angeles</p>

news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
years: [2021, 2020]
---

I am currently a PhD student at [University of Southern California](https://usc.edu/), advised by [Xuehai Qian](http://alchem.usc.edu/~xuehaiq/).

Please refer to [our group's webpage](http://alchem.usc.edu/portal/index.html) for my research.

---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
