---
title: Aula 9 - Trabalhando com formulários
nav_order: 9
has_children: true
has_toc: false
#youtubeId: 8pW5SjU7Ggs
next: ../10
---

{% assign title = page.title | split: "-"  %}
{% assign slide =  title[1] | replace: " ", "-" | prepend: page.nav_order %}

{% if page.nav_order < 10 %}
{% assign slide =   slide | prepend: "0" %}
{% endif %}


## {{ title | slice: 1 }}

### Recurso

<span class="fs-3">
  <a href="{{site.baseurl}}/assets/downloads/{{ slide }}.pdf" class="btn" target="_blank">Notas de aula</a>
<a href="https://www.icloud.com/keynote/036ORKpdcKVbm4SNnwStcfUQQ#13-Autenticacao-e-Autorizacao" class="btn" target="_blank">Slides com animação</a>
</span>

{% comment %}
{% include youtubePlayer.html id=page.youtubeId %}
{% endcomment %}


<span class="fs-3 float-right">
[Próxima aulas]({{page.next}}){: .btn }
</span>

