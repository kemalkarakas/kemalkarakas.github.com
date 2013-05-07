---
layout: page
title: 
tagline:
---
{% include JB/setup %}

{% for post in site.posts %}
<article>
	<h3 style="margin: 0px; padding: 0px; color: #191919"><a href="{{ BASE_PATH }}{{ post.url }}" style="margin: 0px; padding: 0px; color: #333">{{ post.title }}</a></h3>
	<p style="color: #666">{{ post.date | date_to_string }}</p>
</article>
  {% endfor %}



