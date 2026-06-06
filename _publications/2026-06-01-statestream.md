---
title: "StateStream: Learning Predictive State for Embodied Video World Models"
collection: publications
category: manuscripts
permalink: /publication/2026-06-01-statestream
excerpt: "A predictive-state video world model for embodied long-horizon rollout, action-conditioned future evaluation, and observation-based state updates."
date: 2026-06-01
venue: "Manuscript"
citation: "Ruochong Zheng et al. &quot;StateStream: Learning Predictive State for Embodied Video World Models.&quot; Manuscript, 2026."
---

StateStream recasts embodied video prediction as predictive state modeling. Instead of repeatedly generating from bounded visual windows, the model maintains a persistent state that carries rollout-relevant information through long interactions.

StateStream uses a causal latent flow interface with block-causal attention, a monotone noise hierarchy, and a rolling KV cache that commits generated or observed chunks into a reusable predictive state. The same state supports long-horizon rollout, action-conditioned future evaluation, and observation-based state updates.

On BridgeV2 125/253/381-frame prediction, StateStream improves PSNR by 5.13/4.94/3.84 and SSIM by 0.174/0.222/0.182 over non-streaming baselines.
