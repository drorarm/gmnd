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
{: #drors-code }

<ul>
  {% for post2 in site.posts %}
  check -- {{ post2.title }}
   {% if post2.category == "drors-code" %}
    <li>
      <a href="{{site.baseurl | append:  post2.url }}">{{ post2.title }}</a>
    </li>
   {% endif %}
  {% endfor %}
</ul>


