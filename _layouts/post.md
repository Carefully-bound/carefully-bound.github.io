---
layout: default
---
<div class="post-header-wrapper">
    <div class="post-header-column">
        <span>
        {% if page.previous %}
            <a href="{{ page.previous.url}}">Previous Post</a>
        {% else %}
            <i>No Previous Post</i>
        {% endif %}
        </span>
    </div>
    <div class="post-header-column">
        <span>
            <a href="{{ site.baseurl }}">Home</a>
        </span>
    </div>
    <div class="post-header-column">
        <span>
        {% if page.next %}
            <a href="{{ page.next.url}}">Next Post</a>
        {% else %}
            <i>No Next Post</i>
        {% endif %}
        </span>
    </div>
</div>

{{ content }}
