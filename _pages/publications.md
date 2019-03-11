---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This is a page with Quentin's scientific publications. It will be filled out soon. For now, visit [Q's old publications page](https://quentinread.weebly.com/publications) or you can find the articles on <u><a href="{{author.googlescholar}}"Google Scholar</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


