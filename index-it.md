---
permalink: "/indice.html"
layout: home
header:
  image: "/assets/img/home-header.jpg"
tagline: 'Scrivi una fantastica descrizione del tuo nuovo sito qui. Puoi modificare
  questa descritione nel file index-it.md. Apparira'' anche nel head meta (per indicizzazione
  SEO) e nella descrizione del sito nel feed.xml.

'
excerpt: 'Scrivi una fantastica descrizione del tuo nuovo sito qui. Puoi modificare
  questa descritione nel file index-it.md. Apparira'' anche nel head meta (per indicizzazione
  SEO) e nella descrizione del sito nel feed.xml.

'
repository:
  is_project_page: true
  show_downloads: true
  repository_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog
  zip_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.zip
  tar_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.tar.gz
ref: home
lang: it
---

Simple Blog Theme e' un tema pulito e responsive per Jekyll, con alcune funzionalitá social. Si ispira al tema Cayman Blog.

Questo tema ha tutto quello di cui avete bisogno per iniziare con un blog in Jekyll con nessuno sforzo: pagine, post, bottoni social, commenti. É responsive quindi funziona su mobile.

Dai un'occhiata alla pagina Gitlab per maggiori informazioni.

Trovi questo testo nel file `indice.md`, puoi modificarlo, o rimuoverlo completamente, a seconda delle tue necessitá.

<h1>Articoli Recenti</h1>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" max_posts=3 max_post_tags=3 %}

---

<h1>Ultimi Progetti</h1>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="projects" max_posts=3 max_post_tags=3 %}
