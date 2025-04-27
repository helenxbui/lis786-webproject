---
title: About
layout: page
permalink: /about
---
![Image of manga mural from Unsplash](https://i.imgur.com/mqzUPRH.png)

*Learn what makes manga unique!*

What is manga? It's a stylistic form of comic storytelling that originated in Japan, blending Western and Eastern influences. 
According to Data Bridge Market Research, the manga market represents a dynamic and diverse segment of the global publishing industry, characterized by a rich array of genres and artistic styles. Manga has garnered international popularity, captivating readers of all ages with its compelling narratives, vibrant artwork, and unique storytelling in both print and digital formats. 
The global manga market size is estimated to grow by USD 28.15 billion from 2025-2029, according to Technavio [(Source: Yahoo! Finance)](https://finance.yahoo.com/news/manga-market-grow-usd-28-162800094.html "Yahoo! Finance"). Manga has become a global phenomenon worthy of academic study and research; this research guide will assist you on your manga journey by providing resources such as books, databases, and web resources of interest.

This guide covers:   

- Books
- Databases
- Other Resources

<h2>List of Contents</h2>
 {% for study in site.studies %}
    <!-- DO SOMETHING -->
    <h3>{{ study.title }}</h3>
    <p><img src="{{ study.category }}" alt="alt text..." /></p>
    <p>{{ study.content }}</p>
    <p>Category: {{ study.category }}</p>

 {% endfor %}
