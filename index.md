---
layout: drors-posts-layouts
images:
  - path: /assets/projects-images/bidet1.jpeg
    column: 1
    text: Some text 1
  - path: /assets/projects-images/bidet2.jpeg
    column: 2
    text: Some text 2
---

# קצת עקום 
## פרויקטים
{: #drors-projects }

<ul>
  {% for image in page.images %}
    <li class="col-{{ image.column }}" style="background-image: url({{ image.path }})">
      <p>{{ image.text }}</p>
    </li>
  {% endfor %}
</ul>

## קצת קוד לא יזיק
{: #drors-code }

<ul>
  {% for post2 in site.posts %}
   {% if post2.category == "drors-code" %}
    <li>
      <a href="{{site.baseurl | append:  post2.url }}">{{ post2.title }}</a>
    </li>
   {% endif %}
  {% endfor %}
</ul>
