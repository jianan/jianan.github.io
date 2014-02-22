---
layout: page
title: Jianan's Github Page
tagline: 
---

## Pages

[QTLpvl vignettes][qtlpvl-ghpages]

## Blog post list
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


Sources on [github][mygithub].

---
My parts of this web site are licensed under
[CC BY](http://creativecommons.org/licenses/by/3.0/).

[![CC BY](http://i.creativecommons.org/l/by/3.0/88x31.png)](http://creativecommons.org/licenses/by/3.0/)


[mygithub]: https://github.com/jianan/jianan.github.io
[qtlpvl-r]: https://github.com/jianan/qtlpvl/tree/master
[qtlpvl-ghpages]: https://github.com/jianan/qtlpvl/tree/gh-pages
