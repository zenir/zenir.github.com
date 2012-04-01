---
layout: page
title: Ihaveu Team
tagline: 
---
{% include JB/setup %}
<p>这是 zenir 的个人网站的最新版本，使用 <a href="https://github.com/mojombo/jekyll">Jekyll</a> 搭建。</p>
<p>创作是一件开心的事情，沉浸只是因为纯粹的灵感。我希望自己的生命能够时常充满灵感，而文字就是这些愉快时光曾经存在过的证明。</p>
<p>                                                  --Livid</p>

<h4>最近发布的文章</h4>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

