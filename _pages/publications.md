---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!--{% if author.googlescholar %}
  <p>You can also find my articles on <u><a href="https://scholar.google.com/citations?user=c5EdqCYAAAAJ&hl=en">my Google Scholar profile</a>.</u></p>
{% endif %}
-->
<p>Selected publications, full list can be found at <a href="https://scholar.google.com/citations?user=c5EdqCYAAAAJ&hl=en">my Google Scholar profile</a>.<br>
Return to <a href="https://jhpanda.github.io">Junhui's homepage</a>.<br> 
Jump to <a href="https://jhpanda.github.io/cv">Junhui's CV</a></p>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
