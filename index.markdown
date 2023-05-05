---
layout: home
---

# IT Blog Title

- [**About**](/about)
- [**記事一覧**](/)
- [**RSSフィードを購読する**]({{ site.baseurl }}/feed.xml)

## 記事一覧
{% for post in site.posts %}
- {{ post.date | date: "%Y年%m月%d日" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
