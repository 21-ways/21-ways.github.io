---
layout: page
title: 21 Ways
subtitle: 21 Ways To Look At Bitcoin
subtitle_link: http://21WaysBook.com
category: bitcoin
description: The prismatic nature of Bitcoin explored through 21 lenses.
quote: "\"Is it possible that there are people who say 'Bitcoin' and suppose they mean something shared by all?\""
image: /assets/images/21-lessons-twitter-cover-audio.jpg
---

<div class="action-buttons">
  <div class="button button-red button-large">
    <a href="https://patreon.com/dergigi"><i class="fab fa-patreon"></i> &nbsp; Become a Patron</a>
  </div>
  <small>
    (or
    <a href="https://dergigi.com/support">support me</a>
    in another way
    )
  </small>
</div>

---

Introduction


Terminology


Chapter Zero: A Quick And Dirty Explanation


### 21 Ways

{% assign toc_pages = site.pages | where: "toc", true %}
{% assign pages_sorted = toc_pages | concat: site.ways | sort: 'order' %}

{% for way in pages_sorted %}
  {% if way.link %}
  1. [{{ way.title }}]({{ way.link }})
  {% else %}
  1. {{ way.title }}
  {% endif %}
{% endfor %}


What Bitcoin Is Not

Glossary

Thanks
