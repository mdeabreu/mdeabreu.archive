---
layout: page
title: Tag Archive
permalink: /tag/
---

{% capture site_tags %}{% for cat in site.tags %}{{ cat | first }}{% unless forloop.last %},{% endunless %}{% endfor %}{% endcapture %}
{% assign tags = site_tags | split:',' | sort %}

<ul>
  {% for t in tags %}
    <li>{% taglink t %}{{ t }}{% endtaglink %}</li>
  {% endfor %}
</ul>

{% if tags.size > 0 %}
  <ul>
    {% for t in tags %}
      <li>{% taglink t %}{{ t }}{% endtaglink %}</li>
    {% endfor %}
  </ul>
{% else %}
  <p>It looks like there are no posts or pages that have been tagged.</p>
{% endif %}