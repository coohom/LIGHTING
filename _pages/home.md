---
layout: project
urltitle: "Data-driven-Digital-Lighting-Design-for-Residential-Indoor-Spaces"
title: "Data-driven-Digital-Lighting-Design-for-Residential-Indoor-Spaces"
categories: computer graphics, machine learning, system
permalink: /
---
<style> 
.center{text-align:center} 
</style> 

<br>
<div class="row">
  <div class="col-xs-12">
    <center>
      <h2>Data-driven Digital Lighting Design for Residential Indoor Spaces</h2>
    </center>
    <br>
    <center>
      Haocheng Ren<sup>1</sup>,
      Hangming Fan<sup>1</sup>,
      <a href="http://www.cad.zju.edu.cn/home/rwang/">Rui Wang</a><sup>1</sup>,
      <a href="http://www.cad.zju.edu.cn/home/huo/">Yuchi Huo</a><sup>1,2</sup>,
      <a href="http://scholar.google.com/citations?user=dwvfKSkAAAAJ&hl=en">Rui Tang</a><sup>3</sup>,
      Lei Wang<sup>4</sup>,
      <a href="http://www.cad.zju.edu.cn/home/bao/">Hujun Bao</a><sup>1</sup>,
    </center>
    <br>
    <center>
      <sup>1</sup>State Key Laboratory of CAD &amp; CG, Zhejiang University,
      <sup>2</sup>Zhejiang Lab,
      <sup>3</sup>KooLab, Manycore Tech Inc.
      <sup>4</sup>RaysEngine Tech Inc.
    </center>
    <br>
    <!-- <center>
      (*: Equal Contribution)
    </center>
    <br> -->
    <center>
      <!-- <a href='https://arxiv.org/abs/2107.06149'>arXiv</a> | <a href="{{ "/static/pdf/supp.pdf" | prepend:site.baseurl }}">Supp</a> | <a href='https://www.kujiale.com/coohomcloud/minervas'>Online System</a> | <a href="https://coohom.github.io/cloud-docs/">Doc</a> -->
      <a href="{{ "/static/pdf/paper.pdf" | prepend:site.baseurl }}">Paper</a> | <a href="{{ "/static/pdf/supp.pdf" | prepend:site.baseurl }}">Supp</a> | <a href='https://coohom.github.io/MINERVAS/'>Dataset</a>
    </center>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <img src="{{ "/static/img/teaser.png" | prepend:site.baseurl }}">
  </div>
</div><br>

<!-- <div class="row" id="news">
  <div class="col-xs-12">
    <h2>News</h2>
  </div>
</div> -->

<!-- <div class="row">
  <div class="col-xs-12">
    <ul>
      <li>2022-08: The MINERVAS System is accepted to Computer Graphics Forum, Pacific Graphics 2022!</li>
      <li>2021-07: The MINERVAS System is available online!</li>
    </ul>
  </div>
</div><br> -->


<div class="row" id="abstract">
  <div class="col-xs-12">
    <h2>Abstract</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <p>
      <!-- <center><iframe width="900" height="500" src="https://www.youtube.com/embed/wUUINjbLNG0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center> -->
      <!-- <center><iframe width="900" height="500" src="https://www.youtube.com/embed/sAr4AYdpdrU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center> -->
      <center><iframe width="900" height="500" src="https://www.youtube.com/embed/Pxz3iSuNHDs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
    </p>
    <p>
      Conventionally, interior lighting design is technically complex yet challenging and requires professional knowledge and aesthetic disciplines of designers. This article presents a new digital lighting design framework for virtual interior scenes, which allows novice users to automatically obtain lighting layouts and interior rendering images with visually pleasing lighting effects. The proposed framework utilizes neural networks to retrieve and learn underlying design guidelines and the principles beneath the existing lighting designs, e.g., a newly constructed dataset of 6k 3D interior scenes from professional designers with dense annotations of lights. With a 3D furniture-populated indoor scene as the input, the framework takes two stages to perform lighting design: (1) lights are iteratively placed in the room; (2) the colors and intensities of the lights are optimized by an adversarial scheme, resulting in lighting designs with aesthetic lighting effects. Quantitative and qualitative experiments show that the proposed framework effectively learns the guidelines and principles and generates lighting designs that are preferred over the rule-based baseline and comparable to those of professional human designers.
    </p>
  </div>
</div><br>

<!-- <div class="row">
  <div class="col-xs-12">
    <h2>Online System</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <p>
      We provide a free trial account for each user with the limited scene and machine time, you can sign up <a href='https://www.kujiale.com/coohomcloud/minervas#/register'>here</a>. If you would like to use our system for research purposes, please send the <a href="{{ "/static/pdf/tos.pdf" | prepend:site.baseurl }}">Terms of Use</a> to <a href="mailto:minervas@qunhemail.com" class="email" data-animate-hover="shake" data-animate="fadeInUp">MINERVAS Group<i class="fa fa-envelope"></i></a>. Once receiving the agreement form, our group will contact you.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-xs-12">
    <h2>DSL Examples</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <p>
      MINERVAS system allows users to control the data generation pipeline via Domain Specific Language (DSL). The DSL is designed with flexibility and ease of use. For flexibility, we build our DSL as an internal DSL under the Python programming language. For ease of use, we provide several common samplers for users to easily generate diverse scenes for domain randomization.
    </p>
    <p>
      Here we show some examples of our DSL and generated results. We only show the built-in samplers here. For more information about DSL, please refer to <a href='https://coohom.github.io/cloud-docs/'>Document</a>.
    </p>
  </div>
</div><br> -->


<!-- **** Furniture arrangement sampler *** -->
<!-- <div class="center">
  <div class="col-xs-12">
    <h3>Furniture Rearrangment</h3>
  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/styles/atom-one-light.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/highlight.min.js"></script>
<script>hljs.highlightAll();</script>
<pre><code class="python">class FurnitureLayoutSampler(SceneProcessor):
  def process(self):
      for room in self.shader.world.rooms:
          room.randomize_layout(self.shader.world)
</code></pre>

<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:600px">
  <img class="mySlides" src="{{ '/static/img/samples/Layout_0.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides" src="{{ '/static/img/samples/Layout_1.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides" src="{{ '/static/img/samples/Layout_2.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides" src="{{ '/static/img/samples/Layout_3.jpg' | prepend:site.baseurl }}" style="width:100%">
</div>

<script type="text/javascript" src="{{ '/static/js/slideshow.js' | prepend:site.baseurl }}"></script>
<script>
carousel("mySlides", 0);
</script>

<!-- **** Material sampler *** -->
<!-- <div class="center">
  <div class="col-xs-12">
    <h3>Material Sampler</h3>
  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/styles/atom-one-light.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/highlight.min.js"></script>
<script>hljs.highlightAll();</script>
<pre><code class="python">class MaterialSampler(EntityProcessor):
    def process(self):
        for instance in self.shader.world.instances:
            if instance.label in [247, 894]: # 247: 'chair', 894: 'desk'
                self.shader.world.replace_material(id=instance.id)
</code></pre>

<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:600px">
  <img class="mySlides2" src="{{ '/static/img/samples/Material_4.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides2" src="{{ '/static/img/samples/Material_6.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides2" src="{{ '/static/img/samples/Material_7.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides2" src="{{ '/static/img/samples/Material_8.jpg' | prepend:site.baseurl }}" style="width:100%">
</div>

<script>
carousel("mySlides2", 0);
</script> -->

<!-- **** Light sampler *** -->
<!-- <div class="center">
  <div class="col-xs-12">
    <h3>Light Sampler</h3>
  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/styles/atom-one-light.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/highlight.min.js"></script>
<script>hljs.highlightAll();</script>
<pre><code class="python">class LightSampler(EntityProcessor):
    def process(self):
        for light in self.shader.world.lights:
            light._tune_temp(1) # randomize color temperature
            light.tune_intensity(1) # randomize intensity
            light.tune_random(1.2) # randomize intensity
</code></pre>

<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:600px">
  <img class="mySlides3" src="{{ '/static/img/samples/Light_1.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides3" src="{{ '/static/img/samples/Light_2.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides3" src="{{ '/static/img/samples/Light_3.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides3" src="{{ '/static/img/samples/Light_4.jpg' | prepend:site.baseurl }}" style="width:100%">
</div>

<script>
carousel("mySlides3", 0);
</script> -->


<!-- **** Model sampler *** -->
<!-- <div class="center">
  <div class="col-xs-12">
    <h3>Model Sampler</h3>
  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/styles/atom-one-light.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/highlight.min.js"></script>
<script>hljs.highlightAll();</script>
<pre><code class="python">class ModelSampler(EntityProcessor):
    def process(self):
        for instance in self.shader.world.instances:
            if instance.type == 'ASSET':
                self.shader.world.replace_model(id=instance.id)
</code></pre>

<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:600px">
  <img class="mySlides4" src="{{ '/static/img/samples/Model_0.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides4" src="{{ '/static/img/samples/Model_1.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides4" src="{{ '/static/img/samples/Model_16.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides4" src="{{ '/static/img/samples/Model_14.jpg' | prepend:site.baseurl }}" style="width:100%">
</div>

<script>
carousel("mySlides4", 0);
</script> -->

<!-- **** Depth sampler *** -->
<!-- <div class="center">
  <div class="col-xs-12">
    <h3>Depth sampler</h3>
  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/styles/atom-one-light.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/highlight.min.js"></script>
<script>hljs.highlightAll();</script>
<pre><code class="python">class DepthNoiseSample(PixelProcessor):
    def process(self):
        # 0: NoNoiseModel
        # 1: GaussianNoiseModel
        # 2: PoissonNoiseModel
        # 3: SaltAndPepperNoiseModel
        # 4: KinectNoiseModel
        self.gen_depth(noise=4)
</code></pre>

<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:600px">
  <img class="mySlides5" src="{{ '/static/img/samples/depth.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides5" src="{{ '/static/img/samples/depth_Kinect.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides5" src="{{ '/static/img/samples/depth_Gaussian.jpg' | prepend:site.baseurl }}" style="width:100%">
  <img class="mySlides5" src="{{ '/static/img/samples/depth_Poisson.jpg' | prepend:site.baseurl }}" style="width:100%">
</div>

<script>
carousel("mySlides5", 0);
</script>
<br> -->

<div class="center">
  <div class="col-xs-12">
    <h3>Visual Results</h3>
  </div>
</div>


<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:1200px">
  <img class="mySlides5" src="{{ '/static/img/results1.png' | prepend:site.baseurl }}" style="width:100%">
</div>

<script>
carousel("mySlides0", 0);
</script>
<br>

<div class="center">
  <div class="col-xs-12">
    <h3>Free-view Walk-through</h3>
  </div>
</div>


<link rel="stylesheet" href="{{ '/static/css/w3.css' | prepend:site.baseurl }}">
<div class="w3-center w3-content w3-section" style="max-width:1200px">
  <img class="mySlides5" src="{{ '/static/img/results2.png' | prepend:site.baseurl }}" style="width:100%">
</div>

<script>
carousel("mySlides1", 0);
</script>
<br>




<div class="row">
  <div class="col-xs-12">
    <h2>Acknowledgements</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <p>
      We would like to thank all reviewers for their insightful comments. We also thank Jialin Huang, Bing Xu for preparing the dataset and helpful discussions, Jacob Si for preparing the video, Yunjin Zhang for proofreading the article, and all participants in our perceptual studies.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-xs-12">
    <h2>Citation</h2>
  </div>
</div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/styles/atom-one-light.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.0.1/highlight.min.js"></script>
<!-- <script>hljs.highlightAll();</script> -->
<pre><code class="text">
@article{10.1145/3582001,
author = {Ren, Haocheng and Fan, Hangming and Wang, Rui and Huo, Yuchi and Tang, Rui and Wang, Lei and Bao, Hujun},
title = {Data-Driven Digital Lighting Design for Residential Indoor Spaces},
year = {2023},
issue_date = {June 2023},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {42},
number = {3},
issn = {0730-0301},
url = {https://doi.org/10.1145/3582001},
journal = {ACM Trans. Graph.},
doi = {10.1145/3582001},
month = {mar},
articleno = {28},
numpages = {18},
keywords = {Lighting design, neural network, interior design, deep learning, data-driven approach}
}
</code></pre>

<hr>
