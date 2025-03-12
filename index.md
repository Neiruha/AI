---
layout: default
title: NEIRUHA ~ AI Примеры и тесты
---

# Добро пожаловать

Вы найдете здесь тексты, сгенерированные различными AI моделями, в рамках курса.

## Тексты, сгенерированные AI:

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
