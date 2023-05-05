---
layout: home
---

# 記事一覧

{% for post in site.posts %}
- [{{ post.date | date: "%Y年%m月%d日" }}]({{ post.url }}) - [{{ post.title }}]({{ post.url }})
{% endfor %}

[RSSフィードを購読する](/feed.xml)
