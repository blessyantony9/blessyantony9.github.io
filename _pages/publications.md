---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find the latest list of my publications on [my Google Scholar profile](https://scholar.google.com/citations?hl=en&authuser=1&user=nGvGIhcAAAAJ).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
