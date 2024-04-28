---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Preprints
{% include base_path %}

{% for post in site.publications reversed %}{% if post.type == "preprint" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

## Conference articles

{% for post in site.publications reversed %}{% if post.type == "conf" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

## Journal articles
{% include base_path %}

{% for post in site.publications reversed %}{% if post.type == "journal" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}