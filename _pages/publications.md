---
layout: archive
title: "Publications"
permalink: /pk-publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
<p><font size="5"><strong>Publications</strong></font></p>
<p><font size="3">*Click on the title for summary.</font></p>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
