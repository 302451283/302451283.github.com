---
layout: page
title: 美好生活...
---
{% include JB/setup %}


## 坚定不移地去做正确的事情 

    
    你也许会累
   
    你也许会迟疑
      
    勇敢的向前走
      
	  
## 照顾好自己...


##Update：
-------------

<ul class="posts">
{% for post in site.posts %}
<li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>; <span>{{ post.date | date_to_string }}</span> </li>
{{ post.excerpt }}
{% endfor %}
</ul>




