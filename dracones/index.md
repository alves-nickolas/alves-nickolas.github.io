---
layout: default
title: hic sunt dracones
---

<h1>
<div align="center">
  <img src="https://alves-nickolas.github.io/dracones/hicsuntwhite.png" alt="hic sunt dracones">
</div></h1>

<div align="center">
  <img src="https://alves-nickolas.github.io/dracones/dracones-eye.png" alt="Dragon eye inside a cave" width=300px>
</div>

Welcome to hic sunt dracones! I every now and then write threads on my [personal twitter](https://twitter.com/nickfismat) concerning Physics and Mathematics. Eventually I decided it was about time I created a blog to have a more logical way of doing SciComm. You see, I'm talkative, which means splitting texts in 280-character-long tweets frequently leads to dozens of tweets on a single thread. Hence, a blog. 


{% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.excerpt }}
{% endfor %}

