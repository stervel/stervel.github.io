---
layout: page
---

{% for work in site.works reversed %}

<div class="wthumb-container">
    <a href="{{ site.baseurl }}{{ work.permalink }}">
        <img src="{{ site.baseurl }}/assets/img/{{ work.thumb }}" style="width:100%;">
    </a>
</div>
<div>
    <a style="text-decoration:none;" href="{{ site.baseurl }}{{ work.permalink }}">
        <div style="font-weight:600;">
            {{ work.title }} →
        </div>
        <div style="font-size:1rem;">
            {{ work.kala }}
        </div>
    </a>
</div>
{% endfor %}
