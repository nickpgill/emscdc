---
id: 4
title: News
date: 2014-03-11T19:18:39+00:00
author: nickgill
layout: page
---

The latest news from the EMS-CDC...

---
<table width="100%" border="3">
  <tr>
    <td align="center"> 
<b>18/11/2022. This site is now out of date. The new EMS-CDC site can be found <a href = "https://euromathsoc.org/committee-developing-countries">here</a>.</b>
</td></tr></table>


{% for post in site.posts %}

[{{ post.title }}]({{ site.baseurl }}/{{ post.url }})

Posted on {{ post.date | date: "%b %-d, %Y" }}

---

{% endfor %}

subscribe via [rss]({{ site.baseurl }}/feed.xml)
