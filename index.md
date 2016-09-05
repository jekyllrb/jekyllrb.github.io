---
layout: default
---

{% for node in site.pages %}

<div class="container">
	<div class="cards">
		<a class="card" href="{{node.url}}">
			<span class="card-header" style="background-image: url(http://placeimg.com/400/200/animals);">
				<span class="card-title">
					<h3>{{ node.url | split: '/' | last }}</h3>
				</span>
			</span>
			<span class="card-summary">
				A summary will also be present. Usually two to three brief sentences about the content on the detail page.
			</span>
			<span class="card-meta">
				Published: June 18th, 2015
			</span>
		</a>
	</div>
</div>

{% endfor %}
