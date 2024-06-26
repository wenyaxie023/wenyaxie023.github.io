---
layout: archive
title: "Miscellaneous"
permalink: /miscellaneous/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">I'm a big fan of Hermann Hesse's and Fyodor Dostoevsky's books.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
