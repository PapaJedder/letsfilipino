---
layout: home
title: "Teach"
---

Let's Teach

{% for p in site.teach %}

[{{ p.title }}]( {{ p.url | prepend: site.baseurl }})

{{ p.excerpt }}

{% endfor %}