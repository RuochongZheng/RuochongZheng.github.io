---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research is centered on **generative world modeling for embodied intelligence**. I aim to build models that can understand spatial structure, predict future dynamics, and support action-aware interaction in the physical world.

Research Thread
======

**1. Visual generation as a world prior for VLA and embodied agents**

Large-scale visual generation models learn strong priors over objects, scenes, text rendering, and instruction-conditioned visual composition. During my internship at Zhipu AI, I worked on GLM-Image, focusing on autoregressive image generation, model-architecture migration, decoder SFT, and automated evaluation. This gave me hands-on experience with visual tokens, position encodings, multimodal instruction following, and VLM/OCR-based evaluation. I see these capabilities as useful building blocks for VLA systems: synthetic visual data generation, action-conditioned visual prediction, perceptual state modeling, and scalable evaluation.

**2. Predictive-state video world models**

Embodied agents need world models that go beyond fixed-window video clip generation. In StateStream, I explore predictive state modeling: a world model maintains a persistent state that carries rollout-relevant information through long interactions. StateStream uses block-causal attention, a monotone noise hierarchy, and a rolling KV cache to commit generated or observed chunks into a reusable predictive state. This interface supports long-horizon rollout, counterfactual action branching, and online correction from new observations.

**3. 3D scene understanding and interaction**

For embodied intelligence, visual prediction must be grounded in spatial structure. My 3D Gaussian Splatting work studies controllable 3D scene representation and manipulation. iSegMan focuses on interactive region selection and manipulation in 3D Gaussian scenes, while Tune-Your-Style studies intensity-controllable 3D style transfer with cross-view consistency. Together, these projects provide experience in 3D scene representation, spatial grounding, and user/agent-driven scene editing.

**4. Tokenization and structured representations**

Beyond visual data, I am interested in how complex structured worlds can be compressed into reusable tokens and states. BiHiTo studies hierarchical tokenization for all-atom biomolecular structures, mapping biological assembly hierarchies into multi-level discrete codebooks. This project reflects my broader interest in tokenization, representation learning, and architecture design for structured domains.

Long-Term Goal
======

My long-term goal is to connect **visual generation**, **predictive world models**, and **3D world understanding** into models that can serve embodied agents: models that remember interaction history, reason about alternative futures, update beliefs from observations, and ground predictions in 3D structure.
