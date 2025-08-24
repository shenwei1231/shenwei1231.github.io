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

<center>
 <video src="{{ site.baseurl }}/images/3dseg.mp4" controls="controls" width="85%" loop></video>
</center>
<br>
 
### Publications
 - Jiazhong Cen, Jiemin Fang, Zanwei Zhou, Chen Yang, Lingxi Xie, Xiaopeng Zhang, **Wei Shen**, Qi Tian. <font color='Navy'>Segment Anything in 3D with Radiance Fields</font>. **International Journal of Computer Vision**, 133(8): 5138-5160, 2025. ([PDF](https://arxiv.org/pdf/2304.12308.pdf))
 - Jiazhong Cen, Zanwei Zhou, Jiemin Fang, **Wei Shen**, Lingxi Xie, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian. <font color='Navy'>Segment Anything in 3D with NeRFs</font>. **Advances in Neural Information Processing Systems (NeurIPS)**, New Orleans, USA, 2023. ([PDF](https://proceedings.neurips.cc/paper_files/paper/2023/file/525d24400247f884c3419b0b7b1c4829-Paper-Conference.pdf)) ([CODE](https://github.com/SJTU-DeepVisionLab/SegmentAnythingin3D))
 - 
 
 
## [2. Tissue reconstruction from endoscopic surgery videos](/research/3dseg/)
