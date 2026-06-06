---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a master's student in Computer Science at Peking University, working on visual generation, 3D vision, and world modeling. My research interest lies in **generative world modeling for embodied intelligence**: building models that can learn reusable visual and 3D representations, maintain predictive states over long-horizon interactions, and support action-conditioned future reasoning for embodied agents and VLA systems.

My current work connects three complementary threads:

- **Visual generation as world priors.** During my internship at Zhipu AI, I worked on GLM-Image, an autoregressive image generation foundation model, with experience in model migration, visual token interfaces, training-inference alignment, SFT data iteration, and automated evaluation. I am interested in how large-scale visual generation can support visual priors, synthetic data, instruction following, and evaluation for VLA and embodied agents.
- **Video world models for embodied prediction.** In StateStream, I study predictive state modeling for embodied video world models, moving beyond fixed-window clip generation toward persistent states that support long-horizon rollout, action-conditioned future evaluation, and observation-based state updates.
- **3D scene understanding and interaction.** Through 3D Gaussian Splatting projects such as iSegMan and Tune-Your-Style, I explore interactive 3D segmentation, controllable scene editing, cross-view consistency, and 3D-aware generation.

Before joining Peking University, I received my B.Eng. in Software Engineering from Beijing Jiaotong University. I am broadly excited about world models, video generation, 3D AIGC, multimodal agents, and representation learning.

News
======

- **2026.06:** Working on StateStream, a predictive-state video world model for embodied long-horizon prediction.
- **2026.05:** Completed research internship at Zhipu AI on GLM-Image AR-decoder training and evaluation.
- **2026.02:** BiHiTo appeared in AAAI 2026.
- **2025.10:** Tune-Your-Style appeared in ICCV 2025.
- **2025.06:** iSegMan appeared in CVPR 2025.

Selected Work
======

**StateStream: Learning Predictive State for Embodied Video World Models**

Predictive state modeling for embodied video world models, supporting long-horizon rollout, action-conditioned future evaluation, and observation-based state updates.

**BiHiTo: Biomolecular Hierarchy-inspired Tokenization**

AAAI 2026, first author. A hierarchical tokenizer for all-atom biomolecular structures that maps biological assembly hierarchies into multi-level discrete codebooks.

**iSegMan: Interactive Segment-and-Manipulate 3D Gaussians**

CVPR 2025. Interactive 3D Gaussian segmentation and manipulation through epipolar-guided interaction propagation and visibility-based voting.

**Tune-Your-Style: Intensity-tunable 3D Style Transfer with Gaussian Splatting**

ICCV 2025. Intensity-controllable 3D style transfer for Gaussian Splatting scenes with cross-view consistent stylization.

[View publications]({{ site.baseurl }}/publications/) · [View CV]({{ site.baseurl }}/cv/) · [Download CV]({{ site.baseurl }}/files/Ruochong_Zheng_CV.pdf)
