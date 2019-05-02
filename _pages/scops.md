---
title: "Varun Jampani - SCOPS"
layout: gridlay
excerpt: "Varun Jampani: SCOPS"
sitemap: false
permalink: /scops/
---

[comment]: Title
<h2 align="center"> SCOPS: Self-Supervised Co-Part Segmentation </h2>
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
Parts provide a good intermediate representation of objects that is robust with respect to the camera, pose and appearance variations. Existing works on part segmentation is dominated by supervised approaches that rely on large amounts of manual annotations and can not generalize to unseen object categories. We propose a self-supervised deep learning approach for part segmentation, where we devise several loss functions that aids in predicting part segments that are geometrically concentrated, robust to object variations and are also semantically consistent across different object instances. Extensive experiments on different types of image collections demonstrate that our approach can produce part segments that adhere to object boundaries and also more semantically consistent across object instances compared to existing self-supervised techniques.

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/scops_results.png" width="900px" />
		</div>
    <figcaption>
				Sample part segmentation obtained by SCOPS on different types of image collections: (left) unaligned faces from CelebA, (middle) birds from CUB~\cite{wah2011caltech} and (right) horses from PASCAL VOC dataset images, showing that SCOPS can be robust to appearance, viewpoint and pose variations.
    </figcaption>
</figure>
</center>

[comment]: Paper
<h3> Paper </h3>
- Paper: <a href="{{ site.url }}{{ site.baseurl }}/papers/hung19_SCOPS.pdf" style="color: #CC0000"> PDF </a>
- Supplementary: <a href="{{ site.url }}{{ site.baseurl }}/papers/hung19_SCOPS_supp.pdf" style="color: #CC0000"> PDF </a>

<!-- - Poster: <a href="https://ps.is.tuebingen.mpg.de/uploads_file/attachment/attachment/279/cvpr_poster.pdf" style="color: #CC0000"> PDF </a> -->

Please consider citing if you make use of this work and/or the corresponding code:

```
@inproceedings{hung:scops:2019,
	title = {SCOPS: Self-Supervised Co-Part Segmentation},
	author = {Hung, Wei-Chih and Jampani, Varun and Liu, Sifei and Molchanov, Pavlo and Yang, Ming-Hsuan and Kautz, Jan},
	booktitle = { IEEE Conf. on Computer Vision and Pattern Recognition (CVPR)},
	month = june,
	year = {2019}
}
```

[comment]: Code
<h3> Code </h3>
Coming soon.

[comment]: Video
<h3> Video </h3>
<center>
<iframe width="900" height="500" src="https://www.youtube.com/embed/q37MxZolDck" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center>

<!-- We integrated video propagation network into <a href="http://caffe.berkeleyvision.org/" style="color: #CC0000"> Caffe </a> neural network framework. Code is available online in ths github repository:
<a href="https://github.com/varunjampani/video_prop_networks" style="color: #CC0000"> https://github.com/varunjampani/video_prop_networks</a>. -->


<!-- <h3> Usage </h3>

The video propagation networks are generic and can be used for propagating any type of information across video frames. They are end-to-end trainable and can be combined with any existing deep network. The main use of VPNs in comparison to standard spatio-temporal CNNs is that VPNs can enable long-range pixel/superpixel connections while being computationally fast. In this paper, we experimented with label propagation (foreground or semantic labels) and colour propagation. See experiments in the paper and the corresponding <a href="https://github.com/varunjampani/video_prop_networks" style="color: #CC0000"> codes</a>.

An example color propagation:

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/color_propagation.png" width="800px" />
		<p> &nbsp; </p>
		</div>
    <figcaption>
		<b>
			Input grayscale video frames and corresponding ground-truth (GT) color images together with color predictions of Levin et al. (2004) and VPN-Stage1 models.
		</b>
    </figcaption>
</figure>
</center>

A couple of examples for object mask propagation:

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/video_seg_visuals.png" width="800px" />
		<p> &nbsp; </p>
		</div>
    <figcaption>
		<b>
			Shown are the different frames in example videos with the corresponding ground truth (GT) masks, predictions from BVS [M&auml;rki et al. 2016], OFL [Tsai et al. 2016], VPN (VPN- Stage2) and VPN-DLab (VPN-DeepLab) models.
		</b>
    </figcaption>
</figure>
</center>

<p> &nbsp; </p> -->
