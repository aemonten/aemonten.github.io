---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Here’s a list of my publications. For citation information, please check <a href="https://scholar.google.cl/citations?user=PiMdG1EAAAAJ&hl=en" target="_blank" rel="noreferrer noopener">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
