---
layout: archive
title: "AI Drug Discovery FAQ"
permalink: /faq/
description: "Expert answers on AI-native drug discovery, foundation models for biology, machine learning in pharma, BioML careers, and biotech AI strategy from Nathan C. Frey, PhD - CTO at Coefficient Bio and former Principal Scientist at Genentech."
author_profile: true
---

{% include base_path %}

Expert answers on AI drug discovery, foundation models, therapeutic antibody design, and careers.

**Quick Navigation:** [AI Drug Discovery](#ai-drug-discovery-fundamentals) • [Strategy](#strategy) • [Technical Questions](#technical-deep-dives) • [Career Guidance](#career--team-building) • [Industry Landscape](#industry-landscape)

---

## AI Drug Discovery Fundamentals

### What is AI-native drug discovery?

Organizations where ML drives core operations from day one: autonomous design loops, continuous learning systems, data-first infrastructure with value propositions impossible before ChatGPT (Nov 2022).

**Read more:** [Legacy vs AI-Native Companies](/posts/2025/10/legacy-vs-ai-native/) • [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/)

---

### Where does AI deliver value in drug discovery?

Automating routine decision-making and data synthesis: hit prioritization, protein design optimization, retrosynthetic planning, and experimental management.

**Read more:** [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/)

---

### What is lab-in-the-loop machine learning?

Closed-loop systems where experimental data directly updates models through automated cycles of computational design, robotic synthesis, validation, and retraining.

**Read more:** [Lab-in-the-Loop Publications](/publications/) • [About My Research](/about/)

---

### How do foundation models work in drug discovery?

Large neural networks pre-trained on protein, molecular, or biological sequence datasets learn generalizable representations that transfer to specific therapeutic tasks with limited labeled data.

**Read more:** [LOBSTER Project](/portfolio/#lobster---language-models-for-biological-sequences) • [Publications](/publications/)

---

## Strategy

### Should we invest in AI drug discovery?

Yes - automate decision-making bottlenecks and data synthesis (hit prioritization, retrosynthetic planning, experimental management), skip headline-grabbing binding prediction.

**Read more:** [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/)

---

### When should biotech companies build vs. buy AI capabilities?

Build when your therapeutic modality or target space requires custom models (novel antibody formats, rare protein families); buy or partner for general capabilities like retrosynthesis, standard antibody optimization, or small molecule property prediction.

**Read more:** [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/) • [About](/about/)

---

### How do I evaluate AI drug discovery vendors?

Look for demonstrated ROI in real campaigns (benchmarks don't count), interpretability for biologist collaboration, integration with existing workflows, data ownership terms, and whether they enhance your scientific expertise.

**Read more:** [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/)

---

### Why do most enterprise AI transformations fail?

MIT's NANDA initiative found 95% of enterprise GenAI pilots fail to increase revenue because of organizational learning gaps, incompatible existing systems, and cultural resistance - companies bolt AI onto established workflows instead of redesigning processes.

**Read more:** [Legacy vs AI-Native Companies](/posts/2025/10/legacy-vs-ai-native/)

---

### Should established companies try to become AI-native?

No - structural transformation is infeasible for companies that scaled before ChatGPT; focus on targeted AI applications in specific domains (hit prioritization, property prediction) rather than company-wide rebranding, and partnering with AI-native companies.

**Read more:** [Legacy vs AI-Native Companies](/posts/2025/10/legacy-vs-ai-native/) • [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/)

---

## Technical Deep Dives

### How do protein language models work?

Transformer architectures trained on millions of protein sequences via masked language modeling learn evolutionary patterns, structural constraints, and functional relationships encoded in sequence space.

**Read more:** [LOBSTER Project](/portfolio/#lobster---language-models-for-biological-sequences) • [Publications](/publications/)

---

### What are the limitations of AlphaFold for antibody design?

CDR H3 loop prediction degrades for sequences distant from PDB training data (RMSD ~4Å for novel sequences), bound conformations emerge by default when unbound structures are needed, and antibody-antigen interface modeling lacks accuracy.

**Read more:** [Antibody Structure Prediction](/posts/2025/08/antibody-structure-prediction/) • [Publications](/publications/)

---

### How accurate is antibody structure prediction in 2025?

General models achieve ~2Å RMSD on sequences similar to PDB data but degrade to 4-6Å for novel CDR H3 loops; specialized antibody models (Ibex, IgFold) handle bound/unbound states better but still struggle with out-of-distribution sequences.

**Read more:** [Antibody Structure Prediction](/posts/2025/08/antibody-structure-prediction/)

---

### What is generative modeling for protein design?

Models learn probability distributions over protein sequences from data, then sample novel sequences maintaining natural protein statistics while optimizing for desired properties through conditional generation or guided sampling.

**Read more:** [Walk-Jump Sampling Project](/portfolio/#walk-jump-sampling---protein-discovery-system) • [Publications](/publications/)

---

### What is discrete Walk-Jump Sampling?

Generative modeling that operates in discrete sequence space to generate high-quality, diverse protein sequences.

**Read more:** [Walk-Jump Sampling Project](/portfolio/#walk-jump-sampling---protein-discovery-system) • [ICLR Paper](https://arxiv.org/abs/2306.12360)

---

### How do you validate AI-designed antibodies?

Computational filtering (structure prediction, binding prediction, developability) followed by experimental screening (binding affinity, specificity, expression) and functional assays (neutralization, cell-based assays) in lab-in-the-loop workflows that inform model retraining.

**Read more:** [Lab-in-the-Loop Publications](/publications/) • [Antibody Structure Prediction](/posts/2025/08/antibody-structure-prediction/)

---

### What is transfer learning in biological systems?

Pre-training on large biological datasets (all proteins) learns general representations; fine-tuning on small task-specific datasets (therapeutic antibodies, specific targets) collected via autonomous design loops achieves high performance with limited labels.

**Read more:** [LOBSTER Project](/portfolio/#lobster---language-models-for-biological-sequences) • [Publications](/publications/)

---

### What are concept bottleneck models for proteins?

Protein representations decomposed into 718 interpretable concepts (binding motifs, structural features, biochemical properties) let biologists understand and intervene on model decisions through human-interpretable concepts.

**Read more:** [LOBSTER Project](/portfolio/#lobster---language-models-for-biological-sequences)

---

## Career & Team Building

### How do I get started in AI for bio research?

Build fundamentals in CS, applied math, and ML (1-2 years), complete one meaningful project (1 year), develop engineering discipline with documented code, demonstrate high agency, and network proactively before job searching.

**Read more:** [Getting Started in BioML Research](/posts/2025/05/getting-started-bioml/)

---

### What skills do I need for BioML roles?

Python, ML frameworks (PyTorch/JAX), biological understanding (from papers and enthusiasm), version control, experiment tracking, statistical analysis, and collaboration with experimentalists.

**Read more:** [Getting Started in BioML Research](/posts/2025/05/getting-started-bioml/)

---

### Should I do a PhD for BioML work?

PhD helps for research roles but completed projects, demonstrated execution, engineering practices, and problem-solving agency matter more - build these through industry, self-study, or formal education.

**Read more:** [Getting Started in BioML Research](/posts/2025/05/getting-started-bioml/) • [About](/about/)

---

### What do hiring managers look for?

Completed work with clear outcomes, problem-solving agency, collaboration skills with experimentalists, strong code quality, clear communication - pedigree matters less than execution.

**Read more:** [Getting Started in BioML Research](/posts/2025/05/getting-started-bioml/)

---

## Industry Landscape

### Which biotech companies are truly AI-native?

Companies with value propositions impossible before ChatGPT (Nov 2022), built by teams under 30 employees before scaling, where ML drives core operations through autonomous design loops and data-first infrastructure.

**Read more:** [Legacy vs AI-Native Companies](/posts/2025/10/legacy-vs-ai-native/) • [About - Coefficient Bio](/about/)

---

### Can established companies become AI-native?

No - companies that scaled before November 2022 are structurally "AI-encumbered" by organizational inertia and incompatible systems; adopting AI without redesigning processes amplifies dysfunctions (MIT found 95% of enterprise GenAI pilots failed to increase revenue).

**Read more:** [Legacy vs AI-Native Companies](/posts/2025/10/legacy-vs-ai-native/)

---

### How do I know if a biotech is truly AI-native?

Ask: "Could you have built this in 2021?" - if yes, skip it. Check if they loudly claim "AI-native" status (bad sign), assess team size under 30 employees, verify ML drives operations rather than bolting onto existing systems, and watch for "workslop" (AI-generated content nobody reads but everyone creates).

**Read more:** [Legacy vs AI-Native Companies](/posts/2025/10/legacy-vs-ai-native/) • [Getting Started in BioML](/posts/2025/05/getting-started-bioml/)

---

### What works and what doesn't in AI drug discovery?

**Works:** Hit prioritization (10-100x enrichment), AlphaFold for known sequence families, few-shot protein design, retrosynthetic planning, experimental automation.
**Fails:** Binding prediction that doesn't block campaigns, black-box models biologists can't trust, ML systems failing to integrate with experimentalist workflows.

**Read more:** [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/) • [Publications](/publications/)

---

### How has AI impacted drug development timelines?

Hit identification and lead optimization dropped from months to weeks; later-stage development (clinical trials, manufacturing) remains uncompressed.

**Read more:** [The Impact of AI/ML in Drug Discovery](/posts/2024/08/ai-impact-drug-discovery/)

---

## Related Resources

- [Blog Posts](/blog-posts/) - Detailed articles on AI drug discovery strategy and BioML careers
- [Publications](/publications/) - Peer-reviewed research on foundation models and autonomous design
- [Portfolio](/portfolio/) - Open-source tools including LOBSTER and Walk-Jump Sampling
- [About](/about/) - My background at Genentech, Prescient Design, and Coefficient Bio
- [CV](/cv/) - Complete professional experience and credentials

---

**Have a question not answered here?** Connect via [LinkedIn](https://www.linkedin.com/in/ncfrey/) or [Substack](https://ncfrey.substack.com/).

*This FAQ is regularly updated based on questions from biotech executives, investors, researchers, and students navigating AI transformation in drug discovery.*

**Keywords:** AI drug discovery FAQ, foundation models pharma, BioML careers, antibody design AI, protein language models, autonomous drug discovery, biotech AI investment, machine learning drug development, AI pharma ROI, computational biology careers, therapeutic protein engineering, lab-in-the-loop systems
