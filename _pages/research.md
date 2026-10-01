---
title: "Research"
sitemap: false
permalink: /research/
toc: false
---

<link rel="stylesheet" href="../assets/style.css">

<aside class="sidebar__right sticky" style="max-width: 250px;">
  <nav class="toc" aria-label="Table of contents" style="background: rgba(128,128,128,0.06); border: 1px solid rgba(128,128,128,0.2); border-radius: 8px; padding: 12px 14px;">
    <header><h4 class="nav__title" style="margin: 0 0 10px 0; font-size: 0.85em; text-transform: uppercase; letter-spacing: 0.8px; opacity: 0.85;"><i class="fas fa-compass"></i> Outlines</h4></header>
    <ul class="toc__menu" style="list-style: none; margin: 0; padding: 0;">
      <li style="margin-bottom: 8px;"><a href="#nlp" style="text-decoration: none; font-size: 0.9em; display: block; padding: 6px 10px; border-radius: 4px; border-left: 3px solid #00adb5; background: rgba(0, 173, 181, 0.08); font-weight: 500;">NLP & Reasoning</a></li>
      <li style="margin-bottom: 8px;"><a href="#cv" style="text-decoration: none; font-size: 0.9em; display: block; padding: 6px 10px; border-radius: 4px; border-left: 3px solid #ff5722; background: rgba(255, 87, 34, 0.08); font-weight: 500;">Computer Vision</a></li>
      <li style="margin-bottom: 0;"><a href="#convergence" style="text-decoration: none; font-size: 0.9em; display: block; padding: 6px 10px; border-radius: 4px; border-left: 3px solid #b388ff; background: rgba(179, 136, 255, 0.08); font-weight: 500;">Multimodal Convergence</a></li>
    </ul>
  </nav>
</aside>

My research spans **Natural Language Processing (NLP)**, **Computer Vision (CV)**, and their **multimodal convergence**. Specifically, I focus on advancing structured reasoning, grounding, and alignment across language models and dynamic visual representations.

<hr style="border: none; border-top: 1px solid currentColor; opacity: 0.25; margin: 2em 0 1.5em 0;" />

<h2 id="nlp" style="scroll-margin-top: 30px;">Natural Language Processing & Structured Reasoning</h2>

My work in NLP centers on understanding how language models reason internally, grounding their outputs with structured knowledge, and maintaining performance under low-resource and class-imbalanced constraints.

#### Grounding & Reasoning Architectures
* **GRASP-ChoQ: Knowledge Graph-Augmented Stance Detection** *(ACL Anthology / BLP 2025)*  
  LLMs frequently struggle to detect subtle, indirect stances in low-resource regional contexts. We developed a Chain-of-Questions reasoning framework paired with Neo4j Knowledge Graph retrieval, improving DeepSeek R1 stance detection F1 score to 93.33 (a 40.6% relative gain).  
  [[paper]](https://aclanthology.org/2025.banglalp-1.2/) [[pdf]](/Publications/GRASP_ChoQ_compressed.pdf)

* **Enhancing LLM Reasoning via Negative Supervision and Error Reflection** *(Submitted to ACL ARR 2026)*  
  A systematic investigation into how unlearning, negative feedback signals, and self-reflection loops can guide internal model logic, allowing models to catch and correct flawed deduction trajectories prior to text generation.  
  _[Under Review]_

#### Low-Resource Benchmarks & Model Efficiency
* **Moner Janala: Bengali Mental Health Counseling Dataset** *(Mendeley Data 2026)*  
  Addressed the lack of psychological NLP resources in low-resource settings by curating and structuring 625 verified counseling Q&A pairs from national archives (2009–2024) to benchmark mental health NLP models.  
  [[dataset]](https://data.mendeley.com/datasets/pwd2r284wh/1)

* **SLM Optimization via Distillation & Quantization Pipelines** *(Submitted 2026)*  
  Compressed language models for Bangla affective computing (hate speech and emotion classification) using knowledge distillation and precision quantization for resource-constrained deployment.  
  _[Under Review]_

* **Ontology-Driven Synthetic Clinical Dialogue Generation** *(Working Manuscript 2026)*  
  Formulated an ontology-constrained prompt engineering pipeline to generate structured synthetic medical dialogue in both standard and regional code-mixed Bengali.  
  _[Working Manuscript]_

#### Representation Learning & Stylistic Modeling
* **Adapting Contextual Embeddings under Severe Class Imbalance** *(IEEE iCACCESS 2024)*  
  Mitigated classification failure across 568k+ Amazon e-commerce reviews by pairing RoBERTa contextual representations with class re-weighting and gradient-boosted trees.  
  [[paper]](https://ieeexplore.ieee.org/abstract/document/10499554) [[pdf]](/Publications/Adapting_Contextual_Embedding_to_Identify_Sentiment_of_E_commerce_Consumer_Reviews_with_Addressing_Class_Imbalance_Issues.pdf)

* **Deceptive Linguistic Pattern Extraction with RoBERTa** *(IEEE ICCIT 2023)*  
  Constructed a deep classifier atop RoBERTa representations to detect subtle misinformation cues on the 72k-article WELFake benchmark (99.76% accuracy).  
  [[paper]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=B2hJJz8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=B2hJJz8AAAAJ:2osOgNQ5qMEC) [[pdf]](/Publications/Detection of Fake News with RoBERTa Based Embedding and Modified Deep Neural Network Architecture.pdf)

* **Autoregressive Style Replication via GPT Fine-Tuning** *(B.Sc. Thesis 2023)*  
  Fine-tuned autoregressive language models on regional literary corpora to study narrative style transfer, perplexity dynamics, and text coherence in low-resource domains.  
  [[pdf]](/Publications/Rakib_Mollah_BSc_thesis.pdf)

<hr style="border: none; border-top: 1px solid currentColor; opacity: 0.25; margin: 2em 0 1.5em 0;" />

<h2 id="cv" style="scroll-margin-top: 30px;">Computer Vision & Video Dynamics</h2>

This track explores model interpretability, robust real-time action recognition, and algorithmic video dynamics under unconstrained conditions.

#### Video Dynamics & Boundary Analysis
* **DetectVideoShotLength: Algorithmic Video Scene Cut Detection** *(Python Package 2024)*  
  Developed an open-source pipeline using color histogram divergence and Structural Similarity (SSIM) to detect scene cuts, calculate shot durations, and analyze cut distributions in unconstrained video.  
  [[code]](https://github.com/RakibMollah/DetectVideoShotLength)

#### Explainable Diagnostics & Ensemble Vision
* **Grad-CAM Enhanced Pulmonary Screening from Radiographs** *(IEEE SMART GENCON 2023)*  
  Benchmarked five deep CNN architectures on 21,000+ chest X-rays, incorporating Grad-CAM saliency heatmaps to visually verify that model classifications aligned with true clinical opacities rather than spurious image artifacts (99.13% accuracy).  
  [[paper]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=B2hJJz8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=B2hJJz8AAAAJ:d1gkVwhDpl0C) [[pdf]](/Publications/Exploring_Deep_Convolutional_Neural_Networks_A_Grad-CAM_Enhanced_Comparative_Stu.pdf)

* **Multi-Backbone Ensembles for Brain MRI Diagnostics** *(IEEE ICAIIHI 2023)*  
  Mitigated single-model variance and overfitting on structural brain MRI scans by constructing an ensemble architecture (ResNet-50, EfficientNet B7, DenseNet-121) across dual ADNI cohorts.  
  [[paper]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=B2hJJz8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=B2hJJz8AAAAJ:u-x6o8ySG0sC) [[pdf]](/Publications/Improving Alzheimer's Disease Diagnosis on Brain MRI Scans with an Ensemble of Deep Learning Models.pdf)

* **Parameter-Efficient Real-Time Driver Behavior Classification** *(IEEE ICCIT 2022)*  
  Constructed a real-time vision framework combining fine-tuned MobileNet and DenseNet121 architectures to categorize 10 distinct driver distraction behaviors on the State Farm dataset (99.81% accuracy).  
  [[paper]](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=B2hJJz8AAAAJ&sortby=pubdate&authuser=1&citation_for_view=B2hJJz8AAAAJ:u5HHmVD_uO8C) [[pdf]](/Publications/An Ensemble Approach for Identification of Distracted Driver by Implementing Transfer Learned Deep CNN Architectures.pdf)

<hr style="border: none; border-top: 1px solid currentColor; opacity: 0.25; margin: 2em 0 1.5em 0;" />

<h2 id="convergence" style="scroll-margin-top: 30px;">Multimodal Convergence (Vision + Language)</h2>

The intersection of my research focuses on grounding semantic language priors within 3D/4D visual geometry and eliminating cross-modal hallucinations in Vision-Language Models.

* **Shot-GS: VLM-Guided Spatio-Temporal Reasoning for Dynamic Gaussian Splatting** *(Ongoing Research 2026)*  
  Dynamic 4D Gaussian Splatting collapses when applied to casual, multi-shot video because camera cuts break low-level optical flow and point tracking. This framework leverages Vision-Language Models (e.g., SAM 2, invariant entity tokens) to maintain cross-shot semantic identity and applies spatio-temporal reasoning across unobserved cut boundaries.  
  _[Ongoing Research]_

* **Mitigating VLM Hallucination via DPO and Targeted Negative Sampling** *(Ongoing Research 2026)*  
  Aligning Vision-Language Models for complex document and financial reasoning by applying Direct Preference Optimization (DPO) combined with targeted negative sampling to penalize subtle visual hallucinations and numerical inaccuracies.  
  _[Ongoing Research]_

* **Project Z: Geospatial Intelligence & Conversational Analytics** *(2024)*  
  Coupled dynamic geospatial demographic mapping with an interactive conversational assistant to synthesize regional socio-economic trends for data-driven decision support.  
  [[demo / repository]](https://github.com/RakibMollah/Project-Z) 
