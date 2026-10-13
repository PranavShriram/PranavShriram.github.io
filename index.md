---
layout: default
title: About
---
<section class="profile">
  {% if site.author.photo %}<img class="avatar" src="{{ site.author.photo | relative_url }}" alt="{{ site.author.name }}">{% endif %}
  <div>
    <h1>{{ site.author.name }}</h1>
    <p class="affil">
      {{ site.author.position }}<br>
      {{ site.author.university }}
    </p>
    {% include social.html %}
    <p class="quote">&ldquo;I like finding solutions to problems and problems in solutions&rdquo;</p>
  </div>
</section>

<div markdown="1">
I am a third year computer science PhD student at the University of Illinois Urbana-Champaign, where I work
on applied cryptography with Prof. [Ling Ren](https://sites.google.com/view/renling) and Prof. [David Heath](https://daheath.web.illinois.edu).
I have worked on specialized secure multiparty computation protocols such as private information retrieval,
private range queries, and private aggregation.

Before UIUC, I did my B.Tech in Computer Science at NIT Trichy.
</div>

<p><a href="{{ '/research/' | relative_url }}">Publications &rarr;</a></p>

<img class="corner-bear" src="{{ '/files/koala.svg' | relative_url }}" alt="" aria-hidden="true">
