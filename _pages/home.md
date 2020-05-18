---
title: "Complex Data Lab - Home"
layout: homelay
excerpt: "Complex Data Lab at McGill University."
sitemap: false
permalink: /
---

We are a dynamic research group at the [Leiden Institute of Physics](http://www.physics.leidenuniv.nl). Our aim is to explore and understand [quantum materials](http://condensedconcepts.blogspot.nl/2013/05/what-is-quantum-matter.html), including strange metals, high-temperature superconductors, and quantum critical electron matter.


<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        {% for img in site.data.home_carousel %}
            {% if forloop.index == 1 %}
                <li data-target="#carousel" data-slide-to="{{ forloop.index }}" class="active"></li>
            {% else %}
                <li data-target="#carousel" data-slide-to="{{ forloop.index }}"></li>
            {% endif %}
        {% endfor %}
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        {% assign class = "item active" %}
        {% for img in site.data.home_carousel %}
            <div class="{{ class }}">
                <img src="{{ site.url }}{{ site.baseurl }}/assets/{{ img }}" alt="{{ img }}" />
            </div>
            {% assign class = "item" %}
        {% endfor %}
    </div>

<a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
</a>
<a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
</a>
</div>




To this end, we develop novel spectroscopic-imaging scanning tunneling microscopy (SI-STM) tools to visualize the relevant quantum mechanical degrees of freedom. We want to be able to build the perfect instruments to answer the  scientific questions we deem most important (see [Research](research)).

We are located at Leiden University, the birthplace of superconductivity and home to Kamerlingh Onnes, Lorentz, Huygens, Einstein, de Sitter, and others (see e.g. [the wall of signatures from Ehrenfest lecturers](https://www.lorentz.leidenuniv.nl/history/colloquium/muur_heel.html)). We exchange ideas and work with our neighbors from [Quantum Matter & Optics](http://www.physics.leidenuniv.nl/qo-home), as well as with the colleagues from our [world-class theory section](https://www.lorentz.leidenuniv.nl).

 **We are  looking for passionate new PhD students, Postdocs, and Master students to join the team** [(more info)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


We are grateful for funding from Leiden University, [NWO](www.nwo.nl) ([Vidi talent scheme](http://www.nwo.nl/en/research-and-results/programmes/Talent+Scheme) and the [Frontiers in Nanoscience program](https://www.universiteitleiden.nl/en/research/research-projects/science/frontiers-of-nanoscience-nanofront)), and from an [ERC starting grant](https://erc.europa.eu/funding/starting-grants).

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/logopic/Logo_Leiden.jpg" style="width: 210px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/logopic/Logo_Nanofront.jpg" style="width: 110px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/logopic/Logo_NWO.jpg" style="width: 120px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/logopic/Logo_ERC.jpg" style="width: 110px">
</figure>