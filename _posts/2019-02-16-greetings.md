---
title: Basic Greetings
categories: Translation
tags: ["translation", "bikol", "kapampangan"]
---

{% assign greeting = site.data.hambingan-basic-greetings %}
{% for s in greeting.salita  %}
<table>
<thead>
<td>Wika</td>
<td>Pagbati</td>
</thead>
<tr> 
    <td>Tagalog</td>
    <td>{{ s.tagalog }}</td>
</tr>
<tr>
    <td>Bikol</td>
    <td>{{ s.bikol }}</td>
</tr>
<tr>
    <td>Kapmapangan</td>
    <td>{{ s.kapampangan }}</td>
</tr>
<tr>
    <td>Bisya</td>
    <td>{{ s.bisaya }}</td>
</tr>
<tr>
    <td>Ilokano</td>
    <td>{{ s.ilokano }}</td>
</tr>
</table>
{% endfor %}


