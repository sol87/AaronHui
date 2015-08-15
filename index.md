---
layout: page
title: 主页测试
tagline: 志高心正，知行合一
---
{% include JB/setup %}

# 欢迎来到我的博客

现在是我第一次测试jekyll生成博客并发布到Github的功能。
希望我可以成功。


# 文章列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 如果我成功了

那么我会尽量分享一些内容上来的。
我是一名CG公司的TD，工作中，我主要使用Python、Qt进行一系列小型桌面软件和软件插件开发。因为工作需要和个人兴趣，我也一直在研究和学习图形软件开发、CG项目管理等方面的知识。

##我说完了，愿我成功吧！