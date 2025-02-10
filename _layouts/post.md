---
layout: default
---
<div class="row">
    <div class="column">
        {% if page.previous %}
        <span>
            <a href="{{ page.previous}}">Previous Post</a>
        </span>
        {% endif %}
    </div>
    <div class="column">
        <span>
            <a href="{{ site.baseurl }}">Home</a>
        </span>
    </div>
    <div class="column">
        {% if page.next %}
        <span>
            <a href="{{ page.next}}">Next Post</a>
        </span>
        {% endif %}
    </div>
</div>

<section>
    {{ content }}
</section>