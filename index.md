---
layout: archive
permalink: /
title: "Latest Posts"
image:
    feature: Eclipse-Danjon-moon-demo_S_Bob-King.jpg
    credit: Hubber  high resolution photo
    creditlink: http://i0.wp.com/www.universetoday.com/wp-content/uploads/2015/09/Eclipse-Danjon-moon-demo_S_Bob-King.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
