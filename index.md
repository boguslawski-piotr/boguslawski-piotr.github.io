---
layout: default
author: Piotr Boguslawski
---
{% for post in site.posts %}

{{ post.date | date_to_string }} 
{{ post.content }}
	
{% endfor %}
