---
layout: post
title:  "Another post"
date:   2017-03-13 19:09:48 +0100
tags: 
    - beatles
    - data
---

This is just another post. See how to include data inside your posts:

## Beatles Discography

<ul>
{% for album in site.data.beatles %}
    <li><b>{{ album.Name }}</b> (released on {{ album.Released }})</li>
{% endfor %}
</ul>
<iframe src="https://www.zonerama.com/Embed/Account/40631?color=green&autoplay=false&vertical=false" style="width: 720px; height: 330px;" scrolling="no" frameborder="0" allowTransparency="true"></iframe>
