---
layout: drors-posts-layouts
---

# הפוסטים של דרור
## מה יש לי להגיד
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

## קצת קוד לא יזיק
{: #drors-code-posts }

<ul>
  {% for post in site.posts %}
   {% if post.category == "drors-code-posts" %}
    <li>
      <a href="{{site.baseurl | append:  post.url }}">{{ post.title }}</a>
    </li>
   {% endif %}
  {% endfor %}
</ul>


