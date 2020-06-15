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
1. **Differentiable computer vision techniques**, including, but not limited to, differentiable depth and pose estimation, feature extraction and matching pipelines, image filtering, pointset alignment, reconstruction pipelines, and their applications.
2. **Differentiable geometry processing and graphics** tools, including, but not limited to, differentiable mesh manipulation, rendering, higher-order light transport, and their applications.
3. **Differentiable physics simulation** methods, that innovate either at the implementation level (i.e., differentiable reparameterizations of contact, articulated bodies, collisions, etc.), or at the application level (policy learning, representation learning, physics-informed neural network design, etc.).
4. **Interplay of the aforementioned** areas. This, in the organizers’ opinion, is the key focus of the workshop.
