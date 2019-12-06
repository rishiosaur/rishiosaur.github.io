---
layout: default
title: Rishi Kothari, Developer
---

## Hey there! 👋🌊
{: data-aos="zoom-in"}
I'm <span class="bg-light-yellow">Rishi Kothari</span>, a 13 year old developer and student living and working out of Toronto, Canada.
{: data-aos="fade-left"}

<div data-aos="fade-right" class="aos-init halftone">
<img src="/assets/attachments1/44606624_2484325718260664_2498399909355454464_o.jpg" alt="Me at HtN" title="Me @ HtN"  class="halftone">
</div>

### A bit about me.
{: data-aos="zoom-in" }
There really isn't too much to learn about me. I live with my parents, am studying in the IB Program at Turner Fenton Secondary, and love CS and math.

I publish my papers on <a href="https://observablehq.com/@rishiosaur" style="--theme:orange" class="hover-white no-underline black border-up">Observable</a>, I use <a href="https://music.apple.com/profile/itsrishikothari" style="--theme:red" class="hover-white no-underline black border-up">Apple Music</a>, you can find my resumé on <a href="https://www.notion.so/rishikothari/Resum-1f30f8797204413c8ef738558aa89f1b" style="--theme:grey" class="hover-white no-underline black border-up">Notion</a>, and I shoot photos on <a href="https://instagram.com/yo.rishi" style="--theme:purple" class="hover-white no-underline black border-up">Instagram</a>.
{: data-aos="fade-left"}


{% if page.internships %}
I'm <span class="bg-light-green">open for internships right now</span>, wherever in the world you may be.
{% endif %}


## Some things I've done...
<section class="cf w-100 pa2-ns">
  {% for project in site.projects %}
  {% if project.coming %}
  <article class=" fr w-100 w-50-m  w-50-ns pa2-ns " data-aos="zoom-in">
  {% else %}
  <article class=" fr w-100 w-50-m  w-50-ns pa2-ns pointer" data-aos="zoom-in">
  {% endif %}
  {% unless project.coming %}
  <a href="{{ project.url }}" class="ph2 ph0-ns pb3 link db dim">
  {% endunless %}
    {% if project.coming %}
    {% if project.logo %}
      <div class="aspect-ratio aspect-ratio--1x1" style="opacity: .25;">
        <img style="background-image:url({{project.logo}});" 
        class="db bg-center cover aspect-ratio--object" />
      </div>
    {% else %}
    <div class="aspect-ratio aspect-ratio--1x1 " style="opacity: .25;">
        <img style="background-color: white" 
        class="db bg-center cover aspect-ratio--object" />
      </div>
    {% endif %}
    {% else %}
    <div class=" aspect-ratio aspect-ratio--1x1 grow" >
      <img style="background-image:url({{project.logo}});" 
      class="db bg-center cover aspect-ratio--object" />
    </div>
    {% endif %}
    {% if project.coming %}
      <h3 class="f5 f4-ns mb0 black-60 border-down dib" data-aos="zoom-in" style="--theme:#cacaca">{{ project.title }}</h3>
        <h3 class="f6 f5 fw4 mt2 black-60" data-aos="fade-right">Coming Soon.</h3>
    {% else %}
      <h3 class="f5 f4-ns mb0 black-90 border-down dib" data-aos="zoom-in" style="--theme:{{project.theme}}">{{ project.title }}</h3>
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

### Stats
{: data-aos="fade-in"}
<article class="nr5-l" data-name="slab-stat-large">
  <div class="cf">
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-up">
      <dd class="f6 fw4 ml0">Programming for</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">~5 <span class="bg-blue white">years</span></dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="zoom-in">
      <dd class="f6 fw4 ml0">Location</dd>
      <dd class="f2 f-subheadline-l fw6 ml0"><span class="red">Tor</span><span class="bg-red white">on</span><span class="red">to</span></dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-in">
      <dd class="f6 fw4 ml0 ">Favorite Language</dd>
      <dd class="f2 f-subheadline-l fw6 ml0 white bg-orange">Rust</dd>
    </dl>
    <a class="link hover-gold pointer black" href="http://turnerfenton.com/"><dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-left">
      <dd class="f6 fw4 ml0">High School</dd>
      <dd class="f2 f-subheadline-l fw6 ml0 hover-gold">TFSS</dd>
    </dl></a>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="zoom-in">
      <dd class="f6 fw4 ml0">Hackathons</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">2</dd>
    </dl>