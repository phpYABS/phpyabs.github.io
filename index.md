---
layout: page
title: phpYABS
tagline: Manage your books easily
---
{% include JB/setup %}

<p>Welcome to phpYABS's web site!</p>
<p>This is my very first open source project (early 2000s), I was very young and inexperienced.
Sometimes i like to improve this as a refactoring exercise. Code quality is still poor.</p>

## Posts

{% for post in site.posts %}
* {{ post.date | date_to_string }} [{{ post.title }}]({{ BASE_PATH }}{{ post.url }})
{% endfor %}
