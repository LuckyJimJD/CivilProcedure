---
layout: page
permalink: /materials/
title: Materials

---

# Cases

<div>
{% for page in site.pages %}
{% if page.categories contains 'cases' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</div>

# Readings

<div>
{% for page in site.pages %}
{% if page.categories contains 'readings' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</div>



# Outlines 

<div>
{% for page in site.pages %}
{% if page.categories contains 'outlines' %}
<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
{% endif %}
{% endfor %}
</div>

# Visual Aids 

<div>
{% for page in site.pages %}
{% if page.categories contains 'visuals' %}

<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>

{% endif %}
{% endfor %}
</div>

# Review Problems 

<div>
{% for page in site.pages %}
{% if page.categories contains 'problems' %}

<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>

{% endif %}
{% endfor %}
</div>


# Practice Exam Questions

<div>
{% for page in site.pages %}
{% if page.categories contains 'exams' %}

<li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>

{% endif %}
{% endfor %}
</div>

