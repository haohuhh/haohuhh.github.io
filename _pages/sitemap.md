---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Researches</h2>
{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

<h2>Teaching Materials</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

<h2>Personal</h2>
{% for post in site.personal %}
  {% include archive-single.html %}
{% endfor %}

