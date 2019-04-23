---
layout: page
title: "Browse..."
editor: John Glasenapp
publish_date: 2018-11-15
permalink: /exhibits/toc/
---


### a multiplicity of practices

<ul>
	{% for item in site.exhibits %}
		{% if item.layout == "exhibit" %}
		<li><a href="{{ site.baseurl }}{{ item.permalink }}">{{ item.title }}</a></li>
		{% endif %}
	{% endfor %}
</ul>

### or learn more

<ul>
	{% for item in site.exhibits %}
		{% if item.layout != "exhibit" and item.title != "Browse..." %}
		<li><a href="{{ site.baseurl }}{{ item.permalink }}">{{ item.title }}</a></li>
		{% endif %}
	{% endfor %}
</ul>