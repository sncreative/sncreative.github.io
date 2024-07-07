---
layout: default
title: Blog - SN Creative
description: Blog
---

<div class="main">
<div class="container">

  <div class="row">
  <div class="col-md-12">
  <h2>Latest Posts</h2>
  </div>
  </div>

<div class="row">
{% for post in site.posts %}
<div class="col-md-4">
{% if page.featured_image %} <img src="{{ page.featured_image }}" alt="Featured Image"> {% endif %}
<a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}
</div>  

</div>
</div>
