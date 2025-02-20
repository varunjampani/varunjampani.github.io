---
title: "Varun Jampani - Home"
layout: gridlay
excerpt: "Varun Jampani"
sitemap: false
permalink: /
---

<div class="container-fluid">

<div class="row">

<div class="col-sm-8">

I am VP Research at Stability AI, leading the generative vision research on image, video and 3D foundation models. In the past, I was a researcher at Google Research and Nvidia Research. I completed my PhD at [Perceiving Systems](https://ps.is.tuebingen.mpg.de) department, Max-Planck Institute (MPI) for Intelligent Systems in T&uuml;bingen, Germany. My PhD advisor was [Prof. Peter V. Gehler](http://files.is.tue.mpg.de/pgehler//).
I did my bachelors and masters in Computer Science at [IIIT-Hyderabad](https://www.iiit.ac.in), India.

<!-- My work lies at the intersection of Computer Vision and Machine Learning. Specifically, I am working on leveraging machine learning techniques for understanding and improving computer vision models. The main research question is how different components of a computer vision system need to learn and interact with each other for robust perception. -->

<!-- My research interests include 3D/4D Computer Vision and Machine Learning. Specifically, I am mainly interested in automatic 3D and 4D object understanding from internet image collections and videos leveraging both reconstruction and generation techniques. In addition, I also work on understanding and generating creative images such as visual metaphors, paintings etc. -->

At Stability AI, we strive to advance the state-of-the-art in vision foundation models with diverse applications in understanding, reconstruction and generation tasks in both 2D and 3D. A central research question is how to train generative models that can act as generic yet powerful priors for the visual world around us.


<!-- **_I am looking for motivated students for collaborations and internships. If interested, please drop me an email with your CV._** -->

**_If you are interested in joining my Generative Vision team at Stability or research collaborations or internships, please drop me an email with your CV._**
  
<!-- **_We have research scientist and software engineer positions in our team in Google Research. Please drop me an email with your CV if you are interested in applying._** -->

### News
{% for article in site.data.news limit:9 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
<a href="{{ site.url }}{{ site.baseurl }}/allnews.html">see all news</a>

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:left">

  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_pic.jpeg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->

  <A HREF="mailto:&#118;&#097;&#114;&#117;&#110;&#106;&#097;&#109;&#112;&#097;&#110;&#105;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;">&#118;&#097;&#114;&#117;&#110;&#106;&#097;&#109;&#112;&#097;&#110;&#105;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;</A> <br>
  Stability AI <br>
  Boston, MA, USA.<br>


</div>

</div>
</div>

<div class="col-sm-12">

### Publications
  
Refer to my <a href="https://scholar.google.com/citations?hl=en&user=1Cv6Sf4AAAAJ&view_op=list_works"> Google Scholar </a> page for a more up-to-date list of publications.

{% for publi in site.data.publist limit:30 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

<!--  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" /> -->

<!--  <p>{{ publi.description }}</p> -->

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">see all publications</a>

</div>

<div class="col-sm-12">

### Theses

{% for publi in site.data.theseslist limit:6 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<p> &nbsp; </p>

</div>
