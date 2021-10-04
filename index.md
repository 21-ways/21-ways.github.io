---
layout: page
title: 21 Ways
subtitle: 21 Ways To Look At Bitcoin
subtitle_link: http://21WaysBook.com
category: bitcoin
description: The prismatic nature of Bitcoin explored through 21 lenses.
quote: "\"Oh, you foolish Alice!\" she said again, \"how can you learn lessons in here? Why, there's hardly room for you, and no room at all for any lesson-books!\""
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

{% assign toc_pages = site.pages | where: "toc", true %}
{% assign pages_sorted = toc_pages | concat: site.ways | sort: 'order' %}

{% for way in pages_sorted %}
  * {{ way.title }}
{% endfor %}
