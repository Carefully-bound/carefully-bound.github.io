---
layout: default
---
<div class="post-header-wrapper">
    <div class="post-header-column">
        <span>
        {% if page.previous %}
            <a href="{{ page.previous.url}}">Previous Post</a>
        {% else %}
            _No Previous Post_
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
            _No Next Post_
        {% endif %}
        </span>
    </div>
</div>

<section>
    {{ content }}
</section>