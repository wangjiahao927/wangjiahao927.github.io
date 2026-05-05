---
layout: home
title: "Ван Цзяхао"
---

## Добро пожаловать

Привет! Я Ван Цзяхао, студент компьютерной специальности.

## Мои заметки

{% for post in site.posts %}
- **{{ post.date | date: "%Y-%m-%d" }}** – [{{ post.title }}]({{ post.url }})
{% endfor %}
