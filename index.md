---
layout: drors-posts-layouts
---

# קצת עקום 
## פרויקטים
{: #drors-projects }

<ul>  
    <li>      
      ![image Bidet1](/_images/bidet1.jpeg)
    </li>     
    <li>      
      ![image Bidet2](/_images/bidet2.jpeg)
    </li>     
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
