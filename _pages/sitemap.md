---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

Here's the sitemap.

<h2>Researches</h2>
{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

<h2>Teaching Materials</h2>
{% for post in site.teaching %}
  {% include archive-single.html %}
{% endfor %}

<h2>Personal</h2>
{% for post in site.personal %}
  {% include archive-single.html %}
{% endfor %}

