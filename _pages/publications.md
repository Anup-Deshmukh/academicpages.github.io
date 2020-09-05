---
layout: archive
title: ""
permalink: /anup-publications/
author_profile: true
---

{% include base_path %}
<p><font size="5"><strong>Publications</strong></font></p>
<p><font size="3">*You can also find my articles on <i><a href="https://scholar.google.com/citations?user=YldJsvcAAAAJ&hl=en"> Google Scholar</a></i></font></p>
<p><font size="3">*Click on the title for summary</font></p>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
