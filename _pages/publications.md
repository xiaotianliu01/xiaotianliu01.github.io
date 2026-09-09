---
layout: page
permalink: /publications/
title: Publications
description: "<small class='text-muted'>* Authors are listed in alphabetical order.</small>"
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Working Papers</h2>

{% bibliography --group_by none --query @*[category=under_review]* %}

<h2>Journal Papers</h2>

{% bibliography --group_by none --query @*[category=published]* %}

<h2>Conference Papers</h2>

{% bibliography --group_by none --query @*[category=conference]* %}

<h2>Work in Progress</h2>

{% bibliography --group_by none --query @*[category=working]* %}

</div>
