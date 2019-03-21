---
layout: archive
title: "Publications and Talks"
permalink: /publications/
author_profile: true
---

## Publications

These are Quentin's scientific publications and talks. You can also visit [Q's old publications page](https://quentinread.weebly.com/publications) or you can find the articles on [Q's Google Scholar profile page](https://scholar.google.com/citations?user=nW17_vcAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Talks

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
