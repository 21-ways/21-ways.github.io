---
layout: page
title: 21 Ways
subtitle: 21 Ways To Look At Bitcoin
subtitle_link: http://21-ways.com
category: bitcoin
description: The prismatic nature of Bitcoin explored through 21 lenses.
quote: "\"Is it possible that there are people who say 'Bitcoin' and suppose they mean something shared by all?\""
image: /assets/images/21-ways-twitter-cover.jpg
---

{% include image.html path="/assets/images/21-ways-circle-orange.png" link="https://patreon.com/dergigi" %}

---

> Bitcoin is different things to different people.

---

21 Ways is a work in progress. Some chapters have already been published.
Just like my first book 21 Lessons, this book will be released under a
permissive [creative commons] license. Follow me on [twitter] and support me
on [patreon] if you want to tag along and support the project.

This project is run on a [value-for-value][v4v] basis. 🧡

[creative commons]: https://dergigi.com/license
[twitter]: https://twitter.com/dergigi
[patreon]: https://patreon.com/dergigi
[v4v]: https://dergigi.com/busking

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

<a id="toc"/>

[Introduction]

Terminology

[Chapter Zero: A Quick And Dirty Explanation][zero]

[Chapter 0.1: Bitcoin's Building Blocks][0.1]

[Introduction]: {{ 'intro' | absolute_url }}
[Terminology]: {{ 'terminology' | absolute_url }}
[zero]: {{ '0' | absolute_url }}
[0.1]: {{ 'blocks' | absolute_url }}


{% assign pages_sorted = site.ways | sort: 'order' %}

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
