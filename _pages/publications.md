---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=U2etQ3AAAAAJ&hl=en">Google Scholar</a>.</u>

{% include base_path %}

## Preprints

{% for post in site.publications reversed %}
  {% if post.pubsource == "unpublished" %}
    {% include archive-single2.html %}
  {% endif %}
{% endfor %}

## Publications

{% for post in site.publications reversed %}
  {% if post.pubsource == "journal" %}
    {% include archive-single2.html %}
  {% endif %}
{% endfor %}
