---
layout: default
title: Tags
permalink: /tags/
mainnavitem: false
---
{% include relBase.html %}
<h1>Tags</h1>
<div class="archives">
  {% for tag in site.tag %}
  <div class="archive-group">
    {% capture tag_name %}{{ tag | first }}{% endcapture %}
    <div id="#{{ tag_name | slugize }}"></div>
    <p></p>

    <h3 class="tag-head">{{ tag_name }}</h3>
    <a name="{{ tag_name | slugize }}"></a>
    {% for post in site.tags[tag_name] %}
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