---
Title: "Stuff"
permalink: "stuff/"
---
<h2>Stuff</h2>
<section class="posts">
<ul>
{% for post in site.posts.stuff %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a> - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%m-%d-%Y" }}</time></li>
{% endfor %}
</ul>
</section>
