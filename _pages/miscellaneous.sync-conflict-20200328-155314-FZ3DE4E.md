---
-layout: archive
title: "Miscellaneous"
permalink: /miscellaneous/
author_profile: true
---
My hometown is [Shanghai, China](https://en.wikipedia.org/wiki/Shanghai).

Besides academics, I am an amateur runner and chess player. I have finished 3 half marathons since May 2018. My [lichess](https://lichess.org/) rating is around top 10%. 

I like open-source software, especially the ones that respect user privacy. Some of my favourites are: [Debian](https://www.debian.org/), [Lineage OS](https://lineageos.org/), [F-Droid](https://f-droid.org/), [Signal](https://www.signal.org/), [Zotero](https://www.zotero.org/), [Joplin](https://joplinapp.org/).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
