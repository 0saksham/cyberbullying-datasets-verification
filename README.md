# MultiBully-XAI Dataset Verification Repository

## Overview

This repository documents all datasets used in the research study:

**“Explainable AI for Multimodal Cyberbullying Detection (MultiBully-XAI)”**

The purpose of this repository is to provide transparency, traceability, and verification of all datasets used in the experimental evaluation, including:

- Publicly published datasets
- Subsets of benchmark datasets
- Author-created synthetic datasets
- Real-world validation samples
- Explainability evaluation datasets

This repository does **not** redistribute copyrighted or platform-restricted content.  
It provides documentation, source references, and access instructions in compliance with ethical and platform policies.

---

# Dataset Summary

| Dataset Name | Type | Size Used | Source Type |
|--------------|------|-----------|-------------|
| MMBD (Twitter Multimodal) | Text + Image | 8,472 | Published External Dataset |
| Twitter Cyberbullying (Van Hee et al., 2018) | Text-only | ~10,000 | Open-Access Published Dataset |
| Instagram Synthetic Dataset | Text + Image | 5,236 | Author-Created |
| XAI Evaluation Dataset | Multimodal | 200 | Author-Created |
| Real-World Validation Dataset | Multimodal | 150 | Author-Collected |

Total multimodal posts referenced in the study: **13,708**

---

# 1️⃣ MMBD – Multimodal Bullying Detection Dataset

**Source Type:** Published External Dataset  
**Platform:** Twitter  
**Data Type:** Text + Image  

Original Publication:
Kumari, K., & Singh, J. P. (2021).  
Deep learning for cyberbullying detection in social media: A multi-modal approach.  
Expert Systems with Applications, 171, 114664.  
DOI: https://doi.org/10.1016/j.eswa.2021.114664

Subset Used in Study:
- 8,472 samples
- Bullying ratio: 25.4%
- Used for baseline reproduction experiments

Access Note:
Due to Twitter Terms of Service, raw tweet content is not redistributed.
Access may require:
- Tweet ID hydration via Twitter API
- Contacting original authors
- Accessing supplementary materials (if provided)

See folder: `/MMBD/`

---

# 2️⃣ Twitter Cyberbullying Dataset – Van Hee et al. (2018)

**Source Type:** Open-Access Published Dataset  
**Platform:** Twitter  
**Data Type:** Text-only  

Original Publication:
Van Hee et al. (2018)  
Automatic detection of cyberbullying in social media text  
PLoS ONE, 13(10), e0203794  
DOI: https://doi.org/10.1371/journal.pone.0203794

Approximate Size Used:
~10,000 tweets

Purpose in Study:
- Text-based validation
- Baseline comparison

Access Note:
Dataset details and annotation methodology are available via the open-access publication.
Raw tweets may require tweet ID hydration.

See folder: `/VanHee2018/`

---

# 3️⃣ Instagram Synthetic Cyberbullying Dataset

**Source Type:** Author-Created Synthetic Dataset  
**Platform Simulated:** Instagram  
**Data Type:** Text + Image  

Dataset Size:
- 5,236 samples
- Bullying ratio: 23.8%

Purpose:
- Simulate multimodal cross-platform bullying
- Improve generalization
- Evaluate multimodal fusion

Data Generation:
- Synthetic augmentation
- Controlled class balancing
- Manual validation

Public Availability:
This dataset is not sourced from a public repository.
It was generated specifically for research purposes.

See folder: `/Instagram_Synthetic/`

---

# 4️⃣ XAI Evaluation Dataset

**Source Type:** Author-Created  
**Size:** 200 samples  

Purpose:
Evaluate explanation quality of:
- SHAP
- LIME
- Attention Visualization

Evaluation Metrics:
- Faithfulness
- Robustness
- Understandability

This dataset was created exclusively to measure interpretability performance.

See folder: `/XAI_Evaluation/`

---

# 5️⃣ Real-World Social Media Validation Dataset

**Source Type:** Author-Collected  
**Size:** 150 samples  

Platforms Included:
- Twitter
- Instagram
- Facebook
- TikTok

Annotation Process:
- 3 independent moderators
- Majority voting
- Conflict resolution procedure

Purpose:
Validate real-world generalization performance.

See folder: `/RealWorld_150/`

---

# Ethical Compliance Statement

- No raw social media content is redistributed in this repository.
- No copyrighted images are stored.
- No personally identifiable information (PII) is included.
- All datasets comply with platform Terms of Service.
- Author-created datasets were generated or anonymized for academic research.

This repository serves documentation and verification purposes only.

---

# Reproducibility Statement

All dataset sources are documented with:
- Original publication references
- Access instructions
- Subset size used in the study
- Annotation methodology (for custom datasets)

This ensures transparency and academic reproducibility of the MultiBully-XAI framework.

---

# Contact Information

For dataset access requests related to external datasets,
please refer to the original publication authors.

For clarification regarding author-created datasets,
please contact the corresponding research author.

---

# Repository Structure

