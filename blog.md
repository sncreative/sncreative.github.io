---
layout: default
title: Blog - SN Creative
description: Celebrate a graduation ceremony with SN Creative’s graduation party invitations and greeting cards. Whether it’s you or someone you love, mark the milestone with any of our graduation themed templates.
---

<div class="header">
<div class="container">
<div class="row">
<div class="col-md-12">
<div class="logo">
<a href="{{site.url}}"><img src="{{site.url}}/images/logo.png" class="img-responsive"></a>
</div>		
</div>
</div>
</div>
</div>

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

<div class="footer">
<div class="container">
<div class="row">
<div class="col-md-12">	
</div>
</div>
</div>
</div>
