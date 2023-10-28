---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
This page only lists recent publications, for the full list, please go to [Google Scholar](https://scholar.google.com/citations?user=WDbZYj0AAAAJ&hl=en).
(* indicates corresponding author)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
