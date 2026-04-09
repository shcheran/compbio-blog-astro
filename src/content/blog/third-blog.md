---
title: "Week 3 - AI, Multi-Omics & Next-Generation Therapeutics"
description: "A curated digest of advances in AI-driven biology, single-cell analysis, genomics, and emerging therapeutic strategies."
pubDate: '2026-04-09'
heroImage:  '../../assets/week-3.png'
---


This collection focuses on the convergence of **AI, multi-omics technologies, and next-generation therapeutic design**, highlighting both methodological advances and translational applications.

Across these works, a clear trend emerges: biological research is becoming increasingly **data-driven, model-integrated, and computationally scalable**, enabling deeper understanding and more precise intervention in complex systems.

---

## AI for Molecular & Sequence Biology

### AI Foundation Models for RNA Biology

**Source:** PubMed (RNA Biology)

**Abstract**  
AI foundation models are reshaping RNA biology by learning complex relationships between sequence, structure, and function from large-scale datasets. These models provide generalizable representations that can be fine-tuned for diverse downstream tasks, including motif discovery and regulatory element identification. Importantly, the integration of explainable AI methods enables researchers to move beyond prediction toward mechanistic understanding. ([link to the publication](https://pubmed.ncbi.nlm.nih.gov/41873866/))

**Keywords:** RNA, foundation models, explainable AI, sequence biology  

---

### Protein Language Model Distillation

**Source:** Nature Methods  

**Abstract**  
This work demonstrates that co-distillation of multiple protein language models can produce a single high-performance model capable of accurate variant effect prediction. By removing dependence on structural or genetic data, the approach simplifies deployment while maintaining state-of-the-art performance. This significantly broadens accessibility of advanced protein modeling tools. ([link to the publication](https://www.nature.com/articles/s41592-026-03050-9))

**Keywords:** protein language models, variant prediction, model compression  

---

### VESM — Sequence-Only Variant Modeling

**Source:** Nature Methods  

**Abstract**  
VESM aggregates predictions from multiple protein language models into a unified sequence-only model that outperforms hybrid approaches. It provides not only classification but also quantitative severity scores for variants, improving interpretability and clinical relevance. This enhances its utility in diagnostics and precision medicine. ([link to the publication](https://www.nature.com/articles/s41592-026-03049-2))

**Keywords:** PLM, genomics, variant severity, clinical AI  

---

## Single-Cell & Multi-Omics Analysis

### CASPA — Single-Cell Proteomics Pipeline

**Source:** bioRxiv  

**Abstract**  
CASPA introduces a fully automated pipeline for single-cell proteomics that addresses key challenges such as missing data, contamination, and limited feature space. By incorporating LLM-guided annotation with structured reasoning and validation, it produces reproducible and interpretable cell-type classifications. This represents a major step toward scalable, standardized proteomics workflows. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.04.03.716382v1))

**Keywords:** single-cell proteomics, pipelines, LLMs, reproducibility  

---

### MitoChontrol — Adaptive RNA-seq Quality Control

**Source:** bioRxiv  

**Abstract**  
MitoChontrol introduces a probabilistic framework for mitochondrial quality control in single-cell RNA-seq data. By adapting thresholds to cell-type-specific distributions, it avoids common biases introduced by fixed filtering rules. This improves data quality and preserves biologically meaningful variation across heterogeneous tissues. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.04.04.716517v1))

**Keywords:** scRNA-seq, quality control, mitochondria, data filtering  

---

### Total RNA Sequencing Across Modalities

**Source:** Nature Biotechnology  

**Abstract**  
This method enables simultaneous profiling of both polyadenylated and non-polyadenylated RNAs, revealing regulatory programs that are missed by standard RNA-seq approaches. By capturing a broader spectrum of transcripts, it provides a more complete view of gene regulation. This expands opportunities for discovering new biological mechanisms and therapeutic targets. ([link to the publication](https://www.nature.com/articles/s41587-026-03068-6))

**Keywords:** RNA-seq, transcriptomics, noncoding RNA  

---

### Long-Read RNA-seq Benchmarking

**Source:** bioRxiv  

**Abstract**  
This study provides a comprehensive comparison of long-read RNA sequencing platforms and computational tools across bulk and single-cell settings. It reveals platform-specific biases and offers guidance on sequencing depth and method selection. The results serve as a valuable reference for designing transcriptomics experiments. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.04.01.715783v1))

**Keywords:** long-read sequencing, benchmarking, transcriptomics  

---

## Generative & Simulation-Based Biology

### CLOP-DiT — Generative Single-Cell Models

**Source:** bioRxiv  

**Abstract**  
CLOP-DiT enables generation of realistic single-cell transcriptomic profiles from structured biological descriptions. By aligning textual and cellular representations and using diffusion models, it allows controlled simulation of cell states. This opens new possibilities for data augmentation, hypothesis testing, and experimental design. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.03.26.714457v1))

**Keywords:** generative models, single-cell, diffusion  

---

### OPTIMIS — AI-Driven Therapy Optimization

**Source:** bioRxiv  

**Abstract**  
OPTIMIS integrates stochastic biological modeling with neural ODEs and reinforcement learning to simulate and optimize therapeutic interventions. It enables adaptive treatment strategies that respond dynamically to cellular behavior. This framework moves toward real-time, personalized therapy design. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.03.24.713941v1))

**Keywords:** reinforcement learning, therapy optimization, simulation  

---

### AI-Assisted QSP Modeling

**Source:** bioRxiv  

**Abstract**  
This AI-assisted workflow uses large language models to reconstruct and extend quantitative systems pharmacology models with reduced manual effort. It maintains mechanistic transparency while improving reproducibility and scalability. The approach accelerates model-informed drug development workflows. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.04.05.716273v1))

**Keywords:** QSP, pharmacology, AI modeling  

---

## Genomics & Functional Interpretation

### SNP Annotation Benchmarking

**Source:** bioRxiv  

**Abstract**  
This study systematically compares SNP annotation tools and gene models, revealing significant discrepancies across methods. It demonstrates that integrated multi-tool approaches provide more complete and reliable functional interpretations. This is critical for preserving pathway-level insights in genomic studies. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.03.21.713397v1))

**Keywords:** SNP, annotation, genomics, pathways  

---

### FoundedPBI — Phage Interaction Prediction

**Source:** bioRxiv  

**Abstract**  
FoundedPBI uses genomic foundation models and ensemble learning to predict phage-bacterium interactions from sequence data. By incorporating long-context genomic information, it significantly improves predictive performance. This accelerates the development of phage therapy as an alternative to antibiotics. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.03.24.713871v1))

**Keywords:** phage therapy, genomics, prediction  

---

### Multi-Omics Hypertension Study

**Source:** PubMed (Epigenetics)

**Abstract**  
This study integrates epigenomic and transcriptomic data to identify methylation-driven genes associated with essential hypertension. It highlights key regulatory pathways and potential drug targets shared across tissues. The findings provide new insights into disease mechanisms and biomarker discovery. ([link to the publication](https://pubmed.ncbi.nlm.nih.gov/41943668/))

**Keywords:** epigenomics, hypertension, biomarkers  

---

## Imaging & Structural Biology

### DeepBranchAI — 3D Segmentation

**Source:** bioRxiv  

**Abstract**  
DeepBranchAI introduces a cascade workflow that enables accurate 3D segmentation of branching biological structures from minimal annotations. By iteratively refining training data, it overcomes annotation bottlenecks and preserves topological integrity. The method generalizes across domains, from mitochondria to vascular systems. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.03.25.714249v1))

**Keywords:** segmentation, imaging, 3D modeling  

---

### Sequence Display — Protein Screening

**Source:** Nature Biotechnology  

**Abstract**  
Sequence Display links protein variants to DNA barcodes, enabling high-throughput functional screening via sequencing. This transforms protein engineering into a scalable, data-driven process. It significantly accelerates variant analysis and therapeutic development. ([link to the publication](https://www.nature.com/articles/s41587-026-03087-3))

**Keywords:** protein engineering, sequencing, high-throughput  

---

## Systems Biology & Cellular Mechanisms

### Translation Fidelity in Brain Development

**Source:** bioRxiv  

**Abstract**  
This study shows that mRNA translation fidelity is dynamically regulated during development and varies across tissues. High fidelity in neurons is essential for proper maturation and function. These findings reveal translation accuracy as a critical regulatory layer in development. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.04.01.715671v1))

**Keywords:** translation, development, neuroscience  

---

### Lung Fibrosis Resolution Dynamics

**Source:** bioRxiv  

**Abstract**  
Longitudinal single-cell analysis reveals the cellular and signaling changes underlying spontaneous resolution of lung fibrosis. It identifies both pro- and anti-fibrotic pathways and their interactions across cell types. These insights provide potential therapeutic targets for fibrotic diseases. ([link to the publication](https://www.biorxiv.org/content/10.64898/2026.04.06.716772v1))

**Keywords:** fibrosis, single-cell, signaling  

---

### Toward Virtual Cells

**Source:** Nature Biotechnology  

**Abstract**  
This perspective argues that true virtual cell models will require integrating AI-driven pattern recognition with mechanistic biological models. Combining these approaches enables both predictive accuracy and interpretability. This integration is key to advancing systems biology and drug discovery. ([link to the publication](https://www.nature.com/articles/s41587-026-03110-7))

**Keywords:** systems biology, modeling, AI  

---

## Therapeutics & Industry

### Sidewinder Bispecific ADCs

**Source:** BioSpace  

**Abstract**  
Sidewinder is developing bispecific antibody-drug conjugates that target two tumor receptors simultaneously. This dual-targeting strategy improves specificity and reduces off-target toxicity. It represents a promising direction for next-generation cancer therapeutics. ([link to the publication](https://www.biospace.com/business/novartis-backed-sidewinder-collects-137m-series-b-to-strike-at-difficult-to-treat-tumors))

**Keywords:** ADC, oncology, bispecific  

---

### Roche Molecular Glue Partnership

**Source:** BioSpace  

**Abstract**  
Roche is expanding into degrader-antibody conjugates through a major partnership, combining protein degradation with targeted delivery. This hybrid modality could enhance therapeutic precision and efficacy. It signals growing industry investment in next-generation drug mechanisms. ([link to the publication](https://www.biospace.com/deals/roche-sticks-with-c4t-adding-up-to-1b-for-molecular-glue-partnership))

**Keywords:** molecular glue, protein degradation, therapeutics  

---

### Sanofi Bispecific Trial Results

**Source:** Fierce Biotech  

**Abstract**  
Sanofi’s bispecific inhibitor shows strong results in respiratory diseases but fails to demonstrate efficacy in eczema. This highlights the complexity of translating mechanisms across disease contexts. It underscores the importance of disease-specific pathway targeting in drug development. ([link to the publication](https://www.fiercebiotech.com/biotech/sanofis-bispecific-scores-double-respiratory-phase-2-wins-flunks-eczema-study-0))

**Keywords:** bispecifics, clinical trials, immunology  

---

## Final Takeaways

Across these studies, biology is increasingly being shaped by the integration of AI, multi-omics data, and scalable computational models. The field is moving toward more predictive, interpretable, and automated systems that bridge molecular understanding with therapeutic application.