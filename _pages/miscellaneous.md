---
-layout: archive
title: "Miscellaneous"
permalink: /miscellaneous/
author_profile: true
---
Misc.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

