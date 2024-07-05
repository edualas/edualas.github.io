---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  <div class="wordwrap">
    You can find my articles on my Google Scholar profile:
    <iframe src="{{site.author.googlescholar}}" width="100%" height="500px"></iframe>
  </div>
{% endif %}
{% comment %}
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
