---
layout: default
permalink: /en/
title: homeless2010's think
---

<article>
<blockquote><p> 
too young too simple sometimes native.
</p></blockquote>
</article>

<p style="margin-top:1.2em;margin-bottom:0;"><b>Blogs</b> | Browse by <a href="/archive#tags">Tags</a></p>
<hr>
<table>
{% for post in site.categories.cn %}
<tr id="blog-table">
<td>{{ post.date | date: "%Y-%m-%d" }}</td>
<td><a class="post-list-item" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></td>
</tr>
{% endfor %}
</table>
<hr>
<p>All posts <a href="/archive">archived</a></p>
