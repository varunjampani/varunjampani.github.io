---
title: "Varun Jampani - Home"
layout: gridlay
excerpt: "Varun Jampani"
sitemap: false
permalink: /
---

<div class="hero-section">

<div class="hero-content">

I am Chief AI Officer at Arcade AI. Prior to that I was a VP Research at Stability AI. In the past, I was a researcher at Google Research and Nvidia Research. I completed my PhD at [Perceiving Systems](https://ps.is.tuebingen.mpg.de) department, Max-Planck Institute (MPI) for Intelligent Systems in T&uuml;bingen, Germany. My PhD advisor was [Prof. Peter V. Gehler](http://files.is.tue.mpg.de/pgehler//).
I did my bachelors and masters in Computer Science at [IIIT-Hyderabad](https://www.iiit.ac.in), India.

<!-- My work lies at the intersection of Computer Vision and Machine Learning. Specifically, I am working on leveraging machine learning techniques for understanding and improving computer vision models. The main research question is how different components of a computer vision system need to learn and interact with each other for robust perception. -->

<!-- My research interests include 3D/4D Computer Vision and Machine Learning. Specifically, I am mainly interested in automatic 3D and 4D object understanding from internet image collections and videos leveraging both reconstruction and generation techniques. In addition, I also work on understanding and generating creative images such as visual metaphors, paintings etc. -->

<!-- At Stability AI, we strive to advance the state-of-the-art in vision foundation models with diverse applications in understanding, reconstruction and generation tasks in both 2D and 3D. A central research question is how to train generative models that can act as generic yet powerful priors for the visual world around us. -->

<!-- **_I am looking for motivated students for collaborations and internships. If interested, please drop me an email with your CV._** -->

**_If you are interested in joining my team at Arcade or research collaborations or internships, please drop me an email with your CV._**
  
<!-- **_We have research scientist and software engineer positions in our team in Google Research. Please drop me an email with your CV if you are interested in applying._** -->

### News
{% for article in site.data.news limit:9 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
<a href="{{ site.url }}{{ site.baseurl }}/allnews.html">see all news</a>

</div>

<div class="hero-sidebar">

  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_pic.jpeg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->

  <A HREF="mailto:&#118;&#097;&#114;&#117;&#110;&#106;&#097;&#109;&#112;&#097;&#110;&#105;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;">&#118;&#097;&#114;&#117;&#110;&#106;&#097;&#109;&#112;&#097;&#110;&#105;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;</A> <br>
  Arcade AI <br>
  Boston, MA, USA.<br>


</div>

</div>

<div class="main-content-section">

### Publications
  
Refer to my <a href="https://scholar.google.com/citations?hl=en&user=1Cv6Sf4AAAAJ&view_op=list_works"> Google Scholar </a> page for an up-to-date list of publications.

<!-- {% for publi in site.data.publist limit:30 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">see all publications</a>

</div>

<div class="col-sm-12">

### Theses

{% for publi in site.data.theseslist limit:6 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<p> &nbsp; </p>

</div> -->



<p>&nbsp;</p>

<h3>Notable Achievements and Awards</h3>

<ul>
<li><strong>Best Student Paper Honorable Mention</strong> award at CVPR’23.</li>
<li><strong>Best Paper Honorable Mention</strong> award at CVPR’18.</li>
<li><strong>Nvidia Pioneering Research Award</strong>, 2018.</li>
<li><strong>Summa cum laude (highest honors)</strong> from the University of Tübingen for my PhD dissertation.</li>
<li><strong>Outstanding Reviewer Awards</strong> at CVPR'19, CVPR’18, CVPR’17 and ECCV’16.</li>
<li><strong>Gold Medal</strong> for being first in my B.Tech. (out of around 180 students) at IIIT-Hyderabad.</li>
<li>Member of <strong>Doctoral Consortium</strong> at CVPR'16.</li>
<li>Prestigious <strong>Pratibha Scholarship</strong> given by the state government of Andhra Pradesh, India.</li>
<li>All India Rank of <strong>121</strong> (out of over 700K students) in AIEEE'05 and State Rank of <strong>306</strong> (out of over 150K students) in EAMCET'05.</li>
<li>Scholarships from CBSE, national and state governments of India for my academic achievements.</li>
<li>One of the 50 finalists from all over the India for <strong>Reliance-Stanford scholarship 2011</strong>.</li>
<li>A member of 100-member <strong>Youth delegation to China</strong> in 2009 organized by the Ministry of Youth affairs and Sports, India.</li>
</ul>

<p>&nbsp;</p>

<h3>Work Experience</h3>

<h4>Research</h4>

<ul>
<li><strong>Arcade AI, USA</strong>
<ul>
	<li>Chief AI Officer<em>(October&rsquo;25 &ndash; till date)</em></li>
	<li>Generative Product Design.</li>
</ul>
</li>

<li><strong>Stability AI, USA</strong>
<ul>
	<li>VP Research <em>(August&rsquo;24 &ndash; October&rsquo;25)</em></li>
	<li>Lead Researcher <em>(November&rsquo;23 &ndash; August&rsquo;24)</em></li>
	<li>Image, Video and 3D Generative Models.</li>
</ul>
</li>
 
<li><strong>Google Research, Cambridge, MA, USA</strong>
<ul>
	<li>Senior Research Scientist <em>(October&rsquo;21 &ndash; October&rsquo;23)</em></li>
	<li>Research Scientist <em>(July&rsquo;19 &ndash; October&rsquo;21)</em></li>
	<li>3D reconstruction and generation from internet imagery.</li>
</ul>
</li>

<li><strong>Nvidia Research, Westford, MA, USA</strong>

<ul>
	<li>Research Scientist <em>(July&rsquo;17 &ndash; July&rsquo;19)</em></li>
	<li>Learning techniques for computer vision applications.</li>
</ul>
</li>
	<li><strong>Microsoft Research, Cambridge, UK</strong>

	<ul>
		<li>Research Intern <em>(July&rsquo;14 &ndash; Oct&rsquo;14)</em></li>
		<li>Consensus message passing technique for making infer.NET viable for solving vision problems.</li>
	</ul>
	</li>
	<li><strong>Max Planck Institute for Intelligent Systems, T&uuml;bingen, Germany</strong>
	<ul>
		<li>Visiting Researcher <em>(July&rsquo;12 &ndash; Oct&rsquo;12)</em></li>
		<li>Explored different ways of white balancing an image illuminated with multiple colored light sources.</li>
	</ul>
	</li>
	<li><strong>Microsoft Research, Redmond, USA</strong>
	<ul>
		<li>Research Intern <em>(Aug&rsquo;09 &ndash; Oct&rsquo;09)</em></li>
		<li>Developed novel interfaces for web image search results using Silverlight.</li>
	</ul>
	</li>
	<li><strong>Microsoft Advanced Technology Labs, Cairo, Egypt</strong>
	<ul>
		<li>Research Assistant <em>(April&rsquo;12 &ndash; July&rsquo;12)</em></li>
		<li>Developed an image classification system to index web images.</li>
	</ul>
	</li>
	<li><strong>GE Global Research, Bengaluru, India</strong>
	<ul>
		<li>Research Intern <em>(May&rsquo;09 &ndash; July&rsquo;09)</em></li>
		<li>Analyzed experimental data for our perception studies on Pneumoconiosis diagnosis.</li>
	</ul>
	</li>
	<li><strong>Cognitive Sciences Lab, IIIT-Hyderabad, Hyderabad, India</strong>
	<ul>
		<li>Research Assistant <em>(July&rsquo;08 &ndash; Dec&rsquo;08)</em></li>
		<li>Did experiments to test the usability of different pages on a famous Indian web portal.</li>
	</ul>
	</li>
</ul>

<h4>Software Development</h4>

<ul>
	<li><strong>Crypsis Technologies, Hyderabad, India</strong>

	<ul>
		<li>Software Development Engineer <em>(Aug &rsquo;11 &ndash; Feb &rsquo;12)</em></li>
		<li>Developed a web browser based service for mobile website testing using Objective C, Ruby etc&hellip;</li>
	</ul>
	</li>
	<li><strong>Medical Imaging Solutions, Hyderabad, India</strong>
	<ul>
		<li>Software Development Engineer <em>(Dec &rsquo;10 &ndash; March &rsquo;11)</em></li>
		<li>Developed a DICOM communications and download monitor tool using QT-C++</li>
	</ul>
	</li>
</ul>

<h4>Teaching Experience</h4>

<ul>
	<li><strong>IIIT-Hyderabad, Hyderabad, India</strong>

	<ul>
		<li>Teaching Assistant for Computer Vision, Maths-1 and Maths-2 courses</li>
		<li>Involved in conducting tutorial sessions, problem solving sessions and some mid-term exams</li>
	</ul>
	</li>
	<li><strong>Tibetan Children&rsquo;s Village, Dharamsala, India</strong>
	<ul>
		<li>Volunteer Teacher <em>(Sept&rsquo;10 &ndash; July&rsquo;11)</em></li>
		<li>Taught Mathematics, Physics and Biology for class-IX, X and XI students</li>
	</ul>
	</li>
</ul>

<p>&nbsp;</p>

<h3>Education</h3>

<p><em>(Jan&rsquo;13 &ndash; July &rsquo;17)</em></p>

<p><strong>Max-Planck Institute for Intelligent Systems</strong> and <strong>University of T&uuml;bingen</strong>, T&uuml;bingen, Germany</p>

<p>Doctor of Philosophy (<em>PhD</em>) in computer vision and machine learning (Grade: <strong>summa cum laude</strong>)</p>

<p>Thesis Title: Learning Inference Models for Computer Vision</p>

<p>Advisor: Prof. Peter V. Gehler</p>

<p>&nbsp;</p>

<p><em>(July&rsquo;09 - Dec &rsquo;12)</em></p>

<p><strong>International Institute of Information Technology</strong>, Hyderabad (IIIT-H), India</p>

<p>Master of Science (<em>MS</em>) by Research in computer sciences</p>

<p>Thesis Title: A Study of X-ray Image Perception for Pneumoconiosis Diagnosis</p>

<p>Advisors: Prof. Jayanthi Sivaswamy and Prof. Bipin Indurkhya</p>

<p>&nbsp;</p>

<p><em>(July &rsquo;05 &ndash; May &rsquo;09)</em></p>

<p><strong>International Institute of Information Technology</strong>, Hyderabad (IIIT-H), India</p>

<p>Bachelor of Technology (<em>BTech</em>) with Honours in computer sciences (CGPA: <strong>9.68/10.0</strong>)</p>

<p><strong>Gold Medalist </strong>and member of <strong>Dean&rsquo;s list&nbsp;</strong>for all the semesters</p>

<p>&nbsp;</p>

<h3>Academic Services</h3>
<ul>
<li><strong>Meta-Reviewer:</strong> CVPR'20, BMVC'21, AAAI'21, IJCAI'21, BMVC'22, WACV'23, AAAI'23, CVPR'23, BMVC'23, NeurIPS'23, WACV'24, CVPR'24, ICLR'24, ECCV'24, ICML'24, BMVC'24, NeurIPS'24, CVPR'25, ICCV'25, NeurIPS'25, CVPR'26, ICLR'26, ECCV'26, NeurIPS'26.</li>
<li><strong>Reviewer:</strong> I serve as a reviewer for the following conferences and journals: CVPR, NIPS, ICCV, ECCV, PAMI, SIGGRAPH Asia, NSF review panel</li>
<li>I received <strong>Outstanding Reviewer</strong> awards at CVPR'19, CVPR'18, CVPR'17 and ECCV'16 </li>
<li><strong>PhD Thesis Committee:</strong> Zezhou Cheng (UMass, 2023), Chun-Han Yao (UCMerced, 2023)</li>
</ul>

<p>&nbsp;</p>

<h3>Talks</h3>
<ul>
<li>Invited talk at Boston University, Boston, March, 2026.</li>
<li>Invited talk at KUIS AI Center, Koç University, November, 2025.</li>
<li>Keynote talk on 'Crafting Video Diffusion: Precise Inputs and Rich Outputs' at ICCV'25 Workshops on 'AI for 3D Content Creation', 'Generative Scene Completion' and, 'Advances in Image Manipulation', October, 2025.</li>
<li>Invited talk on 'Diffusion Dialed In: Light and Heavy Adaptations of Diffusion Models for Complex Vision Tasks' at CVPR'25 Workshop on <a href="https://vgm-cvpr.github.io/">Visual Generative Modeling: What's after diffusion</a>, June, 2025.</li>
<li>Invited talk on 'Diffusion Dialed In: Light and Heavy Adaptations of Diffusion Models for Complex Vision Tasks' at CVPR'25 Workshop on SyntaGen, June, 2025.</li>
<li>Invited talk on 'A Tale of Two Directions for 3D Generative Models', UIUC, December, 2024.</li>
<li>Guest lecture in Advanced Topics in Computer Vision, University of California, Merced, December, 2024.</li>	
<li>Guest lecture on 'A Tale of Two Directions for 3D Generative Models' in Frontier Topics in Generative AI, Arizona State University, MA, October, 2024.</li>
<li>Invited talk on 'Thinking Fast and Slow: Recent Trends in 3D Generative Models' at ECCV'24 Tutorial on <a href="https://efficient-genai.github.io/index.html">Efficient Generative AI Tutorial</a>, October, 2024.</li>
<li>Keynote talk on 'Instance-Specific 2D and 3D Generation' at ECCV'24 workshop on <a href="https://ilr-workshop.github.io/ECCVW2024/">Instance-Level Recognition Workshop</a>, October, 2024.</li>
<li>Keynote talk on 'Adapting Image and Video Generative Models for 3D Generation' at CVPR'24 workshop on <a href="https://ai3dg.github.io/">AI for 3D Generation</a>, June, 2024.</li>
<li>Keynote talk on 'Reconstructing 3D animals from 2D internet image collections' at CVPR'24 workshop on <a href="https://www.cv4animals.com/">CV4Animals</a>, June, 2024.</li>
<li>Invited talk on '3D of Everything from internet image collections' at ICCV'23 tutorial on <a href="https://sifeiliu.net/NDLM_ICCV23tutorial/">Learning with Noisy and Unlabeled Data</a>, October, 2023.</li>
<li>Guest lecture on '3D from Internet Image Collections' in Deep Learning course, Northeastern University, MA, April, 2023.</li>
<li>Talk on 'Publishing in top vision conferences' at <a href="https://cvit.iiit.ac.in/summerschool2022/">Summer school on AI</a> at IIIT-Hyderabad, August, 2022.</li>
<li><a href="https://www.youtube.com/watch?v=aIgC5izulkk">Talk</a> at <a href="https://cvit.iiit.ac.in/workshops/3dvision/">3D Vision Summer school</a> at IIIT-Hyderabad, May, 2022.</li>
<li><strong>Practical 3D object understanding from image collections and videos</strong>, University of Massachusetts, Amherst, February, 2022.</li>
<li>Guest lecture in 'Advanced Vision' course, University of Edinburgh, February, 2022.</li>
<li>Guest lecture in 'Advanced Topics in Computer Vision' course, UC Merced, September, 2021.</li>
<li>Talk at <a href="https://cvit.iiit.ac.in/summerschool2021/program.php">Summer school on AI</a> at IIIT-Hyderabad, August, 2021.</li>
<li>Guest lecture in 'Advanced Topics in Computer Vision' course, UC Merced, October, 2020.</li>
<li><strong>Self-Supervised Part and Viewpoint discovery from Image Collections</strong>, ECCV Tutorial, August, 2020.</li>	
<li><strong>Content-Adaptive Convolutional Neural Networks</strong>, SPCOM, IISc, Bangalore, July, 2020.</li>
<li><strong>Sparse High-Dimensional Neural Networks</strong>, Machine Intelligence Conference, MIT, Boston, November, 2018.</li>
<li><strong>Bilateral Neural Networks for Image, Video and 3D Vision</strong>, University of Massachusetts, Amherst, October, 2017.</li>
<li><strong>Learning Bilateral Information Propagation across Pixels</strong>, Nvidia Research, Santa Clara, June, 2016.</li>
<li><strong>Learning to Propagate Information across Pixels</strong>, Microsoft Research, Redmond, April, 2016.</li>
<li><strong>Primed Message Passing for Layered Graphical Models</strong>, Microsoft Research, Cambridge, October, 2014.</li>
<li><strong>Inverting Graphic Engines using Informed Samplers</strong>, IIIT-Hyderabad, Hyderabad, December, 2013.</li>
</ul>

<p>&nbsp;</p>
