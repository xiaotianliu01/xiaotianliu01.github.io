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

<h2>Papers Under Revision</h2>

{% bibliography --group_by none --query @*[category=under_review]* %}

<h2>Published Papers</h2>

{% bibliography --group_by none --query @*[category=published]* %}

<h2>Working Papers</h2>

{% bibliography --group_by none --query @*[category=working]* %}

</div>
