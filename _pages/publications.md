---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For a full list of my publications please visit my [Google Scholar profile](https://scholar.google.com/citations?user=MmJ5U88AAAAJ).

## Selected Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
