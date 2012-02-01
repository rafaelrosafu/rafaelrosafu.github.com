---
layout: page
title: Ruby, Anarchy, Cinema and Pandas
---
{% include JB/setup %}

<a href="http://www.flickr.com/photos/sebastian_bergmann/1436871395/lightbox/" target="_blank"><img alt="Pandas are nice" src="http://farm2.staticflickr.com/1036/1436871395_af80bc7188_m.jpg"/></a>
<p class="small right"><a href="http://www.flickr.com/photos/sebastian_bergmann/1436871395/lightbox/" target="_blank">Photo by Sebastian Bergmann</a> - <a href="http://creativecommons.org/licenses/by-sa/2.0/" target="_blank">Creative Commons</a></p>

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
