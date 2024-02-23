---
layout: page
permalink: /Mutation Trends/
title: Mutation Trends
description: The mutation trends of important residues. There are several functional motifs or residues in both hemagglutinin (HA) and neuraminidase (NA).
nav: true
nav_order: 5
---

## HA:

##### Receptor-binding Site (S1): 129-138, 153-158, 183-195, 225-228
<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/mutation_trends/HA_ReceptorBinding(S1).gif" title="HA Receptor-binding Site (S1)" class="img-fluid rounded z-depth-1" %}
</div>
---

##### Fusion Peptide (S2): 345-367 (1-23 in S2)
<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/mutation_trends/HA_FusPeptide(S2).gif" title="HA Fusion Peptide (S2)" class="img-fluid rounded z-depth-1" %}
</div>
---

##### Loop -> Helix Peptide (S2): 399-421 (55-77 in S2)
<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/mutation_trends/HA_LoopHelixPeptide(S2).gif" title="HA Loop -> Helix Peptide (S2)" class="img-fluid rounded z-depth-1" %}
</div>
---

##### Fusion Helix (S2): 385-399, 421-444 (41-55, 77-100 in S2)
<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/mutation_trends/HA_FusHelix(S2).gif" title="HA Fusion Helix (S2)" class="img-fluid rounded z-depth-1" %}
</div>
---

## NA:

| Motif/Binding Pocket | Residues |
| -------- | ------- |
| Catalytic Center | R118, D151, R152, L224, Y276, C292, F371, F406 |
| (Related to host selection preference, not totally clear) | S367, G370, E372, S400, S403, K432 |
| Calcium-binding Site | R293, D294, H297, D324, G345, V346, K347 |

<p>&nbsp;</p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mutation_trends/NA_CatCenter_2023.png" title="NA Catalytic Center" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mutation_trends/NA_HostSelePref.gif" title="NA Host Selection Preference" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mutation_trends/NA_CaBinding_2023.png" title="NA Ca-binding Site" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
---
You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

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


