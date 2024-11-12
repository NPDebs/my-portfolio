---
layout: default
title: "Blog"
permalink: /blog/
---

<section class="blog">
    <h2 class="section_title">Blog</h2>
    <div class="blog_posts">
        {% for post in site.posts %}
            <article class="blog_post">
                <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
                <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
                <p>{{ post.excerpt }}</p>
                <a href="{{ post.url | relative_url }}" class="read-more">Read More</a>
            </article>
        {% endfor %}
    </div>
</section>
