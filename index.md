---
layout: default
---


# Mor
Hello There

## This is the start of our website

> This is a blockquote following a header.
> When something is important enough, you do it even if the odds are not in your favor.


[Team Bonding Workshop leaflet]({{ site.url | append: site.baseurl}}/assets/pdfs/ws_leaflet.pdf) 



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl | append:  post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



