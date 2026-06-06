---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

Hi there! I am **Ruochong Zheng** (郑若翀), a master's student in Computer Science at **Peking University**. Before that, I received my B.Eng. in Software Engineering from **Beijing Jiaotong University**.

My research interests lie in **generative world modeling for embodied intelligence**. I am interested in building models that learn reusable visual and 3D representations, maintain predictive states over long-horizon interactions, and support action-conditioned future reasoning for embodied agents and VLA systems.

# 🔥 News

- *2026.06*: Working on **StateStream**, a predictive-state video world model for embodied long-horizon prediction.
- *2026.05*: Completed a research internship at **Zhipu AI / GLM-Image**, focusing on AR image generation, decoder SFT, and automatic evaluation.
- *2026.02*: **BiHiTo** appeared in **AAAI 2026** as a first-author work.
- *2025.10*: **Tune-Your-Style** appeared in **ICCV 2025**.
- *2025.06*: **iSegMan** appeared in **CVPR 2025**.

# 🧠 Research Interests

My current research connects three threads:

- **Visual generation as world priors.** I study how large-scale image/video generation models can provide visual priors, synthetic data, instruction-following behavior, and evaluation signals for VLA and embodied agents.
- **Predictive-state world models.** I explore video world models that move beyond fixed-window clip generation toward persistent states for long-horizon rollout, action-conditioned future evaluation, and online state correction.
- **3D scene understanding and interaction.** I work with 3D Gaussian Splatting and controllable scene representations for spatial grounding, interactive segmentation, and 3D-aware generation.

# 📝 Selected Publications and Preprints

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Manuscript 2026</div><img src="{{ site.baseurl }}/images/papers/statestream.png" alt="StateStream" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[StateStream: Learning Predictive State for Embodied Video World Models]({{ site.baseurl }}/publication/2026-06-01-statestream)

**Ruochong Zheng**, et al.

[**Project**]({{ site.baseurl }}/publication/2026-06-01-statestream)

- We recast embodied video prediction as **predictive state modeling**. StateStream uses block-causal attention, a monotone noise hierarchy, and a rolling KV cache to maintain reusable predictive states, supporting long-horizon rollout, action-conditioned future evaluation, and observation-based state updates. On BridgeV2 125/253/381-frame prediction, it improves PSNR by 5.13/4.94/3.84 and SSIM by 0.174/0.222/0.182 over non-streaming baselines.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">AAAI 2026</div><img src="{{ site.baseurl }}/images/papers/bihito.png" alt="BiHiTo" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[BiHiTo: Biomolecular Hierarchy-inspired Tokenization](https://ojs.aaai.org/index.php/AAAI/article/view/40119)

**Ruochong Zheng**, Yutian Liu, Yian Zhao, Zhiwei Nie, Xuehan Hou, Chang Liu, Siwei Ma, Youdong Mao, Jie Chen

[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/40119)

- We propose a hierarchical tokenizer for all-atom biomolecular structures, mapping biological assembly hierarchies into multi-level discrete codebooks. Compared with Bio2Token, BiHiTo reduces RMSD by 25% on RNA3DB and 51% on FastFolding OOD protein multi-conformation reconstruction.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2025</div><img src="{{ site.baseurl }}/images/papers/isegman.png" alt="iSegMan" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[iSegMan: Interactive Segment-and-Manipulate 3D Gaussians](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhao_iSegMan_Interactive_Segment-and-Manipulate_3D_Gaussians_CVPR_2025_paper.pdf)

Yian Zhao, Wanshi Xu, **Ruochong Zheng**, Pengchong Qiao, Chang Liu, Jie Chen

[**Paper**](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhao_iSegMan_Interactive_Segment-and-Manipulate_3D_Gaussians_CVPR_2025_paper.pdf)

- We study interactive 3D Gaussian segmentation and manipulation without scene-specific training. The framework uses epipolar-guided interaction propagation and visibility-based Gaussian voting to map 2D interaction cues into reliable 3D Gaussian regions for precise scene editing.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICCV 2025</div><img src="{{ site.baseurl }}/images/papers/tune-your-style.png" alt="Tune-Your-Style" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Tune-Your-Style: Intensity-tunable 3D Style Transfer with Gaussian Splatting](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhao_Tune-Your-Style_Intensity-tunable_3D_Style_Transfer_with_Gaussian_Splatting_ICCV_2025_paper.pdf)

Yian Zhao, Rushi Ye, **Ruochong Zheng**, Zesen Cheng, Chaoran Feng, Jiashu Yang, Pengchong Qiao, Chang Liu, Jie Chen

[**Paper**](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhao_Tune-Your-Style_Intensity-tunable_3D_Style_Transfer_with_Gaussian_Splatting_ICCV_2025_paper.pdf)

- We study intensity-controllable 3D style transfer for Gaussian Splatting scenes. The method models style strength with Gaussian neurons and a learnable style tuner, then uses cross-view diffusion stylization guidance and two-stage optimization for consistent 3D stylization.
</div>
</div>

# 💻 Internships

- *2025.11 - 2026.05*, **Research Intern**, Zhipu AI / CogVideo & GLM-Image, Shenzhen, China. Worked on AR image generation model migration, decoder SFT, automatic evaluation, VLM/OCR scoring, and web-based benchmark visualization for GLM-Image.

# 📖 Educations

- *2024.09 - 2027.06*, M.S. in Computer Science and Technology, Peking University, Shenzhen, China.
- *2020.09 - 2024.06*, B.Eng. in Software Engineering, Beijing Jiaotong University, Beijing, China.

# 🎖 Honors and Awards

- Academic Scholarship, Beijing Jiaotong University.
- Beijing municipal award, China College Students' Innovation and Entrepreneurship Competition.

# 📄 CV

My latest CV is available [here]({{ site.baseurl }}/files/Ruochong_Zheng_CV.pdf).
