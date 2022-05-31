---
title: Series
tags: [content_types]
keywords: series, connected articles, tutorials, hello world
last_updated: July 3, 2016
summary: "You can automatically link together topics belonging to the same series. This helps users know the context within a particular process."
sidebar: home_sidebar
permalink: general_anunciar_propiedad.html
folder: mydoc
---

## Using series for pages

You create a series by looking for all pages within a tag namespace that contain certain frontmatter. Here's a <a href="mydoc_seriesdemo1.html">demo</a>.

## Create the series button

First create an include that contains your series button:




Change "ACME series" to the name of your series.

Save this in your \_includes/custom folder as something like series\_acme.html.

{% include tip.html content="With pages, there isn't a universal namespace created from tags or categories like there is with Jekyll posts. As a result, you have to loop through all pages. If you have a lot of pages in your site (e.g., 1,000+), then this looping will create a slow build time. If this is the case, you will need to rethink the approach to looping here." %}

##  Create the "next" include




{% include links.html %}
