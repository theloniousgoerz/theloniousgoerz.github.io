---
layout: page
title: "Teaching & Talks"
permalink: /teaching/
excerpt: "Teaching experience and conference presentations."
deck: "Courses I have taught, and conference talks and posters."
---

## Teaching

- **Teaching Assistant**, SOC 1101 Introduction to Sociology, Cornell University, Summer 2024

## Presentations

<ul class="pres">
{% for pr in site.data.presentations %}
  <li>
    <span class="pr-year">{{ pr.year }}</span>
    <span>
      <span class="pr-title">{{ pr.title }}</span>{% if pr.award %}<span class="award">{{ pr.award }}</span>{% endif %}
      <br><span class="pr-venue">{{ pr.venue }}</span>
    </span>
  </li>
{% endfor %}
</ul>
