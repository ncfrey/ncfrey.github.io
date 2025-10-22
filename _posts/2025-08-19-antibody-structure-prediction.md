---
title: 'The Nuances of Antibody Structure Prediction'
date: 2025-08-19
permalink: /posts/2025/08/antibody-structure-prediction/
tags:
  - antibody design
  - structure prediction
  - AlphaFold
  - protein engineering
  - therapeutic antibodies
excerpt: 'Protein structure prediction advanced dramatically, but therapeutic antibody design faces a bottleneck: accurately predicting CDR loops, especially CDR H3, for novel sequences.'
---

## Executive Summary

Protein structure prediction advanced rapidly. Therapeutic antibody design still hits a wall: accurately predicting complementarity-determining regions (CDRs), especially CDR H3. Guest contribution by Frédéric Dreyer examines why general-purpose models fail on novel antibody sequences and what specialized approaches might work.

*Guest post by Frédéric Dreyer, with my commentary.*

## Key Insights

- **CDR H3 loop complexity**: Third heavy chain CDR resists prediction. Sequence diversity and length variability degrade accuracy for novel sequences (RMSD ~4Å for sequences >7 edits from known structures).

- **General model limitations**: AlphaFold and similar tools rely on multiple sequence alignments. Hypervariable regions lack evolutionary signal. Models predict bound conformations by default, creating problems for unbound antibody design.

- **Specialized model advantages**: Immunoglobulin-specific models like Ibex use conformation tokens to distinguish bound (holo) and unbound (apo) states. Generate either on demand.

- **Out-of-distribution performance gap**: Docking quality scores stay low for novel antibody-antigen complexes (DockQ >0.8 indicates near-native reconstruction). Cofolding methods fail on sequences distant from training data.

- **Design bottleneck identified**: Successful antibody design depends on computational screening and accurate interface modeling. Generative capabilities alone don't cut it.

## Who Should Read This

- **AI for bio researchers** working on protein structure prediction and modeling
- **Antibody engineers** designing therapeutic antibodies
- **Biotech researchers** evaluating AI tools for antibody discovery
- **Machine learning scientists** building models for protein design
- **CTOs and R&D leaders** assessing structure prediction capabilities for drug development

## The CDR H3 Problem

CDR loops, especially CDR H3, determine antibody specificity and binding affinity. Their hypervariability makes them the hardest part to predict. Move away from Protein Data Bank (PDB) sequences and prediction quality degrades rapidly.

Therapeutic antibody design requires exploring novel sequence space. Current models struggle there.

## General vs. Specialized Models

**General models (AlphaFold, ESMFold):**
- Trained on entire PDB
- Rely on evolutionary signal from MSAs
- Computationally expensive
- Predict bound conformations by default

**Specialized antibody models (Ibex, IgFold):**
- Trained specifically on immunoglobulin structures
- Use structural patterns learned from antibody-specific data
- More computationally efficient
- Can explicitly model bound vs. unbound states

## The Bound vs. Unbound Challenge

Antibodies change conformation upon binding. General models trained on PDB structures (mostly bound complexes) predict bound conformations for isolated antibodies. You need accurate unbound structures to predict binding.

Specialized models handle this distinction explicitly. Promise shows, but novel sequences still pose problems.

## What This Means for Therapeutic Development

We generate novel antibody sequences easily. Computational screening creates the bottleneck - predicting which designs work before expensive experimental validation.

Current accuracy falls short for high-confidence *in silico* screening of novel therapeutic antibodies. Better tools needed:
1. **Filtering protocols** - Which designs to pursue
2. **Scoring functions** - How to rank candidates
3. **Interface modeling** - Predicting antibody-antigen interactions accurately

## My Perspective

Structure prediction accuracy determines computational antibody design success. We developed lab-in-the-loop approaches because pure *in silico* design fails for novel targets.

The field celebrates generative capabilities. Focus should shift to filtering, scoring, and ranking protocols that determine actual success rates in therapeutic contexts.

**Full article:** [Read on Substack](https://ncfrey.substack.com/p/the-nuances-of-antibody-structure)

## Related Resources

- [Lab-in-the-Loop Autonomous Antibody Design](/publications/#lab-in-the-loop) - Our approach to overcoming structure prediction limitations
- [Foundation Models in Drug Discovery](/publications/) - My research on protein design and generative models
- [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/) - Where computational methods deliver real value

---

*Last updated: August 2025*

**Keywords:** antibody structure prediction, CDR H3 prediction, AlphaFold antibodies, therapeutic antibody design, protein structure prediction limitations, antibody engineering AI, computational antibody design, de novo binder design
