---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Here are a few of my published research projects, but there are more in the works!

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

![Landscape with sea ice, glacial ice, and rock](../images/seaice.jpg)
<sup>Sea ice breakup in the Lemaire Channel, Antarctica</sup>