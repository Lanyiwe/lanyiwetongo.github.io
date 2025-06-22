---
layout: page
title: Publications
permalink: /Publications/
---

## Mes articles et publications

Bienvenue sur mon espace de publication. Vous trouverez ici des articles, réflexions, et ressources sur la statistique, la science des données et les politiques publiques.

Voici la liste de mes publications et articles :

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>
