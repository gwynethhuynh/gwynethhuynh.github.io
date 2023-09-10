---
layout: page
title: Simple Distributed File System
description: store, fetch, and update files on a remote server from any client
img: assets/img/7.jpg
# redirect: https://unsplash.com
importance: 3
category: projects
---

I implemented remote procedure calls using gRPC and Protobuf to store, list, and fetch files and metadata to and from a remote server. I then added synchronization and caching to maintain files between multiple clients and threads.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gios.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
