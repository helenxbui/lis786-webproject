---
title: Databases
layout: page
permalink: /databases
---
Search further! These databases can be used to look up information related to the topic of manga.

{{ page.my_variable }}

{% for study in site.studies %}
{% if study.category == 'databases' %}
<h3>{{ study.title }}</h3>
<p><img src="{{ study.category }}" alt="" /></p>
<p>{{ study.content }}</p>
<p>Category: {{ study.category }}</p>
{% endif %}
{% endfor %}