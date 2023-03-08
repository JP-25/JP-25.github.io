---
layout: page
title: Mixture-of-Experts for Recommender System
description: Resolved mainstream bias in recommender system
img: assets/img/12.jpg
importance: 1
category: work
---

- Wrote a customized Mixture-Of-Experts(MOE) based on the LOCA to construct one global model;
- Implemented original Multi-Variational Autoencoder model as the kernel experts model;
- Developed the customized gating network with validation loss guided method;
- Calculated the final result of gating network outputs with different expert outputs;
- Achieved optimal final results as LOCA but only contained one training global model;
- Demonstrated that the model with the ability to alleviate popularity bias and mainstream bias.

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

