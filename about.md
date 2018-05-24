---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## About the BoneZone

About pages? What is there to learn about this site?

I plan on using this site to post content directly related to my gaming, programming, and various other hobbies.
There's nothing more than that you need to know, but if you're interested feel free to stick around.

</div>
