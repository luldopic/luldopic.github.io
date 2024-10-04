---
layout: default
title: Projects
---

<h2>Projects</h2>
<div class="row">
    {% for project in site.projects %}
        <div class="col-md-4">
            {% include project_card.html project=project %}
        </div>
    {% endfor %}
</div>
