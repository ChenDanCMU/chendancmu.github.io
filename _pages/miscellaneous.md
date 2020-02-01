---
-layout: archive
title: "Miscellaneous"
permalink: /miscellaneous/
author_profile: true
---
My hometown is [Shanghai, China](https://en.wikipedia.org/wiki/Shanghai).

Besides academics, I am an amateur runner and chess player. I have finished 3 half marathons since May 2018. My [lichess](https://lichess.org/) rating is around top 10%. 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

