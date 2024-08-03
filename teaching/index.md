---
title: Teaching
layout: default
---
<h1>{{ page.title }}</h1>

<p>This page lists different minicourses I taught throughout the years. Lecture notes and video recordings are given if they are publicly available. As usual, occurrences in Portuguese have documents in Portuguese.</p>

{% for course in site.teaching %}
    <h2>{{ course.title }}</h2>
    <p style="text-align: center;">{{ course.event }}</p>
    <p>{{ course.abstract }}</p>
    <p style="text-align: center;">{{ course.lecturenotes }}</p>
    <div style="text-align: center;">{{ course.videorecordings }}</div>
{% endfor %}
