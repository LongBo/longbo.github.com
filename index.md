---
layout: page
title: Hello World!
tagline: My blog is here
---
{% include JB/setup %}


##Welcome 
    
    This is : My Blog =)
    
    My information :
      name : LongBo
      eMail : longbo0820(@)gmail.com
      github : LongBo
      sinaWeibo: (http://weibo.com/lunbor)
      


Here's a my "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

@做真正重要的事，关心真正重要的人
