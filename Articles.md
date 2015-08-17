---
layout: page
title: Articles
---

<p class="message">
  Hi！下面是这个站点内的全部文章了，希望你可以在里面找到你想要的内容。
</p>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>