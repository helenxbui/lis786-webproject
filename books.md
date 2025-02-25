---
title: Books
layout: page
permalink: /books
image_url: https://i.imgur.com/x0qyuBl.png
image_alt: Alt text goes here
my_variable: This is a placeholder text that stands for a variable 
---
Explore select print titles! These print resources were chosen and evaluated for the purpose of expanding the study, research, and creation of manga.

{% include page-image.html %}

{{ page.my_variable }}

{% for study in site.studies %}
{% if study.category == 'books' %}
<h3>{{ study.title }}</h3>
<p><img src="{{ study.category }}" alt="alt text..." /></p>
<p>{{ study.content }}</p>
<p>Category: {{ study.category }}</p>
{% endif %}
{% endfor %}