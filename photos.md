---
layout: default
title: Photos
---

{% for photos in site.photos %}


<a href="{{ photos.url | prepend: site.baseurl }}">
        <h2>{{ photos.title }}</h2>
</a>

<p class="post-excerpt">{{ photos.description | truncate: 160 }}</p>

{% endfor %}      
