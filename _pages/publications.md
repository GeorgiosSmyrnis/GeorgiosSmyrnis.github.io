---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=MmJ5U88AAAAJ).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
