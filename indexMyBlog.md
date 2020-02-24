---
layout: default-heb
---

# הפוסטים של דרור
{: #drors-posts }

<ul>
  {% for post in site.posts %}
   {% if post.category == "drors-posts" %}
    <li>
      <a href="{{site.baseurl | append:  post.url }}">{{ post.title }}</a>
    </li>
   {% endif %}
  {% endfor %}
</ul>
