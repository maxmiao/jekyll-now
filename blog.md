layout: page
title: Photos!
permalink: /blog/
---
---
Research
---

![_config.yml]({{ site.baseurl }}/images/GH_2017-2.jpg)

![_config.yml]({{ site.baseurl }}/images/GH_2017-3.jpg)

![_config.yml]({{ site.baseurl }}/images/GH_2017.jpg)

---
Places
layout: default
title: Photos
---

![_config.yml]({{ site.baseurl }}/images/SEasia_2015-13.jpg)
{% for photos in site.photos %}

![_config.yml]({{ site.baseurl }}/images/Seattle_2018-20.jpg)

![_config.yml]({{ site.baseurl }}/images/Yellowstone_2016-21 copy.jpg)
<a href="{{ photos.url | prepend: site.baseurl }}">
        <h2>{{ photos.title }}</h2>
</a>

![_config.yml]({{ site.baseurl }}/images/lost_coast2016-10 copy.jpg)
<p class="post-excerpt">{{ photos.description | truncate: 160 }}</p>

![_config.yml]({{ site.baseurl }}/images/fall_2018-18 copy.jpg)
{% endfor %}      
