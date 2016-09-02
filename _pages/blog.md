---
layout: blog
title: blog
permalink: "/blog/"
--- 

{% for post in site.posts %}
<div class="roll page-content">
        <header>
                <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
                <h2>
                    <a class="post-link" href="{{ site.github.url }}/{{ post.url }}">{{ post.title }}</a>
                </h2>
        </header>
  {% if post.thumbnail %}
        <article>
            <a href="{{ site.url }}{{ post.url }}">
                <figure>
                    <img src="{{ site.github.url }}/{{ post.thumbnail }}" class="thumb" />
                </figure>
            </a>
  {% endif %}
                <p>{{ post.excerpt }}  <a href="{{ site.github.url }}/{{ post.url }}">Read More</a></p>
        </article>
</div>
{% endfor %}