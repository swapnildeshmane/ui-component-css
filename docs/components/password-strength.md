---
layout: docs
title: Password Strength
description: Documentation and examples for Password Strength using Bootstrap.
group: components
---

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}


## Password Strength (YM required)

{% example html %}
<div class="strength">
  <div class="strength-bar" role="progressbar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
</div>
<div class="strength">
  <div class="strength-bar" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
</div>
<div class="strength">
  <div class="strength-bar" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
</div>
{% endexample %}

## Customizing


### Backgrounds

Use background utility classes to change the appearance of individual progress bars.

{% example html %}
<div class="strength">
  <div class="strength-bar pass-danger" role="progressbar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
</div>
<div class="strength">
  <div class="strength-bar pass-warning" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
</div>
<div class="strength">
  <div class="strength-bar pass-success" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
</div>
{% endexample %}
