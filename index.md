---
id: 4
title: News
date: 2014-03-11T19:18:39+00:00
author: nickgill
layout: page
---

The latest new from the EMS-CDC...

{% for post in site.posts %}

[{{ post.title }}]({{ post.url }})

Posted on {{ post.date | date: "%b %-d, %Y" }}

---

{% endfor %}

subscribe via [rss]({{ site.baseurl }}/feed.xml)
