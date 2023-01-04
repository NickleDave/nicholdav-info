---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---


Please see also this <u><a href="https://www.youtube.com/watch?v=1XEDFpUGmqs&list=PLwh2l2mW-rlqxP4NpjsacS3SoK3RUDUx1">playlist on YouTube</a>.</u>

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
