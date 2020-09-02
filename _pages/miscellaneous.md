---
-layout: archive
title: "Miscellaneous"
permalink: /miscellaneous/
author_profile: true
---
My hometown is [Shanghai, China](https://en.wikipedia.org/wiki/Shanghai).

Besides academics, I am an amateur runner and chess player. My [lichess](https://lichess.org/) rating is around top 10%. My profile photo was taken after I finished my first half marathon in May 2018.  

I have been very successful in fighting with obesity. In 2017, my body weight dropped from [100kg](https://chendancmu.github.io/files/photos/100.jpeg) to [69kg](https://chendancmu.github.io/files/photos/69.jpeg) in 6 months: [before](https://chendancmu.github.io/files/photos/before.jpeg),  [after](https://chendancmu.github.io/files/photos/after.jpeg).

[Here](https://www.zhihu.com/question/49249958/answer/115964465) is a story (in Chinese) about how I independently re-discovered *Poncelet's Theorem* [[1]](http://user.math.uzh.ch/halbeisen/publications/pdf/poncelet.pdf) [[2]](https://mathworld.wolfram.com/PonceletsPorism.html) in 2011 as a high-schooler. It is among the top-voted answers in the maths category of zhihu.com (Chinese version of Quora).

I like free and open-source software, especially the ones that respect user privacy. Some of my favourites are: [Debian](https://www.debian.org/), [Lineage OS](https://lineageos.org/), [F-Droid](https://f-droid.org/), [Signal](https://www.signal.org/), [Zotero](https://www.zotero.org/), [Joplin](https://joplinapp.org/).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

