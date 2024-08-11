---
layout: default
---

<div class="profile-section">
  <img src="{{ site.logo }}" alt="Bryan Nsoh" class="profile-image">
  <div class="profile-info">
    <h1>{{ site.title }}</h1>
    <p>{{ site.description }}</p>
    <a href="https://github.com/BryanNsoh" class="github-link">View My GitHub Profile</a>
  </div>
</div>

## My Projects

<div class="project-grid">
{% for project in site.data.projects %}
  <div class="project-card">
    <h3>{{ project.name }}</h3>
    <p>{{ project.description }}</p>
    <a href="{{ project.link }}">View on GitHub</a>
  </div>
{% endfor %}
</div>