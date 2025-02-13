---
title: "Varun Jampani - SLIDE"
layout: gridlay
excerpt: "Varun Jampani: SLIDE"
sitemap: false
permalink: /slide/
---

[comment]: Title
<h2 align="center"> SLIDE: Single Image 3D Photography <br> with Soft Layering and Depth-aware Inpainting </h2>
<p>&nbsp;</p>

[comment]: Authors
<p style="text-align: center;">
<a href="http://varunjampani.github.io" style="color: #CC0000"> Varun Jampani* </a>
&nbsp;
<a href="https://scholar.google.com/citations?user=eZQNcvcAAAAJ&hl=en" style="color: #CC0000"> Huiwen Chang* </a>
&nbsp;
<a href="https://www.linkedin.com/in/kyle-sargent-784006134" style="color: #CC0000"> Kyle Sargent </a>
&nbsp;
<a href="https://abhishekkar.info/" style="color: #CC0000"> Abhishek Kar </a>
&nbsp;
<a href="https://research.google/people/RichardTucker/" style="color: #CC0000"> Richard Tucker </a>
&nbsp;
<a href="https://research.google/people/107089/" style="color: #CC0000"> Michael Krainin </a>
<br>
<a href="https://www.linkedin.com/in/dominikkaeser" style="color: #CC0000"> Dominik Kaeser </a>
&nbsp;
<a href="https://billf.mit.edu/" style="color: #CC0000"> William T. Freeman </a>
&nbsp;
<a href="http://salesin.cs.washington.edu/" style="color: #CC0000"> David Salesin </a>
&nbsp;
<a href="https://homes.cs.washington.edu/~curless/" style="color: #CC0000"> Brian Curless </a>
&nbsp;
<a href="https://people.csail.mit.edu/celiu/" style="color: #CC0000"> Ce Liu </a>
&nbsp;
</p>
<p style="text-align: center;"> Google </p>
<p style="text-align: center;"> International Conference on Computer Vision (ICCV 2021, Oral) </p>

[comment]: Abstract
<h3> Abstract </h3>
Single image 3D photography enables viewers to view a still image from novel viewpoints. Recent approaches combine monocular depth networks with inpainting networks to achieve compelling results. A drawback of these techniques is the use of hard depth layering, making them unable to model intricate appearance details such as thin hair-like structures. We present SLIDE, a modular and unified system for single image 3D photography that uses a simple yet effective soft layering strategy to better preserve appearance details in novel views. In addition, we propose a novel depth-aware training strategy for our inpainting module, better suited for the 3D photography task. The resulting SLIDE approach is modular, enabling the use of other components such as segmentation and matting for improved layering. At the same time, SLIDE uses an efficient layered depth formulation that only requires a single forward pass through the component networks to produce high quality 3D photos. Extensive experimental analysis on three view-synthesis datasets, in combination with user studies on in-the-wild image collections, demonstrate superior performance of our technique in comparison to existing strong baselines while being conceptually much simpler. 

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide_teaser.png" width="900px" />
		</div>
		<br />
    <figcaption>
		Single image view synthesis with SLIDE (Ours) show better preservation of hair structures compared to that of <a href="https://shihmengli.github.io/3D-Photo-Inpainting/">3D-Photo</a>.
    We also show the novel view (Ours-No-BG) where the background (BG) layer is greyed-out
    to showcase our soft layering.
    </figcaption>
</figure>
</center>

[comment]: Paper
<h3> Paper </h3>
- Paper: <a href="https://arxiv.org/abs/2109.01068" style="color: #CC0000"> arXiv </a>
- Supplementary: <a href="{{ site.url }}{{ site.baseurl }}/papers/jampani21_SLIDE_supp.pdf" style="color: #CC0000"> PDF </a>

[comment]: Video Summary
<h3> Video Summary </h3>
<center>
<iframe width="900" height="500" src="https://youtube.com/embed/RQio7q-ueY8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center>

[comment]: Visual Results
<h3> Video Results </h3>
<h4>Click <a href="https://varunjampani.github.io/slide_visual_results.html" style="color: #CC0000">here</a> for side-by-side results of different techniques.</h4>

[comment]: Citation
<h3> Citation </h3>
```
@inproceedings{jampani:ICCV:2021,
	title = {SLIDE: Single Image 3D Photography with Soft Layering and Depth-aware Inpainting},
	author = {Jampani, Varun and Chang, Huiwen and Sargent, Kyle and Kar, Abhishek and Tucker, Richard and Krainin, Michael and Kaeser, Dominik and Freeman, William T and Salesin, David and Curless, Brian and Liu, Ce},
	booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  year={2021}
}
```
