---
layout: default-heb
---


# החזון שלנו
{: #group-idea }

<ul>
  {% for post in site.posts %}
   {% if post.category == "group-idea" %}
    <li>
      <a href="{{site.baseurl | append:  post.url }}">{{ post.title }}</a>
    </li>
   {% endif %}
  {% endfor %}
</ul>


# סדנת 'התנעת הקבוצה'
{: #tb-ws }
Six sessions, 90 minutes per session, hopfully once a week.

## Session 1: Hello World
Getting to know the Group languege, The foramt (Setting) & the facilitators.

## Session 2: Lunch
Lets see what happend on lunch time, What are we talking about?

## Session 3: Bug Or Feature
How do talk to each other.

## Session 4: Code Review
Communication, Let's review that.

## Session 5: Lost In Translation
English Jerusalem lite talk, why are we do that??

## Session 6: Save & Exit
What happens next, define next sprint.

[Team Bonding Workshop leaflet]({{ site.url | append: site.baseurl}}/assets/pdfs/ws_leaflet.pdf)


# Pilot
{: #pilot }
<ul>
  {% for post in site.posts %}
   {% if post.category == "pilot" %}
    <li>
      <a href="{{site.baseurl | append:  post.url }}">{{ post.title }}</a>
    </li>
   {% endif %}
  {% endfor %}
</ul>



# About US
{: #about-us }
### Mor Aram
 I'm a social worker, and trained group facilitator.
 and I like to communicate, more than all in Hebrew, my language.
 Can we do that? Thanks
[Just click here](./mor_in_hebrew.md)     
 ![Octocat](assets/images/mor.jpg)

### Dror Arm
Hello! I have a confession to make, It's true After six years serving the military, IDF, I arrived to the civil high tech and they told me..
Here we don't write emails in Hebrew, they even laugh about people who wrote in Hebrew.  It's true, it's weird to receive email in Hebrew when you work.
But I hate it! I've always did! so now in my website I can just do what I want!
Here is me [in Hebrew](./dror_in_hebrew.md)

 ![Octocat](assets/images/dror.jpg)
