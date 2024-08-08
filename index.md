---
title: JRG blog
---

# Bienvenido a mi blog

Este es el índice de mi blog. Aquí encontrarás todas mis publicaciones.

{% for post in site.posts %}
  * [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}