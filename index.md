---
layout: default
---

# Welcome to My Portfolio

I'm Bryan Soh, a Biosystems Engineer and AI Engineer passionate about automating intellectual labor with Large Language Models (LLMs).

## My Projects

{% for project in site.data.projects %}
<div class="project-card">
  <h3>{{ project.name }}</h3>
  <p>{{ project.description }}</p>
  <a href="{{ project.link }}">View on GitHub</a>
</div>
{% endfor %}