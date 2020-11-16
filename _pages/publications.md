---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Journal Papers
---
{% for post in site.publications reversed %}
  {% if post.pubtype == "journal" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<br/>

Conference Papers
---
{% for post in site.publications reversed %}
  {% if post.pubtype == "conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<br/>

Patents
---
{% for post in site.publications reversed %}
  {% if post.pubtype == "patent" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<br/>

PhD Thesis
---
{% for post in site.publications reversed %}
  {% if post.pubtype == "thesis" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
