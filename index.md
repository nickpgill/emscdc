---
id: 4
title: News
date: 2014-03-11T19:18:39+00:00
author: nickgill
layout: page
---

The latest news from the EMS-CDC...

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for post in site.posts %}

[{{ post.title }}]({{ post.url }})

Posted on {{ post.date | date: "%b %-d, %Y" }}

---

{% endfor %}

subscribe via [rss]({{ site.baseurl }}/feed.xml)
