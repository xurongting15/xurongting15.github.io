---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
---
{% include base_path %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
  ---
{% endif %}

## You can also find my articles on <a href="https://scholar.google.com/citations?user=xaGzj6IAAAAJ&hl=en">my Google Scholar profile</a>.
{% for post in site.publications reversed %}
  {% include archive-single.html %}
  ---
{% endfor %}
