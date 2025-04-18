---
layout: page            # minima has 'page', 'post' and 'home' (home == blog index)
title: "Home"
permalink: /
---

# Lotus Oak Foundation
*Cultivating wisdom, technology, and culture for generations to come.*

Draft notice: This site is currently in DRAFT mode. Content and design will evolve quickly—stay tuned!


The oak stands firm,  
While the lotus blooms—it swiftly fades.

Endurance and ephemerality,  
A dance of strength and grace.

Neither wholly masculine nor feminine,  
Their virtues transcend boundaries.

Rooted in the wisdom of ages,  
East and West, ancient and modern,  
Echoing the eternal Tao.

## What We Do

The Lotus Oak Foundation blends philanthropy and ethical investment to address challenges in education, environment, healthcare, and culture. We operate a donor-advised fund model that supports high-impact initiatives, combining timeless wisdom with modern tools.

## Our Mission

We blend traditional philanthropy with innovative social venture approaches, enabling projects in education, healthcare, environmental conservation, and other crucial impact areas to flourish. Our core mission is to address systemic challenges through collaboration, research-based solutions, and responsible stewardship of resources, ensuring the greatest possible impact on community well-being.

## Quick Links

<ul class="quick-links">
  <li><a href="{{ '/vision/' | relative_url }}">Our Vision</a></li>
  <li><a href="{{ '/team/' | relative_url }}">Meet the Team</a></li>
  <li><a href="{{ '/how-it-works/' | relative_url }}">How It Works</a></li>
  <li><a href="{{ '/investment-options/' | relative_url }}">Investment Options</a></li>
  <li><a href="{{ '/contact/' | relative_url }}">Contact Us</a></li>
</ul>

## Latest Updates

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

**Disclaimer**  
The content presented on this site is for informational purposes only and does not constitute financial, legal, or investment advice. The Lotus Oak Foundation is not a registered investment advisor. Please consult a qualified professional before making any financial decisions.

[View all posts]({{ '/blog/' | relative_url }})