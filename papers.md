---
layout: page
title: Papers
---

### 2026

**Yang Liu**, Toan Nguyen, Flora D. Salim. *"CP-MoE: Consistency-Preserving Mixture-of-Experts for Continual Learning."* arXiv:2605.20247, 2026. [[arXiv](https://arxiv.org/abs/2605.20247)]

A continual learning framework for LLMs and VLMs that introduces a transient expert to capture early task-specific updates and guide their integration into stable experts. Uses a consistency-preserving routing bias based on representation similarity, along with selective regularization to protect important historical parameters during merging. Achieves state-of-the-art on SuperNI (zero-shot transfer) and VQA v2 (reduced forgetting over MoE baselines).

---

Toan Nguyen, **Yang Liu**, Celso De Melo, Flora D. Salim. *"Hypertokens: Controlling Token Dynamics for Continual Video–Language Understanding."* arXiv:2603.06662, 2026. [[arXiv](https://arxiv.org/abs/2603.06662)]

A transformer-based token generator that produces fine-tuning tokens on demand with fixed memory cost for continual VideoQA. Introduces meta-inspired regularization connected to sharpness-aware optimization to encourage flatter cross-task minima and improve retention. Leverages lightweight multimodal supervision with mutual-information losses to regularize cross-modal relationships. Achieves superior accuracy with reduced forgetting on continual VideoQA benchmarks.

---

Toan Nguyen, **Yang Liu**, Trung Le, Celso De Melo, Flora D. Salim. *"FOGO: Forgetting-aware Orthogonalization Optimizer."* arXiv:2606.10406, 2026. [[arXiv](https://arxiv.org/abs/2606.10406)]

An optimizer that addresses short-term knowledge loss caused by gradient suppression during standard training. Uses spectral orthogonalization of momentum updates and a compact codebook memory via random projection to resolve conflicts between current and stored gradient directions. Demonstrates improved convergence and retention over Adam and Muon across class-imbalanced classification, continual visual learning, LLaVA-7B fine-tuning, and GPT-2 pretraining.
