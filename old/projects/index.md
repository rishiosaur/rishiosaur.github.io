---
layout: otherpage
title: Projects
---

# Projects
{: data-aos="zoom-in" .ph5-ns}
Some of the things that I've done throughout my time programming.
{: data-aos="zoom-in" .ph5-ns}

<section class="cf w-100 pa2-ns">
  {% for project in site.projects %}
  {% if project.coming %}
  <article class="fr w-100 w-50-m  w-25-ns pa2-ns" data-aos="fade-right">
  {% else %}
  <article class="fr w-100 w-50-m  w-25-ns pa2-ns pointer" data-aos="fade-right">
  {% endif %}
  {% unless project.coming %}
  <a href="{{ project.url }}" class="ph2 ph0-ns pb3 link db dim">
  {% endunless %}
    {% if project.coming %}
    <div class="aspect-ratio aspect-ratio--1x1" style="opacity: .25;">
      <img style="background-image:url(../{{project.logo}});" 
      class="db bg-center cover aspect-ratio--object" />
    </div>
    {% else %}
    <div class="aspect-ratio aspect-ratio--1x1 grow" >
      <img style="background-image:url({{project.logo}});" 
      class="db bg-center cover aspect-ratio--object" />
    </div>
    {% endif %}
    {% if project.coming %}
      <h3 class="f5 f4-ns mb0 black-60 border-down dib" data-aos="fade-left" style="--theme:#cacaca">{{ project.title }}</h3>
        <h3 class="f6 f5 fw4 mt2 black-60" data-aos="fade-right">Coming Soon.</h3>
    {% else %}
      <h3 class="f5 f4-ns mb0 black-90 border-down dib" data-aos="fade-left" style="--theme:{{project.theme}}">{{ project.title }}</h3>
      {% if project.description-home %}
        <h3 class="f6 f5 fw4 mt2 black-60" data-aos="fade-right">{{ project.description-home }}</h3>
      {% else %}
        <h3 class="f6 f5 fw4 mt2 black-60" data-aos="fade-right">{{project.description}}</h3>
      {% endif %}
    {% endif %}
    {% unless project.coming %}
    </a>
    {% endunless %}
  </article>
  
  {% endfor %}
</section>