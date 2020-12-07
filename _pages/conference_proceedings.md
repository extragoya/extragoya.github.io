---
layout: archive
title: "Conference Proceedings"
permalink: /conference_proceeedings/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.conference_proceeedings reversed %}
  {% include archive-single.html %}
{% endfor %}
