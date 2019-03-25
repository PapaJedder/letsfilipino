---
layout: category
tite: Video
permalink: /videos/
---


{%  for post in site.videos %}
<a href="{{ post.url }}">{{ post.title }}</a>

{% endfor %}
