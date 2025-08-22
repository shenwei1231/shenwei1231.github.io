---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}


## [1. 3D segmentation from 2D multi-view images](/research/3dseg/)

3D segmentation from 2D multi-view images, refers to segmenting the 3D structure of arbitrary objects from multi-view 2D images, enabling the rapid and convenient creation of 3D assets. Its capability facilitates applications such as robotic navigation and embodied intelligence simulations. However, this task is much more difficult than 2D image segmentation, requiring solutions to challenges such as establishing cross-view consistent constraints between pixels. We achieve this task by lifting the Segment Anything Model (SAM) from 2D to 3D with the assistance of radiance fields, such as NeRFs and 3DGS, which are known as efficient representations to connect 2D multi-view images with 3D structures.

<center><div style="position: relative; width: 85%; height: 0; padding-bottom: 45%;">
<video width="100%" height="100%" controls>
    <source src="{{ site.baseurl }}/images/3dseg.mp4" type="video/mp4">
</video></div></center><br>

## [2. Tissue reconstruction from endoscopic surgery videos](/research/3dseg/)
