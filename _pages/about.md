---
permalink: /
title: "Robert McLaughlin"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello!

I am a PhD Candidate at UC Santa Barbara.
I study smart contract security and decentralized finance.
I am advised by Giovanni Vigna and Christopher Kruegel.

## CV

[Download my CV here](/files/CV.pdf)

## Recent Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

