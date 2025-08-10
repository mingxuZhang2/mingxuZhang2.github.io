---
layout: archive
title: "Publications and Projects"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<h2>Publications</h2>
<div class="list__wrapper">
{% assign pubs = site.publications | where: "type", "publication" | sort: "date" %}
{% for post in pubs reversed %}
  <div class="list__item">
    {% include archive-card.html %}
  </div>
{% endfor %}
</div>

<h2>Projects</h2>
<div class="list__wrapper">
{% assign projs = site.publications | where: "type", "project" | sort: "date" %}
{% for post in projs reversed %}
  <div class="list__item">
    {% include archive-card.html %}
  </div>
{% endfor %}
</div>
