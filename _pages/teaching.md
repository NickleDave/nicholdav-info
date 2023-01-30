---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

I am a trained [Carpentries](https://carpentries.org/)
instructor and have helped
organize and teach several Software Carpentry workshops.
Additionally I have organized and taught
similar material spread out over a semester
(not official classes, but just an informal meeting of researchers).
All of this teaching was done
under the umbrella of the
[graduate data science group](https://data-science-for-scientists-atl.github.io/)
I helped found while at Emory University.

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
