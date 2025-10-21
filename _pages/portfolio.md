---
layout: archive
title: "Portfolio"
permalink: /portfolio/
description: "Nathan C. Frey's open-source projects in AI drug discovery, protein language models, and materials informatics. Featured projects: LOBSTER (biological sequence models), Walk-Jump Sampling (protein discovery)."
author_profile: true
---

{% include base_path %}

View all projects on [GitHub](https://github.com/ncfrey)

I build open-source tools and libraries for AI-driven scientific discovery. My projects span drug discovery systems, protein language models, generative modeling for therapeutics, and materials informatics.

---

## Featured Projects: AI for Drug Discovery

### LOBSTER - Language Models for Biological Sequences
**Repository:** [prescient-design/lobster](https://github.com/prescient-design/lobster)
**Status:** Active development • Apache 2.0 License
**Technologies:** Python, PyTorch, Hugging Face, Flash Attention

#### Overview

LOBSTER (Language models for Biological Sequence Transformation and Evolutionary Representation) is an open-source library for training and deploying protein language models from scratch. Developed at Genentech's Prescient Design, it enables researchers to build custom foundation models with full control over training data and embedding spaces.

#### Key Capabilities

**Pre-trained Models:**
- 24M and 150M parameter masked language models (BERT-style)
- Concept Bottleneck variants (24M-3B parameters) with 718 interpretable protein concepts
- Encoder-only and decoder-only (Llama-style) architectures
- Available on Hugging Face model hub

**Core Features:**
- **Rapid Training:** Optimized for fast protein language model training (24 GPU hours)
- **Multi-Modal Support:** Handles proteins, DNA, cDNA, and SMILES sequences
- **Concept Bottleneck Models:** CB-LOBSTER enables interpretable protein design through concept interventions
- **Reinforcement Learning:** UME-based reward functions for post-training optimization
- **MCP Integration:** Model Context Protocol support for Claude Desktop and Cursor
- **Production-Ready:** Embedding extraction, naturalness scoring, linear probing, classification heads

#### Research Impact

Based on peer-reviewed research published in 2024:
- **"Cramming Protein Language Model Training in 24 GPU Hours"** (bioRxiv 2024)
- **"Concept Bottleneck Language Models For protein design"** (arXiv 2411.06090)

LOBSTER addresses a critical gap in drug discovery: the ability to rapidly iterate on protein language models tailored to specific therapeutic applications. By enabling customizable training, it allows biotech companies and research labs to build foundation models optimized for their target space without relying solely on general-purpose models like ESM.

#### Applications in Drug Discovery

- **Antibody Design:** Embedding-based optimization for therapeutic antibodies
- **Protein Engineering:** Concept-guided sequence modifications for improved properties
- **Screening & Filtering:** Naturalness scoring to prioritize synthesizable candidates
- **Interpretable Design:** Concept bottlenecks enable biologists to understand and control model decisions
- **Multi-Task Learning:** Integration with cortex framework for combining multiple objectives

#### Who Should Use This

- **Biotech ML Engineers** building custom protein language models
- **Drug Discovery Scientists** needing interpretable sequence optimization
- **AI Researchers** exploring foundation models for biology
- **Computational Biologists** requiring fast iteration on specialized models

**Links:**
- [GitHub Repository](https://github.com/prescient-design/lobster)
- [Documentation](https://github.com/prescient-design/lobster#readme)

---

### Walk-Jump Sampling - Protein Discovery System
**Repository:** [prescient-design/walk-jump](https://github.com/prescient-design/walk-jump)
**Status:** Active • Apache 2.0 License • 58 stars
**Technologies:** Python, Hydra, PyTorch

#### Overview

Official implementation of discrete Walk-Jump Sampling (dWJS), a novel generative modeling approach for protein discovery and therapeutic design. Recognized with the **ICLR 2024 Outstanding Paper Award** (1 of 5 from 7,300+ submissions), this work represents a fundamental advance in discrete sampling methods for biological sequences.

#### Key Features

**Sampling Pipeline:**
- `walkjump_train`: Train generative models on protein datasets
- `walkjump_sample`: Generate new sequences with configurable parameters
- Hydra-based configuration for reproducible experiments
- Support for antibodies, enzymes, and other large molecules

**Evaluation Framework:**
- **Distributional Conformity Score (DCS):** Measures sample quality vs. training distribution
- **Wasserstein Distance:** Quantifies distribution matching
- **Large Molecule Descriptors:** Computes biophysical properties (charge, hydrophobicity, structure)
- **Comparative Benchmarking:** Built-in tools for method comparison

#### Research Foundation

**Publication:** "Protein Discovery with Discrete Walk-Jump Sampling"
**Authors:** Nathan C. Frey, Daniel Berenberg, Karina Zadorozhny, Joseph Kleinhenz, et al.
**Citation:** arXiv:2306.12360 (2023)
**Recognition:** ICLR 2024 Outstanding Paper Award

#### Why This Matters

Generative modeling for proteins faces a fundamental challenge: sequences are discrete, but most generative methods (VAEs, GANs, standard diffusion) assume continuous spaces. Walk-Jump Sampling operates natively in discrete space while maintaining the sampling quality of continuous methods. This makes it particularly suited for therapeutic protein design where sequence validity is critical.

#### Who Should Use This

- **Computational Biologists** working on protein design
- **AI Drug Discovery Teams** building generative pipelines
- **Research Scientists** benchmarking sampling methods
- **ML Engineers** implementing discrete generative models

**Links:**
- [GitHub Repository](https://github.com/prescient-design/walk-jump)
- [Paper (arXiv)](https://arxiv.org/abs/2306.12360)
- [Related Publication](/publications/)

---

**Keywords:** protein language models, generative protein design, AI drug discovery tools, walk-jump sampling, discrete diffusion, antibody design software, materials informatics, graph neural networks, semi-supervised learning, topological materials, open source drug discovery, foundation models biology, therapeutic protein engineering

