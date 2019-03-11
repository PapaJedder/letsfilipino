---
author: Papa Jedder
title: Western Names
categories: [baybayin]
---

<link href="{{ site.baseurl }}/assets/css/baybayin.css" rel="stylesheet">

<table>
{% assign names = site.data.western-names | sort: "name" %}
{% for n in names  %} 
<tr>
  <td>{{ n.name }}</td>
  <td>{{ n.readit }}</td>
  <td class="font-baybayin">{{ n.writeit }}</td>
  <td>{{ n.notes }}</td>
 </tr>
{% endfor %}
  
</table>
