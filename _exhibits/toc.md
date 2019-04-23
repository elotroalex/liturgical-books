---
layout: page
title: "Table of Contents"
editor: John Glasenapp
publish_date: 2018-11-15
permalink: /exhibits/toc/
---

<ul>
	{% for item in site.exhibits %}
		{% unless item.title == "Table of Contents" %}
		<li><a href="{{ site.baseurl }}{{ item.permalink }}">{{ item.title }}</a></li>
		{% endunless %}
	{% endfor %}
</ul>