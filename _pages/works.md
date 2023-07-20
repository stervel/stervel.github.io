---
layout: default
---

<section class="posts">
{% assign sorted = "w-cfp16.png" %}
<div class="work-gallery">
    {% for name in sorted %}
    <div class="boxen">
        <a href="{{ site.imagesurl }}{{ name }}">
            <img src="{{ site.imagesurl }}{{ name }}" alt="{{ name }}" class="werke" />
        </a>
    </div>
    {% endfor %}
</div>
</section>



