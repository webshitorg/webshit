---
layout: default
title: Home
---
<h2>
  <mark>Latest Articles</mark>
</h2>

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    - <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
  </li>
  {% endfor %}
</ul>

<h2>
  <mark>This website is shit.</mark>
</h2>
<p>
  Digital ethics is an iterative journey rather than a final state. While advocating for privacy and accessibility, the ongoing process of learning and implementing these standards remains a priority. As this project continues to evolve, community involvement is encouraged to help identify shortcomings and contribute to the Webshit project and this website itself.
  <p>