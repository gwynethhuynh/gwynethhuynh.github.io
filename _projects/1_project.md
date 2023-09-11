---
layout: page
title: capsule
description: a personal stylist for pieces you already own
img: assets/img/capsule-wardrobe-stock.jpeg
importance: 1
category: projects
---

Capsule is a full end-to-end web application that uses React for the frontend end and Node Express for the backend. It is inspired by Cher's closet from the movie, *Clueless*. 

Users can upload images of shirts and bottoms to their wardrobe, which are stored to Amazon S3.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/capsule-add.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/capsule-added.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

After building a wardrobe, users can then rate different combinations of shirts and bottoms. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/capsule-rate.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Capsule then uses collaborative filtering to make personalized outfit recommendations to the user.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/capsule-recommend.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<a href="https://github.com/gwynethhuynh/capsule-project">Link to My Project Code</a>



