---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find the latest list of my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
