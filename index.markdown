---
layout: home
---

IT Blog Title
[About]({{ site.url }}/about)

{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>{{ post.date | date_to_string }}</small>
  </li>
{% endfor %}
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date: "%d %b %Y" }} - {{ post.title }}</a>
  </li>
{% endfor %}
</ul>

