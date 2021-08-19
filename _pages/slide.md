---
title: "Varun Jampani - SLIDE"
layout: gridlay
excerpt: "Varun Jampani: SLIDE"
sitemap: false
permalink: /slide/
---

[comment]: Title
<h2 align="center"> SLIDE: Single Image 3D Photography with Soft Layering and Depth-aware Inpainting </h2>
<p>&nbsp;</p>

[comment]: Authors
<p style="text-align: center;">
<a href="https://hfslyc.github.io" style="color: #CC0000"> Wei-Chih Hung </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="http://varunjampani.github.io" style="color: #CC0000"> Varun Jampani </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.sifeiliu.net/" style="color: #CC0000"> Sifei Liu </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://research.nvidia.com/person/pavlo-molchanov" style="color: #CC0000"> Pavlo Molchanov </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="http://faculty.ucmerced.edu/mhyang/" style="color: #CC0000"> Ming-Hsuan Yang </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="http://jankautz.com/" style="color: #CC0000"> Jan Kautz </a>
</p>
<p>&nbsp;</p>

[comment]: Abstract
<h3> Abstract </h3>
Single image 3D photography enables viewers to view a still image from novel viewpoints. Recent approaches combine monocular depth networks with inpainting networks to achieve compelling results. A drawback of these techniques is the use of hard depth layering, making them unable to model intricate appearance details such as thin hair-like structures. We present SLIDE, a modular and unified system for single image 3D photography that uses a simple yet effective soft layering strategy to better preserve appearance details in novel views. In addition, we propose a novel depth-aware training strategy for our inpainting module, better suited for the 3D photography task. The resulting SLIDE approach is modular, enabling the use of other components such as segmentation and matting for improved layering. At the same time, SLIDE uses an efficient layered depth formulation that only requires a single forward pass through the component networks to produce high quality 3D photos. Extensive experimental analysis on three view-synthesis datasets, in combination with user studies on in-the-wild image collections, demonstrate superior performance of our technique in comparison to existing strong baselines while being conceptually much simpler. 

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/scops_results.png" width="900px" />
		</div>
		<br />
    <figcaption>
				Sample part segmentation obtained by SCOPS on different types of image collections: (left) unaligned faces from CelebA, (middle) birds from CUB and (right) horses from PASCAL VOC dataset images, showing that SCOPS can be robust to appearance, viewpoint and pose variations.
    </figcaption>
</figure>
</center>

[comment]: Paper
<h3> Paper </h3>
- Paper: <a href="{{ site.url }}{{ site.baseurl }}/papers/jampani21_SLIDE.pdf" style="color: #CC0000"> PDF </a>
- Supplementary: <a href="{{ site.url }}{{ site.baseurl }}/papers/jampani21_SLIDE_supp.pdf" style="color: #CC0000"> PDF </a>

Please consider citing if you make use of this work and/or the corresponding code:

```
@inproceedings{jampani:ICCV:2021,
	title = {SLIDE: Single Image 3D Photography with Soft Layering and Depth-aware Inpainting},
	author = {Jampani, Varun and Chang, Huiwen and Sargent, Kyle and Kar, Abhishek and Rucker, Richard and Krainin, Michael and Kaeser, Dominik and Freeman, William T and Salesin, David and Curless, Brian and Liu, Ce},
	booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  year={2021}
}
```

<!-- [comment]: Code
<h3> Code </h3>
SCOPS is implemented using <a href="https://pytorch.org/" style="color: #CC0000">pytorch</a> neural network framework. Code is available in this github repository:
<a href="https://github.com/NVlabs/SCOPS" style="color: #CC0000">https://github.com/NVlabs/SCOPS</a>. -->

[comment]: Video
<h3> Video </h3>
<center>
<iframe width="900" height="500" src="https://youtu.be/RQio7q-ueY8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center>
