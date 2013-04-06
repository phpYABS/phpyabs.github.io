---
layout: page
title: phpYABS
tagline: Manage your books easily
---
{% include JB/setup %}

<p>Welcome to phpYABS's web site!</p>

## Posts

{% for post in site.posts %}
* {{ post.date | date_to_string }} [{{ post.title }}]({{ BASE_PATH }}{{ post.url }})
{% endfor %}
