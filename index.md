---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

> _With four parameters I can fit an elephant, and with five I can make him wiggle his trunk._ --- John Von Neumann


# Differentiable vision, graphics, and physics


“Differentiable programs” are parameterized programs that allow themselves to be rewritten by gradient-based optimization, and are ubiquitous in modern-day machine learning. Over the last 3-4 years, there is an increasingly popular trend of explicitly encoding our knowledge of the rules of the world in the form of differentiable programs. In particular, differentiable realizations of well-studied processes such as physics, rendering, projective geometry, optimization, etc. have enabled the design of several novel learning techniques. For example, a large number of approaches have been proposed for the unsupervised learning of depth estimation from unlabeled videos. Differentiable 3D reconstruction pipelines have demonstrated the potential for task-driven representation learning. A number of differentiable rendering approaches have been shown to enable single-view 3D reconstruction and other inverse graphics approaches (without requiring any form of 3D supervision). Differentiable physics simulators are being built, to perform physical parameter estimation from video, or for model-predictive control. While the aforementioned advances largely occurred in isolation, recent efforts have attempted bridging the gap between the aforementioned areas. To foster synergy across these disciplines, and to provide a common platform for researchers in these areas to discuss the path ahead, and to raise awareness of the potential of these techniques to the community at-large, we propose to organize the “first workshop on differentiable computer vision, graphics, and physics in machine learning”.

The primary focus areas of this workshop are the following:


Differentiable physics simulation methods, 

Interplay of the aforementioned areas. This, in the organizers’ opinion, is the key focus of the workshop. Our “call for papers” will emphasize this fact, and when picking contributed talks, submissions that span two or more of the above areas will be prioritized. Examples of such interplay include, but are not limited to, differentiable renderers with physics-awareness, vision techniques for dynamic scenes (that explicitly factor in the physics of object motion/interaction).

The primary focus areas of this workshop are the following:
1. **Differentiable computer vision techniques**, including, but not limited to, differentiable depth and pose estimation, feature extraction and matching pipelines, image filtering, pointset alignment, reconstruction pipelines, and their applications.
2. **Differentiable geometry processing and graphics** tools, including, but not limited to, differentiable mesh manipulation, rendering, higher-order light transport, and their applications.
3. **Differentiable physics simulation** methods, that innovate either at the implementation level (i.e., differentiable reparameterizations of contact, articulated bodies, collisions, etc.), or at the application level (policy learning, representation learning, physics-informed neural network design, etc.).
4. **Interplay of the aforementioned** areas is the key focus of the workshop. Our “call for papers” will emphasize this fact, submissions that span two or more of the above areas will be prioritized for oral presentation. Examples of such interplay include, but are not limited to, differentiable renderers with physics-awareness, vision techniques for dynamic scenes (that explicitly factor in the physics of object motion/interaction).
5. **Applications and limitations of differentiable methods**. Differentiable physics allows for more efficient model predictive control and system identification. Differentiable graphics and rendering might allow for more accurate novel viewpoint synthesis. However, there are also limitations. Gradients are not always useful, for example, in contact-rich or long-horizon manipulation tasks. Furthermore, differentiable methods are often applicable only where precise process models are available. How can differentiable methods be combined with non gradient-based optimization (or other techniques) to circumvent these issues?


# Confirmed speakers

<table>
    
    <!-- Sanja Fidler -->
    <tr>
        <td>
            <div class="col-xs-2">
                <p align="center">
                    <img class="people-pic" src="assets/img/sanja.jpg">
                </p>
            </div>
        </td>
        <td>
            <div class="people-name text-center">
                <a href="http://www.cs.toronto.edu/~fidler/" target="_blank">Sanja Fidler</a>, <a href="http://www.utoronto.ca" target="_blank">University of Toronto</a>, <a href="https://nv-tlabs.github.io/"> NVIDIA</a>
            </div>
        </td>
    </tr>

    <!-- Peter Battaglia -->
    <tr>
        <td>
            <div class="col-xs-2">
                <p align="center">
                    <img class="people-pic" src="assets/img/peter.jpg">
                </p>
            </div>
        </td>
        <td>
            <div class="people-name text-center">
                <a href="https://scholar.google.com/citations?user=nQ7Ij30AAAAJ&hl=en" target="_blank">Peter Battaglia</a>, <a href="https://deepmind.com/" target="_blank">DeepMind</a>
            </div>
        </td>
    </tr>

    <!-- Andrea Tagliasacchi -->
    <tr>
        <td>
            <div class="col-xs-2">
                <p align="center">
                    <img class="people-pic" src="assets/img/andrea.jpg">
                </p>
            </div>
        </td>
        <td>
            <div class="people-name text-center">
                <a href="http://gfx.uvic.ca/" target="_blank">Andrea Tagliasacchi</a>, <a href="https://ai.google/research/teams/brain/" target="_blank">Google Brain</a>
            </div>
        </td>
    </tr>


</table>


# Organizers

<table style="border-collapse: collapse; border: none;">
    

    <tr style="border: none;">
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
        <td style="border: none;">
        <div class="col-xs-15">
            <a href="https://johannah.github.io/" target="_blank">
              <p align="center">
              <img class="people-pic" src="assets/img/avatar.jpg">
              </p>
            </a>
            <div class="people-name text-center">
              <a href="https://johannah.github.io/" target="_blank">Johanna Hansen</a><br>
              <a href="https://mila.quebec/en/" target="_blank">Mila</a>, <a href="https://mcgill.ca/" target="_blank">McGill</a>
            </div>
        </div>
        </td>

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
