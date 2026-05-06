---
title: News
nav:
  order: 5
---

# News

{% assign sorted_posts = site.posts | sort: "date" | reverse %}

{% for post in sorted_posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---

{% endfor %}
