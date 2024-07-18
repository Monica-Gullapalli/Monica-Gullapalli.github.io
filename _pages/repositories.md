---
layout: page
permalink: /repositories/
title: Repositories
description: Here's a few things I'm proud of working on
nav: true
nav_order: 4
---

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap justify-content-between">
  {% for user in site.data.repositories.github_users %}
    <div class="card mb-4" style="width: 18rem;">
      <div class="card-body">
        {% include repository/repo_user.liquid username=user %}
      </div>
    </div>
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}
  <h4>{{ user }}</h4>
{% endif %}
  <div class="repositories d-flex flex-wrap justify-content-between">
    <div class="card mb-4 trophy-card">
      <div class="card-body">
        {% include repository/repo_trophies.liquid username=user %}
      </div>
    </div>
  </div>
---
{% endfor %}
{% endif %}
{% endif %}

## GitHub Repositories

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap justify-content-between">
  {% for repo in site.data.repositories.github_repos %}
    <div class="card mb-4" style="width: 18rem;">
      <div class="card-body">
        {% include repository/repo.liquid repository=repo %}
      </div>
    </div>
  {% endfor %}
</div>
{% endif %}