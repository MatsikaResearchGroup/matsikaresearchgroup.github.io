---
title: "Matsika Lab - Pictures"
layout: piclay
excerpt: "Matsika Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [Temple](#temple), [Philadelphia](#philadelphia)


## Temple

#### Current Group: Fall 2023
<!--<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>-->

<figure>
  <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/group_f23.jpg" width="60%" class="imagesize img-responsive center-block" />
  <figcaption> (from left to right) Juan, Maneesh, Dakshitha, Matsika,  Vaibhav, Sabrina, Mohammed, Divya, Carson and Jose.
  </figcaption>
</figure>

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

<p> &nbsp; </p>

### Mohammed's thesis defense 2023
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/md_diss.jpeg" width="40%">
</figure>

### Undergraduate research program poster presentation (CST) 2023
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/urp23.jpeg" width="40%">
</figure>

### Vaibhav and Daksh visit to Spokane, WA 2023
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/spokane.jpeg" width="40%">
<figcaption> <a href="https://aps.org/meetings/meeting.cfm?name=DAMOP23">The APS DAMOP Conference, June 5-9, 2023</a>
</figcaption>
</figure>

### Undergraduate research program poster presentation (CST) 2021
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/urpposterpres.png" width="50%">
</figure>

### Mushir's visit to Park City, Utah 
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/utah.jpg" width="30%">
<figcaption> <a href="https://utahworkshop2019.com/index.htm">The Utah Workshop on Quantum Methods in Molecular and Solid-State Theory, September 22-27, 2019</a>
</figcaption>
</figure>

### Pratip's visit to Troms<span>&#248;</span>, Norway 
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/collage-pratip.jpg" width="40%">
<figcaption> <a href="http://www.istcp-2019.org/">10th Congress of the International Society of Theoretical Chemical Physics 2019</a>
</figcaption>
</figure>

## Philadelphia
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/phillycollage.jpg" width="60%" >
</figure>

<!--## Cornell
From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>-->

<!--## St Andrews
From the [group of Felix Baumberger](http://dqmp.unige.ch/baumberger/) (now at University of Geneva).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">
</figure>-->
