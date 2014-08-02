---
layout: page
title: blog.RyanLucht
tagline: only marginally cool.
---
{% include JB/setup %}

Head to [RyanLucht.com](http://ryanlucht.com) for my main website.

## Posts
<ul class="posts">
    {% for post in site.posts limit 4 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
        {{ post.content | strip_html | truncatewords:75}}<br>
            <a href="{{ post.url }}">Read more...</a><br><br>
    {% endfor %}
</ul>

## More Ryan

Don’t forget that you can find me elsewhere on the web:
    
    twitter : @ryanlucht
    facebook: ryan.lucht
    instagram: jazzfreak11



