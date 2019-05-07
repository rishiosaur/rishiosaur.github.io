---
layout: otherpage
title: Projects
---

# Projects
{: data-aos="zoom-in" .ph5-ns}
Some of the things that I've done throughout my time programming.
{: data-aos="zoom-in" .ph5-ns}

<section class="cf w-100 ph5-ns">
  {% for project in site.projects %}
  <article class="fl w-100 w-50-m  w-25-ns pa2-ns pointer" data-aos="zoom-in">
  <a href="{{ project.url }}" class="ph2 ph0-ns pb3 link db dim">
    <div class="aspect-ratio aspect-ratio--1x1">
      <img style="background-image:url({{project.logo}});" 
      class="db bg-center cover aspect-ratio--object" />
    </div>
    
      <h3 class="f5 f4-ns mb0 black-90">{{ project.title }}</h3>
      <h3 class="f6 f5 fw4 mt2 black-60">{{ project.description }}</h3>
    </a>
  </article>
  
  {% endfor %}
</section>