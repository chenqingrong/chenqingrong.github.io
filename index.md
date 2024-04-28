---
layout: page
title: "Home"
class: home
---

# Hi, I'm Leo (Qingrong) Chen

<div class="columns" markdown="1">

<div class="intro" markdown="1">
I'm a Member of Technical Stuff in [OpenAI](https://openai.com/), building the research platform for large lanague models.

I received my master degree from the CS department at the [University of Illinois Urbana-Champaign](https://cs.illinois.edu/), where I worked with [Tianyin Xu](https://tianyin.github.io/), [Josep Torrellas](https://iacoma.cs.uiuc.edu/josep/torrellas.html) and [Nikita Borisov](http://hatswitch.org/~nikita/).

I received my undergraduate degree in computer science from [Shanghai Jiao Tong University](https://en.sjtu.edu.cn), where I worked with [Haojin
Zhu](https://nsec.sjtu.edu.cn/~hjzhu/).

I am excited about learning new technology, making new friends and getting new experience:)
</div>

<div class="me" markdown="1">
<picture>
  <source srcset='/images/avatar.jpg' type='image/webp' />
  <img
    src='/images/avatar.jpg'
    alt='Leo Chen'
  >
</picture>

{:.no-list}
* chenqr1995 at gmail.com
</div>
</div>

## Recent Blogs

<div>
{% for post in site.posts %}
    <div class="post-block">
      <h3>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      <span class="post-meta" title="{{ post.date | date: "%b %-d Y" }}">{{ post.date | date: "%b %-d" }} <span class="meta-year">{{ currentdate }}</span></span>
      {% if post.description %}<p class="post-subtitle">{{ post.description }}</p>{% endif %}
    </div>
  {% endfor %}
</div>

<a href="{{ "/blog/" | relative_url }}" class="button">
  <i class="fas fa-chevron-circle-right"></i>
  Show More blogs
</a>
