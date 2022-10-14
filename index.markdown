---
layout: default
---

{% for post in site.posts limit:5 %}

<h4><a href="{{post.url}}" class="title"> {{post.title}}</a></h4>

<div class="text line">
	<div class="post unit">
			{{ post.content }}
	</div>

	<div class="smaller caption unit lastUnit">
			{{post.date | date: "%B %-d, %Y"}} <br/>
	</div>
</div>
{% endfor %}