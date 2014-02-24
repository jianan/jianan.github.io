---
layout: page
title: Jianan's Github Page
tagline: 
---

## Pages

[QTLpvl vignettes][qtlpvl-vig]

## Blog post list
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


Sources on [github][mygithub].


[qtlpvl-vig]: http://jianan.github.io/qtlpvl
[mygithub]: https://github.com/jianan/jianan.github.io
[qtlpvl-r]: https://github.com/jianan/qtlpvl/tree/master
[qtlpvl-ghpages]: https://github.com/jianan/qtlpvl/tree/gh-pages
