---
layout: archive
title: "Publications and Projects"
permalink: /publications/
author_profile: true

{% include base_path %}

<h2>Publications</h2>
{% assign pubs = site.publications | where: "type", "publication" | sort: "date" %}
{% for post in pubs reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Projects</h2>
{% assign projs = site.publications | where: "type", "project" | sort: "date" %}
{% for post in projs reversed %}
  {% include archive-single.html %}
{% endfor %}
