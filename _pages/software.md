---
title: "Dries Lab - Software"
layout: gridlay
excerpt: "Dries Lab -- Software"
sitemap: false
permalink: /software/
---


# Software


{% assign number_printed = 0 %}
{% for softw in site.data.softwlist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if softw.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ softw.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ softw.image }}" class="img-responsive" width="50%" style="float: left" />
  <p>{{ softw.description }}</p>
  <p><em>{{ softw.authors }}</em></p>
  <p><strong><a href="{{ softw.link.url }}">{{ softw.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ softw.news1 }}</strong></p>
  <p> {{ softw.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>