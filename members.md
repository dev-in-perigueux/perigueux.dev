---
layout: page
title: Membres
permalink: /membres/
---

Membres listé·e·s sur le site (d'autres participent [aux réunions et à la liste de diffusion](/nous-rejoindre/) sans être forcément repris·es ici) :

{% assign members = site.members | sorby: firstname, lastname %}
{% assign size = members | size %}

{% if size > 0 %}
<ul>
  {% for member in members %}
    <li>
      <a href="{{ member.url }}">{{ member.firstname }} {{ member.lastname }}</a>
    </li>
  {% endfor %}
</ul>
{% endif %}