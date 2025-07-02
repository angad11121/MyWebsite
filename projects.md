---
layout: default
title: Projects
---

## Projects

{% for project in site.data.projects %}
### {{ project.name }}
{{ project.description }}

[View Project]({{ project.link }})
{% endfor %}