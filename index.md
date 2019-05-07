---
layout: default
title: Rishi Kothari, Developer
---

## Hey there!
{: data-aos="zoom-in"}
I'm Rishi Kothari, a 13 year old developer and student living and working out of Toronto, Canada.
{: data-aos="fade-left"}

### A bit about me.
{: data-aos="zoom-in"}
There really isn't too much to learn about me. I live with my parents, am studying in the IB Program at Turner Fenton Secondary, and love programming.
{: data-aos="fade-left"}

I'm open for internships right now, wherever in the world you may be.
{: data-aos="fade-left"}

{::comment}
### Contact?
You can visit my contact page [here](/contact).

### FAQ
If you have any trivial questions, have them answered here!

#### You're pretty young. Why are you programming?
*TL;DR:* Because it's fun.

I got into programming when I was around 8, and I fell in love with it. Solving problems has always been a **strength** of mine, 
{:/comment}
### Stats
{: data-aos="fade-in"}
<article class="nr7-l" data-name="slab-stat-large">
  <div class="cf">
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-in">
      <dd class="f6 fw4 ml0">Birthday</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">Oct. 4, 2005</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-up">
      <dd class="f6 fw4 ml0">Programming for</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">~5 years</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="zoom-in">
      <dd class="f6 fw4 ml0">Location</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">Toronto</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-in">
      <dd class="f6 fw4 ml0">Favorite Dog</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">All of Them</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-in">
      <dd class="f6 fw4 ml0">Favorite Language</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">Elm</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="zoom-out">
      <dd class="f6 fw4 ml0">Hello?</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">Hi.</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="fade-left">
      <dd class="f6 fw4 ml0">High School</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">TFSS</dd>
    </dl>
    <dl class="db dib-l w-auto-l lh-title mr6-l" data-aos="zoom-in">
      <dd class="f6 fw4 ml0">Hackathons</dd>
      <dd class="f2 f-subheadline-l fw6 ml0">4</dd>
    </dl>
  </div>
</article>

## Projects
{: data-aos="zoom-in"}
<section class="cf w-100 pa2-ns">
  {% for project in site.projects %}
  <article class="fl w-100 w-50-m  w-25-ns pa2-ns pointer" data-aos="zoom-in">
  <a href="{{ project.url }}" class="ph2 ph0-ns pb3 link db dim">
    <div class="aspect-ratio aspect-ratio--1x1 grow">
      <img style="background-image:url({{project.logo}});" 
      class="db bg-center cover aspect-ratio--object" />
    </div>
    
      <h3 class="f5 f4-ns mb0 black-90">{{ project.title }}</h3>
      <h3 class="f6 f5 fw4 mt2 black-60">{{ project.description }}</h3>
    </a>
  </article>
  
  {% endfor %}
</section>