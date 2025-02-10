---

---

## Posts

{% for post in site.posts %}
  ### <a href="{{ post.url }}">{{ post.title }}</a>
  <blockquote>{{ post.excerpt }}</blockquote>

{% endfor %}
