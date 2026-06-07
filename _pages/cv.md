---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download PDF CV]({{ site.baseurl }}/files/Ruochong_Zheng_CV.pdf)

Education
======

**Peking University**, M.S. in Computer Science and Technology

School of Electronics Engineering and Computer Science, Shenzhen, China

2024.09 - 2027.06

GPA: 3.79 / 4.0

Research interests: world models, video generation, 3D AIGC, multimodal alignment, and structured tokenization.

**Beijing Jiaotong University**, B.Eng. in Software Engineering

School of Software Engineering, Beijing, China

2020.09 - 2024.06

GPA: 3.27 / 4.0

Research Experience
======

**Zhipu AI / CogVideo & GLM-Image**, Research Intern

2025.11 - 2026.05

- Worked on GLM-Image autoregressive image generation, migrating AR models from a 9B dense architecture to a 30B-A3B MoE backbone and adapting visual vocabulary, 3D RoPE, vision head, tokenizer, position IDs, and training-inference alignment.
- Built an end-to-end image generation evaluation pipeline covering checkpoint submission, AR prior-token generation, decoder inference, OSS cross-cluster synchronization, automatic metrics, and web visualization for 10+ benchmarks and 1000+ prompts.
- Participated in AR SFT and decoder SFT, constructing evaluation sets for knowledge-intensive prompts, long-text rendering, Asian portraits, arXiv/chart data, and automated VLM/OCR-based scoring.
- Iterated decoder SFT through a data-construction, automatic-evaluation, error-analysis, and retraining loop, improving instruction-following VLM score by about 3% and OCR metrics by about 2% over the best checkpoint.

Publications and Projects
======

**StateStream: Learning Predictive State for Embodied Video World Models**

2026.04 - 2026.06

- Proposed predictive state modeling to move embodied video world models from fixed-window clip generation toward stateful prediction over long-horizon interactions.
- Designed a causal latent flow model with block-causal attention, monotone noise hierarchy, and rolling KV cache, enabling long-horizon rollout, action-conditioned future evaluation, and observation-based state updates.
- On BridgeV2 125/253/381-frame prediction, improved PSNR by 5.13/4.94/3.84 and SSIM by 0.174/0.222/0.182 over non-streaming baselines.

**BiHiTo: Biomolecular Hierarchy-inspired Tokenization**, AAAI 2026, first author

2025.05 - 2025.07

- Proposed a hierarchical tokenization framework for all-atom biomolecular structures, mapping proteins, RNA, and small molecules into multi-level discrete codebooks.
- Designed the NHQ module for biologically structured vector quantization, improving OOD generalization; reduced RMSD by 25% on RNA3DB and 51% on FastFolding OOD protein multi-conformation reconstruction compared with Bio2Token.

**BioDynaSpec: Harmonic-Guided Spatio-Spectral Autoregressive Diffusion for Protein Dynamics Generation**, ICML 2026

2026.06

- Studied spatio-spectral generative modeling for long-horizon protein dynamics using harmonic-guided spectral representations and autoregressive diffusion.
- Reduced trajectory error by over 60% on ATLAS, demonstrating the effectiveness of spatio-spectral modeling for protein dynamics generation.

**Tune-Your-Style: Intensity-tunable 3D Style Transfer with Gaussian Splatting**, ICCV 2025

2024.12 - 2025.03

- Studied intensity-controllable 3D style transfer for Gaussian Splatting scenes, balancing content preservation and style strength.
- Designed/participated in Gaussian-neuron style-intensity modeling, learnable style tuning, cross-view diffusion stylization guidance, and two-stage optimization for consistent 3D stylization.

**iSegMan: Interactive Segment-and-Manipulate 3D Gaussians**, CVPR 2025

2024.09 - 2024.11

- Studied interactive 3D Gaussian segmentation and manipulation without scene-specific training.
- Developed/participated in epipolar-guided interaction propagation, visibility-based Gaussian voting, and a manipulation toolbox for precise region control in 3D Gaussian scenes.

Skills
======

PyTorch, distributed training, autoregressive image generation, video world models, 3D Gaussian Splatting, VAE/VQ tokenization, MoE adaptation, tokenizer/position encoding alignment, VLM/OCR evaluation, Python, Linux.
