---
layout: default.liquid

---

## RUST!

{% for post in collections.posts.pages %}
[{{ post.title }}]({{ post.permalink }})
{{post.description}}

{% endfor %}
