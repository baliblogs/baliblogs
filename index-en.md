---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /index.html
header:
  image: /assets/img/home-header.jpg
tagline: > # this means to ignore newlines until "repository:"
  Thoughts of a Common Man surfing the whirlpool of Indian Politics
excerpt: >
  I am Gautam Bali
# repository:
  # is_project_page: true
#   show_downloads: true
#   repository_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog
#   zip_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.zip
#   tar_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.tar.gz
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
