---
layout: page
permalink: /materials/
title: Materials

---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}


# Outlines 

<div>
<ul>
{% for page in site.pages %}
{% if page.categories contains 'outlines' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
</div>

# Visual Aids 

<div>
<ul>
{% for page in site.pages %}
{% if page.categories contains 'visuals' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
</div>

# Review Problems 

<div>
<ul>
{% for page in site.pages %}
{% if page.categories contains 'problems' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
</div>

# Practice Exam Questions

<div>
<ul>
{% for page in site.pages %}
{% if page.categories contains 'exams' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
</div>


