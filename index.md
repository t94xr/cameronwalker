---
layout: default
title: Home
desc: ''
sitemap:
  priority: .8

---

<p>With extensive experience in IT, I've advanced my skills as a computer technician and tech professional.
My expertise spans system building, installation, networking, and providing end-user support across various hardware and software 
platforms.</p>

<p>I have developed a deep knowledge of technology, and my capabilities are widely recognized by peers within the industry.</p>

## me online

- [tech blog](//t94xr.github.io/) - *place for my more techy posts...*
- [server](//server.cameronwalker.nz/) - my personal home server.
- [myhomepage.nz](//myhomepage.nz/) - this is a homepage for anyone to use.
- *socials;*
  - [youtube @t94xr](//youtube.com/@t94xr)
  - [kick/t94xr](//kick.com/t94xr)
  - [rumble/t94xr](//rumble.com/user/cameronwalker)
  - [geoguesser](//geoguessr.com/user/65bb1dfae4581532d19166f0)
  - [reddit/t94xr](//www.reddit.com/user/t94xr/)

## [blog](/blog/)

<ul class="features">
{% for post in site.posts  %}
    <li><a href="{{ post.url }}">{{ post.title }}</a><span class="date">{{ post.date | date: "%b %Y"  }}</span></li>
{% endfor %}
</ul>

<hr>

<div class="center">
<a href="/tag/" title="View Posts by Tag" style="font-size:8pt;">View Posts organized by Tags</a>
</div>
