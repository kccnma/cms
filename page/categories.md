---
layout: default
title: Categories
permalink: /categories/
mainnavitem: false
---
{% include relBase.html %}
<h1>Categories</h1>
<div class="archives">
  {% for category in site.categories %}
  <div class="archive-group">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}"></div>
    <p></p>

    <h3 class="category-head">{{ category_name }}</h3>
    <a name="{{ category_name | slugize }}"></a>
    {% for post in site.categories[category_name] %}
    <article class="archive-item">
      {%- if post.thumbnail -%}
      <div class="featured-image thumb-image">
        <a href="{{ relBase }}{{ post.url | remove_first: '/' }}index.html"><img src="{{ relBase }}{{ post.thumbnail }}"
            alt="{{ post.title }}" /></a>
      </div>
      {%- endif -%}
      <h4><a href="{{ relBase }}{{ post.url | remove_first: '/' }}index.html">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
  {% endfor %}
</div>