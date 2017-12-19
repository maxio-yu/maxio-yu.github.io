---
layout: default
---
# Welcome to Max's Blog

### it's ugly but it's kind-hearted

{% for post in site.posts %}
- [{{post.title}}]({{site.url}}/{{post.url}})
{% endfor %}
