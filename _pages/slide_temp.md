---
title: "Varun Jampani - SLIDE"
layout: gridlay
excerpt: "Varun Jampani: SLIDE"
sitemap: false
permalink: /slide_temp/
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
<p style="text-align: center;"> Google Research </p>
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
- Paper: <a href="{{ site.url }}{{ site.baseurl }}/papers/jampani21_SLIDE.pdf" style="color: #CC0000"> PDF </a>
- Supplementary: <a href="{{ site.url }}{{ site.baseurl }}/papers/jampani21_SLIDE_supp.pdf" style="color: #CC0000"> PDF </a>

[comment]: Video Summary
<h3> Video Summary </h3>
<center>
<iframe width="900" height="500" src="https://youtube.com/embed/RQio7q-ueY8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</center>

[comment]: Visual Results
<style>
h3 {
  font-weight: normal;
}
.example {
  position: relative;
  display: inline-block;
  max-width: 100%;
  min-width: 700px;
}
.item {
  display: inline-block;
  width: 15%;
}
.ibox {
  background: #FFF;
  position: absolute;
  visibility: hidden;
  top: 30px;
  bottom: 0;
  left: 0;
  right: 0;
}
.item img, .item video {
  width: 100%;
  position: absolute;
}
.item:nth-child(1) .ibox {
  visibility: inherit;
}
.item:hover .ibox {
  visibility: inherit;
}
.item .label {
  cursor: pointer;
  text-align: center;
  white-space: nowrap;
  background: #444;
  color: #ddd;
  line-height: 30px;
  margin-right: 4px;
}
.item:hover .label {
  background: #000;
  font-weight: bold;
  color: #faa;
}
.four .item {
  width: 20%;
}

img.height {
  display: block;
  visibility: hidden;
  padding-top: 30px;
  max-width: 100%;
  min-width: 700px;
}
</style>

<h3>RealEstate10K - Hover over the tabs to show the different results</h3>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/input_image.png" /></div>
	<div class=label>Input</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/gt.gif" /></div><div class=label>Ground truth</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/slide.gif" /></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/3dphoto.gif" /></div><div class=label>3D Photo</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/smpi.gif" /></div><div class=label>MPI</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/synsin.gif" /></div><div class=label>Synsin</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/RE10K/example_1/input_image.png" />
</div>

<h3>MannequinChallenge - Hover over the tabs to show the different results</h3>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/input_image.png"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/gt.gif"></div><div class=label>Ground truth</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/slide.gif"></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/3dphoto.gif"></div><div class=label>3D Photo</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/smpi.gif"></div><div class=label>MPI</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/synsin.gif"></div><div class=label>Synsin</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/MC/example_1/input_image.png">
</div>

<h3>Dual-pixels - Hover over the tabs to show the different results</h3>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/input_image.png"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/gt.gif"></div><div class=label>Ground truth</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/slide.gif"></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/3dphoto.gif"></div><div class=label>3D Photo</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/smpi.gif"></div><div class=label>MPI</div>
</div><div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/synsin.gif"></div><div class=label>Synsin</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/dual_pixels/example_1/input_image.png">
</div>

<h3>Online photo collections - Hover over the tabs to show the different results</h3>
<div class=four>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_1/input_image.jpg"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_1/slide.mp4"></video></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_1/slide_with_matte.mp4"></video></div><div class=label>SLIDE with matte(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_1/3dphoto.mp4"></video></div><div class=label>3D Photo</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_1/input_image.jpg">
</div>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_2/input_image.jpg"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_2/slide.mp4"></video></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_2/slide_with_matte.mp4"></video></div><div class=label>SLIDE with matte(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_2/3dphoto.mp4"></video></div><div class=label>3D Photo</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_2/input_image.jpg">
</div>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_3/input_image.jpg"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_3/slide.mp4"></video></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_3/slide_with_matte.mp4"></div></video><div class=label>SLIDE with matte(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_3/3dphoto.mp4"></video></div><div class=label>3D Photo</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_3/input_image.jpg">
</div>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_4/input_image.jpg"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_4/slide.mp4"></video></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_4/slide_with_matte.mp4"></video></div><div class=label>SLIDE with matte(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_4/3dphoto.mp4"></video></div><div class=label>3D Photo</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_4/input_image.jpg">
</div>
<div class=example>
<div class=item><div class=ibox><img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_6/input_image.jpg"></div><div class=label>Input</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_6/slide.mp4"></video></div><div class=label>SLIDE(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_6/slide_with_matte.mp4"></video></div><div class=label>SLIDE with matte(Ours)</div>
</div><div class=item><div class=ibox><video autoplay loop muted src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_6/3dphoto.mp4"></video></div><div class=label>3D Photo</div>
</div><img class=height src="{{ site.url }}{{ site.baseurl }}/images/projectpic/slide/media/unsplash/example_6/input_image.jpg">
</div>
</div>



[comment]: Citation
<h4> Citation </h4>
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
