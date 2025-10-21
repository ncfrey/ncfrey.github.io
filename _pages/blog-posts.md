---
layout: archive
permalink: /blog-posts/
title: "Blog posts"
description: "Writings on AI-native drug discovery and machine learning for therapeutic development. Perspectives on foundation models, autonomous drug discovery systems, and practical guidance for scientists, researchers, students, and leaders navigating the AI transformation in biopharma."
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---

{% include base_path %}

I write about machine learning and biology, with a focus on practical applications in drug discovery, AI strategy for biotech, and career guidance for computational scientists. Below are featured articles that give an idea for what I like to write about - read the full posts on [Substack](https://ncfrey.substack.com/).

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
