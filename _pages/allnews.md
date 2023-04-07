---
title: "News"
layout: textlay
excerpt: "Allan Lab at Leiden University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}

<a class="twitter-timeline" href="https://twitter.com/CVAMO_UGent?ref_src=twsrc%5Etfw">Tweets by CVAMO_UGent</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
