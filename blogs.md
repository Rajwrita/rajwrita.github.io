---
layout: blog
title: Posts
permalink: /posts
---

<!-- Write the Post page here -->
<div class="main">
<div class="post-wrap archive">
    <h3>2020</h3>
    {% for post in site.posts %}
    <article class="archive-item">
        <a class="archive-item-link" href="{{ post.url }}" target="_blank" rel="noopener noreferrer">{{ post.title }}</a>
    </article>
    {% endfor %}
    <article class="archive-item">
        <a class="archive-item-link" href="{{site.url}}/assets/BatchNorm.pdf" target="_blank" rel="noopener noreferrer">Back Propagation in Batch Normalization</a>
    </article>
    
</div>
</div>
