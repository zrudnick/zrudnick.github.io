---
layout: home
title: Home
---

# Welcome to My Website

Hi! I'm Zoe Rudnick, a Biomedical Engineering PhD student passionate about computational genomics.

## About Me
Brief introduction about yourself, your background, current work or studies, and what drives you.

## What You'll Find Here
- **Projects**: Detailed information about my work and personal projects
- **Blog**: Thoughts on [your topics of interest]
- **Resume**: My professional background and experience

## Recent Projects
{% for project in site.projects limit:3 %}
- [{{ project.title }}]({{ project.url }}) - {{ project.description }}
{% endfor %}

[View All Projects →](/projects/)
