---
layout: publication
title: Publications
permalink: /publications/
---

Here is a list of my latest publications, broadly sorted by research topic. Please see [my CV](../cv), or [my ADS page][kg-ads] for a full list of my publications.

[kg-ads]: https://ui.adsabs.harvard.edu/search/p_=0&q=author%3A%22Gerbig%2C%20Konstantin%22&sort=date%20desc%2C%20bibcode%20desc


<span style="color:#800020">**Planetesimal Formation Theory**</span>
* Cui, Gerbig, et al. (2025), [ApJ 986, 86](https://iopscience.iop.org/article/10.3847/1538-4357/add146)
* Gerbig, Lin, & Lehmann (2024), [ApJ 961, 183](https://iopscience.iop.org/article/10.3847/1538-4357/ad1114)
* Gerbig & Li (2023), [ApJ 949, 81](https://iopscience.iop.org/article/10.3847/1538-4357/acca1a) 
* Gerbig, Murray-Clay, Klahr, & Baehr (2020), [ApJ 895, 91](https://ui.adsabs.harvard.edu/abs/2020ApJ...895...91G/abstract)
* Gerbig, Lenz, & Klahr (2019), [A&A 629, A116](https://www.aanda.org/articles/aa/full_html/2019/09/aa35278-19/aa35278-19.html) 

<span style="color:#800020">**Formation and Characterization of Planet-Hosting Binary Systems**</span>
* Trierweiler, Gerbig, & Rice (2025), [Accepted to ApJ](https://arxiv.org/abs/2512.02135)
* Hand, Gerbig, & Rice (2025), [ApJL 985, 1](https://iopscience.iop.org/article/10.3847/2041-8213/adce04)
* Gerbig, Rice, Zanazzi, Christian, & Vanderburg  (2024), [ApJ 972, 161](https://iopscience.iop.org/article/10.3847/1538-4357/ad5f2b) 
* Rice, Gerbig, & Vanderburg (2024), [AJ 167, 126](https://iopscience.iop.org/article/10.3847/1538-3881/ad1bed)
* Rice, Wang, Gerbig, et al. (2023), [AJ 165, 65](https://iopscience.iop.org/article/10.3847/1538-3881/aca88e)

<span style="color:#800020">**Latent Heat in Protoplanetary Disks**</span>
* Gerbig & Laughlin (2022), [ApJ 930, 68](https://iopscience.iop.org/article/10.3847/1538-4357/ac6500) 

<span style="color:#800020">**White Papers**</span>
* Levine, Gerbig, et al.  (2024), [BAAS 56, 1](https://baas.aas.org/pub/2024i004/release/1) 
* Asali, Gerbig, et al.  (2022), [BAAS 54, 1](https://baas.aas.org/pub/2022i091/release/1) 





<!--


{% assign publications_posts = site.publications | sort: 'date' | reverse | paginate: 8 %}

{% for post in publications_posts %}
<div class="post-content">
{% if post.pdflink %}
      <h4 class="post-title">{{post.title}}<a href="{{ post.pdflink }}"><i class="fa fa-link"></i></a></h4>
    {% else %}
      <h4 class="post-title">{{post.title}}</h4>
    {% endif %}
    <p>{{ post.authors | strip_html }},  &nbsp;&nbsp; {{ post.journal | strip_html }}, &nbsp;&nbsp;  {{post.date | date: '%Y'}}</p>
</div>
{% endfor %}

{% include pagination.html collection=site.publications%}








{% assign publications_posts = site.publications | sort: 'date' | reverse | paginate: 8 %}

{% for post in publications_posts %}
<article class="post">
  {% if post.img %}
    <a class="post-thumbnail" style="background-image: url({{"/assets/img/" | prepend: site.baseurl | append : post.img}})" href="{{post.url | prepend: site.baseurl}}"></a>
  {% else %}
  {% endif %}
  <div class="post-content">
    <h2 class="post-title"><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h2>
    {% if post.pdflink %}
      <p>{{ post.authors | strip_html }},  &nbsp;&nbsp; {{ post.journal | strip_html }}, &nbsp;&nbsp;  {{post.date | date: '%Y'}}, &nbsp;&nbsp; <a href="{{ post.pdflink }}"><i class="fa fa-link"></i></a></p>
    {% else %}
      <p>{{ post.authors | strip_html }},  &nbsp;&nbsp; {{ post.journal | strip_html }}, &nbsp;&nbsp;  {{post.date | date: '%Y'}}</p>
    {% endif %}

  </div>
</article>
{% endfor %}

{% include pagination.html collection=site.publications%}

-->


