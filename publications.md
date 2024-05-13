---
title: Publications
description: |
    This section covers languages will you need to be familar with to build a Jekyll static site
---

<ul>
    {% for publication in site.publications %}
        <li>
            <h2>
                <a href="{{ publication.url | relative_url }}">
                    {{ publication.title }}
                </a>
            </h2>

            <p>
                <i>{{ publication.description }}</i>
            </p>
            <p>{{ publication.excerpt }}</p>
        </li>
    {% endfor %}
</ul>
