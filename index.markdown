---

---

## Posts

{% for post in site.posts %}
### _{{ post.date }}:_ <a href="{{ post.url }}">{{ post.title }}</a>
<blockquote>{{ post.excerpt }}</blockquote>
{% endfor %}
