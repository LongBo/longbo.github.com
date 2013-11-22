---
layout: page
title: Hello World!
tagline: My blog is here
---
{% include JB/setup %}


##Welcome 
    
    This : My Blog =)
    
    My information :
      name : Long Bo
      email : longbo0820@gmail.com
      github : LongBo
      twitter : @lunbor
      sina weibo: (http://weibo.com/lunbor)


Here's a my "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

支持中文吧。

