---
layout: archive
title: "Publications"
permalink: /publications/
description: "Nathan C. Frey's scientific publications on AI drug discovery, foundation models for biology, protein generative models, and machine learning for therapeutic development. Featured work includes ICLR Outstanding Paper on discrete walk-jump sampling for protein discovery, neural scaling of chemical models in Nature Machine Intelligence, and Lab-in-the-Loop autonomous antibody design."
author_profile: true
---

{% include base_path %}

Research at the intersection of machine learning and therapeutic discovery. My work spans autonomous drug design systems, foundation models for proteins, and scalable ML methods for chemistry and biology.

[Full publication list on Google Scholar](https://scholar.google.com/citations?user=IMUja60AAAAJ)

---

## Featured Publications

### Lab-in-the-Loop: Autonomous Therapeutic Antibody Design
{: #lab-in-the-loop}

**Frey, N. C.** (co-lead), et al. (2025). "Lab-in-the-loop therapeutic antibody design with deep learning." *bioRxiv*. doi: 10.1101/2025.02.19.639050

**What it does:** Orchestrates generative ML models, multi-task property predictors, active learning, and in vitro experimentation in an iterative optimization loop. Semi-autonomous antibody design.

**Results:** Applied to four clinically relevant targets (EGFR, IL-6, HER2, OSM). Designed and tested 1,800+ unique antibody variants from leads obtained through animal immunization and immune repertoire mining.

**Impact:** End-to-end automation of antibody optimization - design, property prediction, lab testing. Practical ML-in-the-loop system for therapeutic development.

**Target audience:** Biotech researchers evaluating AI drug discovery, antibody engineers.

[Read paper](https://www.biorxiv.org/content/10.1101/2025.02.19.639050v1)

---

### Protein Discovery with Discrete Walk-Jump Sampling
{: #discrete-walk-jump}

**Frey, N. C.**, Berenberg, D., Zadorozhny, K., et al. (2024). "Protein Discovery with Discrete Walk-Jump Sampling." *International Conference on Learning Representations (ICLR 2024)*. **Outstanding Paper Award** 🏆

**Method:** Combines energy-based and score-based models. Learns smoothed energy function, samples from smoothed data manifold with Langevin MCMC, projects to true data manifold with one-step denoising.

**Results:** 97-100% of generated samples expressed and purified successfully. 70% of functional designs matched or beat known functional antibodies for binding affinity.

**Impact:** Resolves training and sampling difficulties in discrete generative models. Top 1.2% of ICLR submissions (Oral). Introduced distributional conformity score to benchmark protein generative models.

**Target audience:** ML researchers, protein engineers.

[Read paper](https://arxiv.org/abs/2306.12360) | [OpenReview](https://openreview.net/forum?id=zMPHKOmQNb) | [ICLR talk](https://iclr.cc/virtual/2024/oral/19713)

---

### Neural Scaling of Deep Chemical Models

**Frey, N. C.**, Soklaski, R., Axelrod, S., et al. (2023). "Neural scaling of deep chemical models." *Nature Machine Intelligence* 5(11), 1297-1305.

**Study:** First systematic investigation of neural scaling in large chemical models. Trained models with 1B+ parameters on datasets up to 10M molecules. Investigated large language models for generative chemistry and graph neural networks for interatomic potentials.

**Results:** Neural scaling laws hold for chemistry models at massive scale. No plateau in loss improvement. Pre-training loss improved monotonically with dataset size up to 10M molecules and model size up to 1B+ parameters.

**Impact:** Chemistry and biology follow ML scaling laws. Empirical foundation for building foundation models for drug discovery. Published in Nature Machine Intelligence.

**Target audience:** AI for bio researchers, computational chemists

[Read paper](https://www.nature.com/articles/s42256-023-00740-3) | [arXiv](https://chemrxiv.org/engage/chemrxiv/article-details/627bddd544bdd532395fb4b5) | [Code](#)

---

### Protein Design with Guided Discrete Diffusion

Gruver, N., Stanton, S., **Frey, N. C.**, Rudner, T. G., et al. (2023). "Protein Design with Guided Discrete Diffusion." *Advances in Neural Information Processing Systems (NeurIPS 2023)*.

**Method:** Guidance for discrete diffusion models following gradients in hidden states of denoising network. Enables design directly in sequence space, bypassing structure-based method limitations.

**Results:** Applied to antibody optimization for expression yield and binding affinity. 99% expression rate, 40% binding rate in exploratory in vitro experiments under locality and developability constraints.

**Impact:** Makes discrete diffusion practical for protein design. Strong performance with limited edits through novel saliency maps.

**Target audience:** ML researchers, protein designers, biotech researchers building guided generation systems.

[Read paper](https://arxiv.org/abs/2305.20009) | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/29591f355702c3f4436991335784b503-Abstract-Conference.html) | [Code](https://paperswithcode.com/paper/protein-design-with-guided-discrete-diffusion-1)

---

## Selected Additional Publications

**Machine Learning for Materials (2018-2020)**

* **Frey, N. C.**, Horton, M. K., Munro, J. M., Griffin, S. M., Persson, K. A., Shenoy, V. B. (2020). "High-throughput search for magnetic and topological order in transition metal oxides." *Science Advances*.

* **Frey, N. C.**, Akinwande, D., Jariwala, D., Shenoy, V. B. (2020). "Machine Learning-Enabled Design of Point Defects in 2D Materials." *ACS Nano*.

* **Frey, N. C.**, et al. (2019). "Prediction of Synthesis of 2D Metal Carbides and Nitrides (MXenes) with Positive and Unlabeled Machine Learning." *ACS Nano*.

* **Frey, N. C.**, Kumar, H., Anasori, B., Gogotsi, Y., Shenoy, V. B. (2018). "Tuning Noncollinear Spin Structure and Anisotropy in Ferromagnetic Nitride MXenes." *ACS Nano*.

**Deep Learning Infrastructure (2021)**

* **Frey, N. C.**, Samsi, S., Ramsundar, B., Coley, C. W., Gadepally, V. (2021). "Bringing Atomistic Deep Learning to Prime Time." *arXiv:2112.04977*.

* **Frey, N. C.**, Samsi, S., McDonald, J., Li, L., Coley, C. W., Gadepally, V. (2021). "Scalable Geometric Deep Learning on Molecular Graphs." *arXiv:2112.03364*.

---

&dagger; Denotes equal contribution where applicable.
