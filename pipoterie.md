---
layout: page
permalink: /pipoterie/
title: dupipo
description: categorie de test.
---

<ul class="post-list">
{% for project in site.pipo reversed %}
    <li>
        <h2><a class="poem-title" href="{{ poem.url | prepend: site.baseurl }}">{{ project.title }}</a></h2>
        <p class="post-meta">{{ project.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>




* pi
* po
	* pipo
	* encore

	
	