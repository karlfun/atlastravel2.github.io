---
layout: single
title: "Around the World"
permalink: /blog/
---

<!-- HTML Meta Tags -->
<title>Around the World</title>
<meta name="description" content="Topeka-based organization established in 2024 to support academic study abroad through travel scholarships to eligible Shawnee County Students.">

<!-- Facebook Meta Tags -->
<meta property="og:url" content="https://atlastravelfoundation.org/blog/">
<meta property="og:type" content="website">
<meta property="og:title" content="Around the World">
<meta property="og:description" content="Topeka-based organization established in 2024 to support academic study abroad through travel scholarships to eligible Shawnee County Students.">
<meta property="og:image" content="https://atlastravelfoundation.org/assets/stamp-logo.jpg">

<!-- Twitter Meta Tags -->
<meta name="twitter:card" content="summary_large_image">
<meta property="twitter:domain" content="atlastravelfoundation.org">
<meta property="twitter:url" content="https://atlastravelfoundation.org/blog/">
<meta name="twitter:title" content="Around the World">
<meta name="twitter:description" content="Topeka-based organization established in 2024 to support academic study abroad through travel scholarships to eligible Shawnee County Students.">
<meta name="twitter:image" content="https://atlastravelfoundation.org/assets/stamp-logo.jpg">

<!-- Meta Tags Generated via https://www.opengraph.xyz -->

#### Recent posts from Around the World:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
