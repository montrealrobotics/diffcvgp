---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
title: Home
---

> _With four parameters I can fit an elephant, and with five I can make it wiggle its trunk._ --- John Von Neumann (abridged)


### Differentiable vision, graphics, and physics applied to machine learning


“Differentiable programs” are parameterized programs that allow themselves to be rewritten by gradient-based optimization. They are ubiquitous in modern-day machine learning. Recently,  explicitly encoding our knowledge of the rules of the world in the form of differentiable programs has become more popular. In particular, differentiable realizations of well-studied processes such as physics, rendering, projective geometry, optimization to name a few, have enabled the design of several novel learning techniques. For example, many approaches have been proposed for unsupervised learning of depth estimation [1‒6] from unlabeled videos. Differentiable 3D reconstruction pipelines [7, 8] have demonstrated the potential for task-driven representation learning. A number of differentiable rendering approaches [9‒14] have been shown to enable single-view 3D reconstruction and other inverse graphics tasks (without requiring any form of 3D supervision). Differentiable physics simulators are being built [15‒20] to perform physical parameter estimation from video or for model-predictive control. While these advances have largely occurred in isolation, recent efforts [21‒24] have attempted to bridge the gap between the aforementioned areas. Narrowing the gaps between these otherwise isolated disciplines holds tremendous potential to yield new research directions and solve long-standing problems, particularly in understanding and reasoning about the 3D world.

Hence, we propose the “first workshop on differentiable computer vision, graphics, and physics in machine learning” with the aim of:
* Narrowing the gap and fostering synergies between the computer vision, graphics, physics, and machine learning communities
* Debating the promise and perils of differentiable methods, and identifying challenges that need to be overcome
* Raising awareness about these techniques to the larger ML community
* Discussing the broader impact of such techniques, and any ethical implications thereof.

Notably, most of the advances in our focus areas have occurred in the last 3-4 years, and the interest in this nascent field seems to be increasing (as evident from the push towards the release of open-source tools such as Kaolin [25], PyTorch3D [26], Kornia [27], tiny-differentiable-simulator [28], and more. This workshop aims to bring together researchers from outside the core ML community (such people from the graphics, vision, and physics simulation communities), enabling synergies among them.


## Speakers

<table style="border-collapse: collapse; border: none;">
    <tr style="border: none;">
        <!-- Sanja Fidler -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="http://www.cs.toronto.edu/~fidler/" target="_blank">
            <p align="center">
            <img class="people-pic" src="assets/img/sanja.jpg">
            </p>
            </a>
            <div class="people-name text-center">
                <a href="http://www.cs.toronto.edu/~fidler/" target="_blank">Sanja Fidler</a>, <a href="http://www.utoronto.ca" target="_blank">University of Toronto</a>, <a href="https://nv-tlabs.github.io/"> NVIDIA</a>
            </div>
        </div>
        </td>
        <!-- Peter Battaglia -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://scholar.google.com/citations?user=nQ7Ij30AAAAJ&hl=en" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/peter.jpg">
              </p>
            </a>
            <div class="people-name text-center">
                <a href="https://scholar.google.com/citations?user=nQ7Ij30AAAAJ&hl=en" target="_blank">Peter Battaglia</a>, <a href="https://deepmind.com/" target="_blank">DeepMind</a>
            </div>
        </div>
        </td>
        <!-- Georgia Gkioxari -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://gkioxari.github.io/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/georgia.jpg">
              </p>
            </a>
            <div class="people-name text-center">
                <a href="https://gkioxari.github.io/" target="_blank">Georgia Gkioxari</a>, <a href="https://research.facebook.com/ai/" target="_blank">Facebook AI Research</a>
            </div>
        </div>
        </td>
    </tr>
    <tr style="border: none;">
        <!-- Andrea Tagliasacchi -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="http://gfx.uvic.ca/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/andrea.jpg">
              </p>
            </a>
            <div class="people-name text-center">
                <a href="http://gfx.uvic.ca/" target="_blank">Andrea Tagliasacchi</a>, <a href="https://ai.google/research/teams/brain/" target="_blank">Google Brain</a>
            </div>
        </div>
        </td>
        <!-- Ming Lin -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://www.cs.umd.edu/~lin/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/ming.jpg">
              </p>
            </a>
            <div class="people-name text-center">
                <a href="https://www.cs.umd.edu/~lin/" target="_blank">Ming Lin</a>, <a href="https://www.cs.umd.edu/" target="_blank">University of Maryland</a>
            </div>
        </div>
        </td>
        <!-- Camillo Jose Taylor -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://www.cis.upenn.edu/~cjtaylor/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/camillo.jpg">
              </p>
            </a>
            <div class="people-name text-center">
                <a href="https://www.cis.upenn.edu/~cjtaylor/" target="_blank">Camillo Jose Taylor</a>, <a href="https://www.upenn.edu/" target="_blank">University of Pennsylvania</a>
            </div>
        </div>
        </td>
    </tr>
    <tr style="border: none;">
        <!-- Bethany Lusch -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://www.alcf.anl.gov/about/people/bethany-lusch" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/bethany.jpg">
              </p>
            </a>
            <div class="people-name text-center">
                <a href="https://www.alcf.anl.gov/about/people/bethany-lusch" target="_blank">Bethany Lusch</a>, <a href="https://www.alcf.anl.gov/" target="_blank">Argonne National Lab</a>
            </div>
        </div>
        </td>
        <!-- Yuanming Hu -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="http://taichi.graphics/me/" target="_blank">
                <p align="center">
                <img class="people-pic" src="assets/img/yuanming.jpg">
                </p>
            </a>
            <div class="people-name text-center">
                <a href="http://taichi.graphics/me/" target="_blank">Yuanming Hu</a>, <a href="https://www.mit.edu/" target="_blank">Massachusetts Institute of Technology</a>
            </div>
        </div>
        </td>
    </tr>
</table>



## Organizers

<table style="border-collapse: collapse; border: none;">
    <tr style="border: none;">
        <!-- Krishna -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://krrish94.github.io" target="_blank">
            <p align="center">
            <img class="people-pic" src="assets/img/krishna.jpg">
            </p>
            </a>
            <div class="people-name text-center">
                <a href="https://krrish94.github.io" target="_blank">Krishna Murthy Jatavallabhula</a><br>
                <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://www.umontreal.ca/" target="_blank">UdeM</a>
            </div>
        </div>
        </td>
        <!-- Kelsey -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://web.mit.edu/krallen/www/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/kelsey.png">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="https://web.mit.edu/krallen/www/" target="_blank">Kelsey Allen</a><br>
              <a href="https://www.mit.edu/" target="_blank">Massachusetts Institute of Technology</a>
            </div>
        </div>
        </td>
        <!-- Victoria -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://vdean.github.io/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/victoria.jpg">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="https://vdean.github.io/" target="_blank">Victoria Dean</a><br>
              <a href="https://www.cmu.edu/" target="_blank">Carnegie Mellon University</a>
            </div>
        </div>
        </td>
    </tr>
    <tr style="border: none;">
        <!-- Johanna -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://johannah.github.io/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/johanna.jpg">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="https://johannah.github.io/" target="_blank">Johanna Hansen</a><br>
              <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://mcgill.ca/" target="_blank">McGill</a>
            </div>
        </div>
        </td>
        <!-- Shuran -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://shurans.github.io/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/shuran.jpg">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="https://shurans.github.io/" target="_blank">Shuran Song</a>, <a href="https://www.cs.columbia.edu/" target="_blank">Columbia University</a>
            </div>
        </div>
        </td>
        <!-- Florian -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="http://www.cs.toronto.edu/~florian/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/florian.jpg">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="http://www.cs.toronto.edu/~florian/" target="_blank">Florian Shkurti</a><br>
              <a href="https://vectorinstitute.ai/" target="_blank">Vector institute</a>, <a href="https://www.utoronto.ca/" target="_blank">University of Toronto</a>
            </div>
        </div>
        </td>
    </tr>
    <tr style="border: none;">
        <!-- Liam -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://liampaull.ca/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/liam.png">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="https://liampaull.ca/" target="_blank">Liam Paull</a><br>
              <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://www.umontreal.ca/" target="_blank">Universite de Montreal</a>
            </div>
        </div>
        </td>
        <!-- Derek -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="http://www.cim.mcgill.ca/~derek/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/derek.jpg">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="http://www.cim.mcgill.ca/~derek/" target="_blank">Derek Nowrouzezahrai</a><br>
              <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://mcgill.ca/" target="_blank">McGill</a>
            </div>
        </div>
        </td>
        <!-- Josh -->
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="http://web.mit.edu/cocosci/josh.html" target="_blank">
                <p align="center">
                <img class="people-pic" src="assets/img/josh.jpg">
                </p>
            </a>
            <div class="people-name text-center">
              <a href="http://web.mit.edu/cocosci/josh.html" target="_blank">Josh Tenenbaum</a><br>
              <a href="https://www.mit.edu/" target="_blank">Massachusetts Institute of Technology</a>
            </div>
        </div>
        </td>
    </tr>
</table>


<!-- [Miles Macklin](http://blog.mmacklin.com/): [University of Copenhagen](https://www.ku.dk/english/), [NVIDIA](https://www.nvidia.com/en-us/) -->


<!-- Old format

<div class="row">
  
  <div class="col-xs-2">
    <a href="https://krrish94.github.io" target="_blank">
      <img class="people-pic" src="assets/img/krishna.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://krrish94.github.io" target="_blank">Krishna Murthy Jatavallabhula</a><br>
      <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://www.umontreal.ca/" target="_blank">Universite de Montreal</a>
    </div>
  </div>
  
  <div class="col-xs-2">
    <a href="https://web.mit.edu/krallen/www/" target="_blank">
      <img class="people-pic" src="assets/img/kelsey.png">
    </a>
    <div class="people-name text-center">
      <a href="https://web.mit.edu/krallen/www/" target="_blank">Kelsey Allen</a><br>
      <a href="https://www.mit.edu/" target="_blank">Massachusetts Institute of Technology</a>
    </div>
  </div>
  
  <div class="col-xs-2">
    <a href="https://vdean.github.io/" target="_blank">
      <img class="people-pic" src="assets/img/victoria.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://vdean.github.io/" target="_blank">Victoria Dean</a><br>
      <a href="https://www.cmu.edu/" target="_blank">Carnegie Mellon University</a>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://johannah.github.io/" target="_blank">
      <img class="people-pic" src="assets/img/avatar.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://johannah.github.io/" target="_blank">Johanna Hansen</a><br>
      <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://mcgill.ca/" target="_blank">McGill</a>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://shurans.github.io/" target="_blank">
      <img class="people-pic" src="assets/img/avatar.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://shurans.github.io/" target="_blank">Shuran Song</a>, <a href="https://www.cs.columbia.edu/" target="_blank">Columbia University</a>
    </div>
  </div>

</div>

<div class="row">

  <div class="col-xs-3">
    <a href="http://www.cs.toronto.edu/~florian/" target="_blank">
      <img class="people-pic" src="assets/img/florian.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://www.cs.toronto.edu/~florian/" target="_blank">Florian Shkurti</a><br>
      <a href="https://vectorinstitute.ai/" target="_blank">Vector institute</a>, <a href="https://www.utoronto.ca/" target="_blank">University of Toronto</a>
    </div>
  </div>

  <div class="col-xs-3">
    <a href="https://liampaull.ca/" target="_blank">
      <img class="people-pic" src="assets/img/liam.png">
    </a>
    <div class="people-name text-center">
      <a href="https://liampaull.ca/" target="_blank">Liam Paull</a><br>
      <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://www.umontreal.ca/" target="_blank">Universite de Montreal</a>
    </div>
  </div>

  <div class="col-xs-3">
    <a href="http://www.cim.mcgill.ca/~derek/" target="_blank">
      <img class="people-pic" src="assets/img/derek.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://www.cim.mcgill.ca/~derek/" target="_blank">Derek Nowrouzezahrai</a><br>
      <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://mcgill.ca/" target="_blank">McGill</a>
    </div>
  </div>

  <div class="col-xs-3">
    <a href="http://web.mit.edu/cocosci/josh.html" target="_blank">
      <img class="people-pic" src="assets/img/josh.jpg">
    </a>
    <div class="people-name text-center">
      <a href="http://web.mit.edu/cocosci/josh.html" target="_blank">Josh Tenenbaum</a><br>
      <a href="https://www.mit.edu/" target="_blank">Massachusetts Institute of Technology</a>
    </div>
  </div>

</div>

-->
