---

---

## Posts

{% for post in site.posts %}
### <a href="{{ post.url }}">{{ post.title }}</a>
_{{ post.date | date_to_long_string: "ordinal" }}_
<blockquote>{{ post.excerpt }}</blockquote>
{% endif %}
