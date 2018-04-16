---
layout: default
title:  Research
class: Research
---


{%  assign index = 1 %}
{% for post in site.posts %}



<h3><a href="{{ post.url }}"> <center>{{ post.title }} </center> </a> </h3>

 <center><img src="/assets/post_images/{{ index }}a.JPG" width="500px"></center>  <br> <br> <br> 
 {% assign index = index | plus: 1 %}

{% endfor %}


