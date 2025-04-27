---
title: Resources
layout: page
permalink: /resources
---
Check out other resources can be used to look up information related to the topic of manga.

{{ page.my_variable }}

{% for study in site.studies %}
{% if study.category == 'resources' %}
<h3>{{ study.title }}</h3>
<p><img src="{{ study.category }}" alt="" /></p>
<p>{{ study.content }}</p>
<p>Category: {{ study.category }}</p>
{% endif %}
{% endfor %}