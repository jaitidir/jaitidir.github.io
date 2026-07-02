---
layout: page
title: F1 track fit
description:
img: assets/img/12.jpg
importance: 1
category: work
---

In this project we look for an approach to an interpolation/approximation problem. We consider a Formula 1 race track and from its geographical position we recover in various ways the path of the track.

We use different known techniques of interpolation and approximation, such us Lagrange’s, Hermite’s or Fourier’s methods, among others. We also analyse the track by dividing it in parts or examining it as a whole.

After trying these different approaches and perspectives of the problem we obtain different results. After comparing them, we reach certain conclusions about which one is the best to solve the problem


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some of the main results using parametric interpolation, Fourier's method and spline approximation by parts.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Best results obtained by interpolation by parts.
</div>

If you want to read it completely you can find it below:

<div style="width:100%; height:630px;">
  <iframe
    src="{{ '/assets/pdf/temat.pdf' | relative_url }}"
    width="100%"
    height="100%"
    style="border:none;"
    loading="lazy">
  </iframe>
</div>