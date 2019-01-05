---
layout: page
title: "Notes"
description: "Notes"
permalink: /notes/
---

{% for post in site.notes %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<!--
<section id="notes">
  {% for post in site.posts %}
       <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </ul>
</section>
-->
