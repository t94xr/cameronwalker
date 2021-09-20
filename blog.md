---
Title: "Blog"
permalink: "blog/"
---

<section class="posts">
<ul>
{% for post in site.posts limit:3 %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a> - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%m-%d-%Y" }}</time></li>
{% endfor %}
</ul>
</section>
