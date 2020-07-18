---
permalink: "/index.html"
layout: home
header:
  image: "/assets/img/home-header.jpg"
tagline: 'Thoughts of a Common Man surfing the whirlpool of Indian Politics

'
excerpt: 'I am Gautam Bali

'
ref: home
lang: en
---

this is my personal blog where I share my opinion and thougts about ongoing politics and events

<h1>Latest Articles</h1>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" max_posts=3 max_post_tags=3 %}

---

<h1>Latest Projects</h1>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="projects" max_posts=3 max_post_tags=3 %}
