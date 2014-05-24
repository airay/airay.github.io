---
layout: default
title: 主页
---
#个人简介#
    孤独的码农......一个不想熬夜的码农，乐于开发任何有趣的项目。
#联系#
    * Email : jianlei_zju@163.com
    * Weibo : ![新浪微博](/assets/ico.png) <http://www.weibo.com/2274950957/profile?rightmod=1&wvr=5&mod=personinfo> 
#TODO#
#文章列表#
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



