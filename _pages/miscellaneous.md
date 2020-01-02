---
-layout: archive
% title: "Miscellaneous"
permalink: /miscellaneous/
author_profile: true
---
My hometown is [Shanghai, China](https://en.wikipedia.org/wiki/Shanghai).

Besides academics, I am an amateur runner and chess player. I lost 30kg (~70 lbs) of body weight in 6 months by running and have finished 3 half marathons since then. My [lichess](https://lichess.org/) rating is around top 10%. 

I like open-source software, especially the ones that respect user privacy. Some of my favourites are: [Debian](https://www.debian.org/), [Lineage OS](https://lineageos.org/), [F-Droid](https://f-droid.org/), [Signal](https://www.signal.org/), [Zotero](https://www.zotero.org/), [Joplin](https://joplinapp.org/).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

