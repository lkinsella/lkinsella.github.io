---
layout: page
title: P.E.B.K.A.C
---
{% include JB/setup %}

Hi I'm Lloyd, welcome to my blog. I've been a software developer, professional or otherwise, for more than 25 years and currently
develop principally for the web, cloud and Windows.

I'm an inconsistent blogger but if you've found yourself here then hopefully something of interest drew you.
Below you'll find a list of available blog posts. You can also see category and tag lists from the menu at the top.

This blog is still a work-in-progress, I've chosen simplicity and clarity over a more complicated theme.

---
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

