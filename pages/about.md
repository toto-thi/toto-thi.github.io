---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
A senior computer science student at NUOL, Laos. I process a strong logical implementation and my interpersonal are excellent. I love to code in my free time and watch some movies. See my skills and experiences below :point_down:.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}

</div>

<div class="row">
{% include about/skills.html title="Version Control" source=site.data.version-control %}
{% include about/skills.html title="Framework" source=site.data.frameworks-skill %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>