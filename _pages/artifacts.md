---
layout: archive
title: "Experience"
permalink: /artifacts/
author_profile: true
---

{% include base_path %}

{% for post in site.artifacts reversed %}
  {% include archive-single-talk-cv.html type='grid'%}
{% endfor %}
