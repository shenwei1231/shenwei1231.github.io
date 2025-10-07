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


## 1. 3D segmentation from 2D multi-view images

3D segmentation from 2D multi-view images, refers to segmenting the 3D structure of arbitrary objects from multi-view 2D images, enabling the rapid and convenient creation of 3D assets. Its capability facilitates applications such as robotic navigation and embodied intelligence simulations. However, this task is much more difficult than 2D image segmentation, requiring solutions to challenges such as establishing cross-view consistent constraints between pixels. We achieve this task by lifting the Segment Anything Model (SAM) from 2D to 3D with the assistance of radiance fields, such as NeRFs and 3DGS, which are known as efficient representations to connect 2D multi-view images with 3D structures.

<center>
 <video src="{{ site.baseurl }}/images/3dseg.mp4" controls="controls" width="85%" loop></video>
</center>
<br>
 
### Publications
 - Jiazhong Cen, Jiemin Fang, Zanwei Zhou, Chen Yang, Lingxi Xie, Xiaopeng Zhang, **Wei Shen**, Qi Tian. <font color='Navy'>Segment Anything in 3D with Radiance Fields</font>. **International Journal of Computer Vision**, 133(8): 5138-5160, 2025. ([PDF](https://arxiv.org/pdf/2304.12308.pdf))
 - Chen Yang, Sikuang Li, jiemin Fang, Ruofan Liang, Lingxi Xie, Xiaopeng Zhang, **Wei Shen**, Qi Tian. <font color='Navy'>GaussianObject: High-Quality 3D Object Reconstruction from Four Views with Gaussian Splatting</font>. **ACM Trans. Graphics (Siggraph Asia)**, 43(6)， 2024. ([PDF](https://arxiv.org/pdf/2402.10259))
 - Jiazhong Cen, Zanwei Zhou, Jiemin Fang, **Wei Shen**, Lingxi Xie, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian. <font color='Navy'>Segment Anything in 3D with NeRFs</font>. **Advances in Neural Information Processing Systems (NeurIPS)**, New Orleans, USA, 2023. ([PDF](https://proceedings.neurips.cc/paper_files/paper/2023/file/525d24400247f884c3419b0b7b1c4829-Paper-Conference.pdf)) ([CODE](https://github.com/SJTU-DeepVisionLab/SegmentAnythingin3D))
 - Jiazhong Cen, Xudong Zhou, Jiemin Fang, Changsong Wen, Lingxi Xie, Xiaopeng Zhang, **Wei Shen**, Qi Tian. <font color='Navy'>Tackling View-Dependent Semantics in 3D Language Gaussian Splatting</font>. **International Conference on Machine Learning (ICML)**, Vancouver, Canada, 2025. ([PDF](https://arxiv.org/abs/2505.24746))
 - Jiazhong Cen, Jiemin Fang, Chen Yang, Lingxi Xie, Xiaopeng Zhang, **Wei Shen**, Qi Tian. <font color='Navy'>Segment Any 3D Gaussians</font>. **AAAI Conference on Artificial Intelligence (AAAI)**, Philadelphia, USA, 2025. ([PDF](https://arxiv.org/pdf/2312.00860.pdf))
 
## 2. Tissue reconstruction from endoscopic surgery videos

Reconstructing deformable tissues from endoscopic videos in robotic surgery is crucial for various clinical applications, such as intraoperative assistance, surgery simulation and training. We propose highly-efficient tissue reconstruction methods based on NeRFs and 3DGS, which not only significantly accelerate the reconstruction process as well as the rendering process (up to real-time), but also maintain or even improve the reconstruction quality across a variety of non-rigid deformations. Our work received <span style="color:LightCoral;">Young Scientist Award</span> of MICCAI 2023.

<center>
 <video src="{{ site.baseurl }}/images/tissueReconstruction.mp4" controls="controls" width="85%" loop></video>
</center>
<br>

### Publications
- Chen Yang, Kailing Wang, Yuehao Wang, Qi Dou, Xiaokang Yang, **Wei Shen**. <font color='Navy'>Efficient Deformable Tissue Reconstruction via Orthogonal Neural Plane</font>. **IEEE Trans. Medical Imaging**, 43(9): 3211-3223, 2024. ([PDF](https://arxiv.org/pdf/2312.15253.pdf))
- Chen Yang, Kailing Wang, Yuehao Wang, Xiaokang Yang, **Wei Shen**. <font color='Navy'>Neural LerPlane Representations for Fast 4D Reconstruction of Deformable Tissues</font>. **International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)**, Vancouver, Canada, 2023. <span style="color:LightCoral;">[Young Scientist Award][STAR Award]</span> ([PDF](https://arxiv.org/abs/2305.19906))
- Kailing Wang, Chen Yang, Yuehao Wang, Sikuang Li, Yan Wang, Qi Dou, Xiaokang Yang, **Wei Shen**. <font color='Navy'>EndoGSLAM: Real-Time Dense Reconstruction and Tracking in Endoscopic Surgeries using Gaussian Splatting</font>. **International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)**, Marrakesh, Morocco, 2024. ([PDF](https://arxiv.org/pdf/2403.15124))
- Kailing Wang, Chen Yang, Rong Lin, Xiaokang Yang, **Wei Shen**. <font color='Navy'>EndoSD-SLAM: Real-time Deformable Endoscopic SLAM via Sparse-Dense Hybrid Representation</font>. **IEEE International Conference on Bioinformatics and Biomedicine (BIBM)**, Wuhan, China, 2025.
- Zanwei Zhou, Chen Yang, Piao Yang, Xiaokang Yang, **Wei Shen**. <font color='Navy'>EndoDAV: Depth Any Video in Endoscopy with Spatiotemporal Accuracy</font>. **International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)**, Daejeon, Korea, 2025. ([PDF](https://papers.miccai.org/miccai-2025/paper/1355_paper.pdf))

