---
layout: default
---

<div class="archive fixed-width-container">
	<h1 class="section-heading">Archives</h1>

	{% for post in site.posts %}
	<div class="">
	    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
	    <div class="date-author">
	        <span class="author">{{ post.author }}</span> &middot;
	        <span class="post-meta">{{ post.date | date_to_long_string }}</span>
	    </div>
	    <p>{{ post.excerpt }}</p>
	</div>
	{% endfor %}
</div>