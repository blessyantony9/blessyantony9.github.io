---
layout: page
title: "Publications"
permalink: /publications/
---

The latest list is also on [Google Scholar]({{ site.author.googlescholar }}).

{% assign peer_reviewed = site.publications | where: "type", "peer-reviewed" | sort: "date" | reverse %}
{% assign preprints = site.publications | where: "type", "preprint" | sort: "date" | reverse %}
{% assign under_review = site.publications | where: "type", "under-review" | sort: "date" | reverse %}

{% if peer_reviewed.size > 0 %}
<div class="pub-group">
<h2>Peer-reviewed</h2>
<ul class="pub-list">
  {% for pub in peer_reviewed %}
  <li>
    <div class="pub__title">{% if pub.paperurl %}<a href="{{ pub.paperurl }}" target="_blank" rel="noopener">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</div>
    <div class="pub__authors">{{ pub.authors | replace: "Antony, B.", "<strong>Antony, B.</strong>" }}</div>
    <div class="pub__meta">{{ pub.venue }}, {{ pub.date | date: "%Y" }}</div>
  </li>
  {% endfor %}
</ul>
</div>
{% endif %}

{% if preprints.size > 0 %}
<div class="pub-group">
<h2>Preprints</h2>
<ul class="pub-list">
  {% for pub in preprints %}
  <li>
    <div class="pub__title">{% if pub.paperurl %}<a href="{{ pub.paperurl }}" target="_blank" rel="noopener">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</div>
    <div class="pub__authors">{{ pub.authors | replace: "Antony, B.", "<strong>Antony, B.</strong>" }}</div>
    <div class="pub__meta">{{ pub.venue }}, {{ pub.date | date: "%Y" }}</div>
  </li>
  {% endfor %}
</ul>
</div>
{% endif %}

{% if under_review.size > 0 %}
<div class="pub-group">
<h2>Under review</h2>
<ul class="pub-list">
  {% for pub in under_review %}
  <li>
    <div class="pub__title">{{ pub.title }}</div>
    <div class="pub__authors">{{ pub.authors | replace: "Antony, B.", "<strong>Antony, B.</strong>" }}</div>
    <div class="pub__meta">{{ pub.venue }}, {{ pub.date | date: "%Y" }}</div>
  </li>
  {% endfor %}
</ul>
</div>
{% endif %}
