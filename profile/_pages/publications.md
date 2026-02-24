---
layout: page
permalink: /publications/
title: publications
description: selected publications (no year grouping)
nav: false
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{# Removed search on purpose for single-page setup #}

<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>
