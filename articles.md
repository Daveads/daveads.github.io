---
layout: default
title: articles
lang: en
---


<div class="posts">
  {% for post in site.posts %}
	
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
    </article>
	
  {% endfor %}
</div>