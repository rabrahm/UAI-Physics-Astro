---
title: "UAI Physics+Astro - News"
layout: textlay
excerpt: "Physics + Astro Group at UAI"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
