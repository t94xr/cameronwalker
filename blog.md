---
Title: "Blog"
permalink: "blog/"
---
<h2>Blog</h2>
<section class="posts">
<ul>
{% for post in site.posts %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a> - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%-d %b %Y" }}</time></li>
{% endfor %}
</ul>
</section>
