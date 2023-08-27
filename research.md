---
layout: main
title: Research
permalink: /research/
---

My research is, in the broadest sense, concerned with better understanding the formation of planets and planetary systems. The ever-increasing body of rich observational constraints from exoplanet astronomy, combined with concrete findings from our own Solar System, provide the boundary conditions for many multifacetted astrophysical problems.



{% assign research_posts = site.research | sort: 'date' | reverse | paginate: 8 %}

{% for post in research_posts %}
<article class="post">
  {% if post.img %}
    <a class="post-thumbnail" style="background-image: url({{"/assets/img/" | prepend: site.baseurl | append : post.img}})" href="{{post.url | prepend: site.baseurl}}"></a>
  {% else %}
  {% endif %}
  <div class="post-content">
    <h2 class="post-title"><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h2>
    <p>{{ post.content | strip_html | truncatewords: 15 }}</p>
    <span class="post-date">{{post.date | date: '%Y, %b %d'}}&nbsp;&nbsp;&nbsp;—&nbsp;</span>
    <span class="post-words">{% capture words %}{{ post.content | number_of_words }}{% endcapture %}{% unless words contains "-" %}{{ words | plus: 250 | divided_by: 250 | append: " minute read" }}{% endunless %}</span>
  </div>
</article>
{% endfor %}

{% include pagination.html collection=site.research%}

