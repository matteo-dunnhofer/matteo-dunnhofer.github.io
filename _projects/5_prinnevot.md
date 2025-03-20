---
layout: project
title: PRINNEVOT
description: Horizon Europe MSCA Postdoctoral Global Fellowship 2023
img: assets/img/prinnevot.jpg
importance: 1
category: leading
related_publications: true
---

# Towards Primate-like Artificial Neural Networks for Visual Object Tracking
### Horizon Europe Marie Skłodowska-Curie Action Postdoctoral Global Fellowship 2023

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prinnevot.jpg" title="example image" class="img-fluid rounded " %}
    </div>
</div>

## Description

The PRINNEVOT project embarks on a mission to bridge the gap between computer vision and the primate visual system in the context of Visual Object Tracking (VOT). VOT is the task of maintaining focus on a specific object amidst a dynamic visual environment. Our brains excel at it but replicating this ability in artificial vision systems remains a challenge. This project seeks to develop a novel class of VOT algorithms inspired by the primate visual system's prowess. Despite notable advancements in deep learning-based VOT over the past decade, these algorithms still fall short in emulating the robustness exhibited by primate vision. PRINNEVOT will address this gap through a multi-faceted approach. Firstly, PRINNEVOT will construct a comprehensive reference dataset, investigating both primate behavior and neural recordings. Secondly, among the existing artificial neural network (ANN)-based VOT methodologies, the project aims to identify those that align most closely with the primate brain's mechanisms. Lastly, PRINNEVOT will leverage the discovered inductive biases to develop a new ANN architecture for VOT that closely mirrors the primate's way of continuous object recognition and localization. By merging computer vision and computational neuroscience research, PRINNEVOT aspires to contribute to the development of more accurate and robust VOT algorithms. These algorithms, in alignment with the European Union's pursuit of safer and ethically grounded Artificial Intelligence, promise to enhance human-centric and trustworthy technologies. Furthermore, the project's outcomes will not only benefit AI and computer vision but also advance our understanding of the primate visual system, offering new empirical models of how the brain tracks objects in dynamic visual environments.


## People

<div class="row">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prinnevot/matteo.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
    <a href="https://matteo-dunnhofer.github.io">
    Matteo Dunnhofer
    </a>
    </div>
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prinnevot/kohitij.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
    <a href="https://vital-kolab.org">
    Kohitij Kar
    </a>
    </div>
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prinnevot/christian.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
    <a href="https://people.uniud.it/page/christian.micheloni">
    Christian Micheloni
    </a>
    </div>
    </div>
</div>

## Institutions

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prinnevot/uniud.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prinnevot/yorku.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

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
