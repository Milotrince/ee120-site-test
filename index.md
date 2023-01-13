---
layout: home
nav_order: 0
---

{%- if site.under_construction -%}
<p class="warning">
This site is under construction. All dates and policies are tentative until this message goes away.
</p>
{%- endif -%}

<!-- <img align="right" alt="CS188 Robot Waving" width="200px" src="assets/images/logo.png"> -->

# {{ site.title }}

## Announcements

{{ site.announcements.last }}

[Past announcements](announcements.md){: .btn .btn-outline .fs-3 }

## Calendar

[Skip to current week](#week-{{ 'now' | date: '%U' }}){: .btn .btn-outline .fs-3 }

<div>
{%- include syllabus.html -%}
</div>
