---
layout: page
title: Deer contact network and supplementary bait
description: Jan, 2024 ~ ongoing
img: assets/img/12.jpg
importance: 1
category: Ongoing
related_publications: true
---

Animals track resource availability and adjust their movement to maximize resource gain. Supplementary feeding can therefore modify movement patterns in ways that elevate opportunities for pathogen transmission. 
Increased visitation and prolonged time spent near feeding sites bring individuals into closer proximity, raising direct contact rate. However, empirical evidence showing increased direct contacts and transmissions remains limited; most existing work is theoretical.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_imgs/project1_deerbait.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    White-tailed deer cofeeding (left) and encountering (upper right) at bait sites, which were piles of corns (bottom right)
</div>

To address this gap, we examined how feeding sites modify transmission potential by altering contact dynamics—focusing on the `<frequency>` and spatial distribution of contacts. 

    ---
    Q1) Does supplementary feeding increase and localize contact?
        - What demographic and environmental factors drive such a pattern? 
    Q2) How much does feeding enhances transmission potential?
    ---

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
