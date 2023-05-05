---
layout: home
---

{% for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: "%Y年%m月%d日" }}</span>
    <h3>
      <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
    </h3>
  </li>
{% endfor %}
