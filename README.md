# DeepSeek Under the Hood

### DeepSeek From Scratch Workshop | Mathematics, Architecture & PyTorch

**DeepSeek Under the Hood** is a collection of learning resources, mathematical explanations, code implementations, and workshop materials created for the **DeepSeek From Scratch Workshop** by **Ananda Rimal (AI Researcher)**.

The goal is to understand **how DeepSeek works internally**—not just how to use the model. We explore the mathematics, architectural decisions, and training techniques behind DeepSeek, then implement key ideas **from scratch using PyTorch**.

## What This Repository Covers

- **Transformer foundations:** Token embeddings, attention, normalization, positional encoding, and feed-forward networks.
- **The mathematics of DeepSeek:** Equations, step-by-step derivations, tensor shapes, and intuition behind each major component.
- **Multi-head Latent Attention (MLA):** Low-rank key/value representations and efficient attention.
- **DeepSeekMoE:** Routed and shared experts, expert selection, and load balancing.
- **DeepSeek-V3:** Architectural components, multi-token prediction, and training-efficiency ideas.
- **DeepSeek-R1:** Reasoning-oriented post-training, reinforcement learning, and Group Relative Policy Optimization (GRPO).
- **Hands-on PyTorch:** Small, readable implementations designed to connect the mathematics to working code.

> **Learning approach:** Understand the intuition → derive the mathematics → implement in PyTorch → test and experiment.

## Who Is This For?

ML engineers, AI researchers, students, and developers who want to move beyond using pretrained models and develop a deeper understanding of modern large language model architectures.

## Primary Papers

- [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://arxiv.org/abs/2405.04434)
- [DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437)
- [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)

## Special Thanks

Special thanks to **Dr. Raj Dandekar** and the **Vizuara team** for their educational books and learning resources. Their work has been a valuable source of inspiration for studying the mathematics and engineering behind modern AI systems.

## About the Workshop

**Instructor:** Ananda Rimal — AI Researcher  
**Workshop:** DeepSeek From Scratch  
**Focus:** Mathematics · Model Architecture · Training · PyTorch Implementations

## Disclaimer

This is an **independent educational repository**, not an official DeepSeek implementation or an affiliated DeepSeek project. The examples are intended for learning and may simplify production-scale systems.

---

**Learn the math. Understand the architecture. Build it from scratch.**