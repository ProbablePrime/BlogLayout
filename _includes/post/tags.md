<ul class="tag-list">
	{% for tag in page.tags %}
	<li class="tag">
		<a class="link" href="/tag/{{ tag }}">{{ tag }}</a>
	</li>
	{% endfor %}
</ul>
