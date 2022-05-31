---
title: "Inicio documentacion y ayuda de busquemos.casa"
keywords: inicio 
tags: [inicio_ayuda]
sidebar: home_sidebar
permalink: index.html
last_updated: Jan 20, 2020
toc: false
summary: Encontrar ayuda en este documento es facil y rapido. Las siguientes notas pueden ayudarle a aclarar dudas sobre el funcionamiento de la pagina y la informacion que encontrara.
---

## Bienvenido

Follow these instructions to build the theme.




## Noticias 

For blog posts, create your markdown files in the \_posts folder following the sample formats. Post file names always begin with the date (YYYY-MM-DD-title).

The news/news.html file displays the posts, and the news_archive.html file shows a yearly history of posts. In documentation, you might use the news to highlight product features outside of your documentation, or to provide release notes and other updates.

See [Posts][mydoc_posts] for more information.


## Comentarios y consultas

The theme integrates [Commento.io](https://commento.io/) for comments below pages and posts. (This commenting service doesn't inject controversial tracking ads like Disqus does.) You will need to Commento.io account + plan ($5/month) to authorize Commento with your domain (no other configuration should be required). If you don't want comments, in the \_config.yml file, change the `comments: true` properties (under `defaults`) to `comments: false` in every instance. Then in the commento.html include file (inside \_includes), the `{% raw %}{% unless page.comments == false %} ... {% endunless %}{% endraw %}` logic will not insert the Commentio form.



## Menu de Navegacion

The top navigation bar's menu items are set through the \_data/topnav.yml file. Use the top navigation bar to provide links for navigating from one product to another, or to navigate to external resources.

For external URLs, use `external_url` in the item property, as shown in the example topnav.yml file. For internal links, use `url` the same was you do in the sidebar data files.

Note that the topnav has two sections: `topnav` and `topnav_dropdowns`. The topnav section contains single links, while the `topnav_dropdowns` section contains dropdown menus. The two sections are independent of each other.


## Busqueda rapida


## Necesita ayuda?

Si no encuentra lo que busca escribanos a ayuda@busquemos.casa y le ayudaremos en lo que necesite.

{% include links.html %}
