---
layout: default
---

<section class="posts">
<ul>
{% for post in site.posts %}
<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><time style="font-feature-settings:tnum;" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%d %m %y" }}</time></li>
{% endfor %}
</ul>
</section>


