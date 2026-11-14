# Binit Behl

### Machine Learning Researcher | AI Safety | LLM Reliability | Trustworthy AI

I build and evaluate reliable machine learning systems, with a focus on AI safety, uncertainty estimation, hallucination detection, out-of-distribution generalization, and training-data attribution.

My work combines research-driven experimentation with practical engineering: designing detection methods, benchmarking against strong baselines, conducting statistical analysis, and building working demonstrations.

Currently: Data Science Intern at Codec Technologies  
Education: B.Tech Computer Science Engineering, GGSIPU (2027)

---

### Research Interests

- Trustworthy and Reliable Artificial Intelligence
- Large Language Model (LLM) Hallucination Detection
- Out-of-Distribution (OOD) Detection
- Model Calibration and Uncertainty Estimation
- Training Data Attribution and Model Interpretability
- Backdoor Attacks and Data Poisoning
- Robust Machine Learning

---

### Featured Research & Projects

#### 1. Hallucination Detection and Mitigation in LLMs
Python · PyTorch · Hugging Face · FAISS · Streamlit

An end-to-end framework for identifying unreliable LLM responses using self-consistency, retrieval-based grounding, and token-level confidence.

- Achieved **0.755 AUROC** using combined trust signals on 300 TruthfulQA questions.
- Reduced Expected Calibration Error from **0.37 to 0.06** using Platt scaling.
- Reduced hallucinated answers shown to users from 79 to approximately 38 per 100 questions in a leave-one-out retrieval experiment.
- Evaluated the safety–usefulness trade-off, including abstention rates and computational overhead.

[Explore the project](https://github.com/Binitbehl/Hallucination-project)

#### 2. TraceML: Training Data Attribution and Model Behaviour Forensics
**Python · PyTorch · Streamlit**

A research implementation exploring how training examples influence model predictions and how attribution can support model forensics.

- Implemented TracIn and nearest-neighbour training-data attribution.
- Investigated backdoor poisoning involving 200 poisoned samples out of 5,000.
- Reduced attack success from 100% to 5.7% after identifying and removing poisoned samples.
- Compared attribution-based label-noise detection with training-loss baselines.

[Explore the project](https://github.com/Binitbehl/Traceml)

#### 3. Feature-Space Out-of-Distribution Detection
Research Publication · Deep Learning · ResNet-50

Sole-author research on improving deep learning reliability under distribution shift using class-conditional Mahalanobis distance and feature-space modelling.

- Improved AUROC over MSP from 0.82 to 0.89 on SVHN.
- Achieved 0.92 AUROC with supervised contrastive regularization.
- Reduced SVHN FPR@95 to 0.14.
- Evaluated across CIFAR-10, SVHN, LSUN and CIFAR-10-C.

Publication: Improving Reliability of Deep Learning Systems Under Distribution Shift via Feature-Space Out-of-Distribution Detection.

[Read the publication](https://journals.stmjournals.com/ijbcb/article=2026/view=260268)

---

### Technical Skills

Programming: Python, C, C++, Java, SQL

Machine Learning: PyTorch, CNNs, Deep Learning, Supervised Contrastive Learning

LLMs & NLP: Hugging Face Transformers, FAISS, Retrieval-Augmented Grounding, NLI, Self-Consistency

AI Safety & Reliability: OOD Detection, Hallucination Detection, Model Calibration, Uncertainty Estimation, TracIn, Data Poisoning Analysis

Research & Evaluation: AUROC, Bootstrap Confidence Intervals, Statistical Significance Testing, Ablation Studies, Baseline Benchmarking

Tools: Git, GitHub, Streamlit, Google Colab

---

### Research & Professional Experience

- Data Science Intern — Codec Technologies
- Published research in deep learning reliability and OOD detection
- Presented research at an international conference (2026)
- Participant — Smart India Hackathon 2025

---

### Let's Connect

- GitHub: https://github.com/Binitbehl
- LinkedIn: https://linkedin.com/in/binitbehl
- Google Scholar: https://scholar.google.com/citations?user=GWCsovwAAAAJ
- Email: binitbehl@gmail.com

---

"Building AI systems that are not just powerful, but reliable, explainable, and trustworthy."
