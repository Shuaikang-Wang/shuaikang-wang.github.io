---
layout: cv
permalink: /cv/
title: CV
nav: true
# nav_order: 5
cv_pdf: /assets/cv/cv_20251110.pdf # you can also use external links here
---


{% assign cv_url = page.cv_pdf | relative_url %}
<meta http-equiv="refresh" content="0; url={{ cv_url }}">
<p>If you are not redirected, <a href="{{ cv_url }}">click here</a>.</p>
