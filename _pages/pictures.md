---
title: "Dries Lab - Pictures"
layout: piclay
excerpt: "Dries Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [BUMC](#bumc), [Dana-Farber Cancer Institute](#dana-farber-cancer-institute)


## BUMC

<!--
#### Timelapse of our STM assembling [(see LION news item)](https://www.physics.leidenuniv.nl/index.php?id=11573&news=867&type=lion&ln=EN):
<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

-->

<p> &nbsp; </p>


## Dana-Farber Cancer Institute
From the [group of Rani George](https://ranigeorgelab.dana-farber.org/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/george_lab.jpg" width="60%">
</figure>  



From the [group of Guo-Cheng Yuan](http://bcb.dfci.harvard.edu/~gcyuan/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/GC_lab.jpg" width="60%">
</figure>