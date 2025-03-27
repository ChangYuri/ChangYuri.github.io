---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Welcome to my blog. I am a data scientist currently stuying at University of Chicago. I love coding, cooking, hiking and reading. Feel free to contact me.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
{% include about/skills.html title="Language Skills" source=site.data.language-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>