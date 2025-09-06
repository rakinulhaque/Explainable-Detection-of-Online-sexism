# Explainable Detection of Online Sexism

## Overview
Sexism in online environments is a pervasive and harmful issue. It affects not only those directly targeted but also contributes to creating unwelcoming, exclusionary, and unsafe digital spaces. Traditional automated moderation tools typically provide only high-level binary or categorical labels (e.g., *sexist* vs. *not sexist*) without further explanation. While useful for scale, such approaches lack interpretability and transparency, limiting trust and preventing deeper understanding.

This project addresses these limitations by developing **explainable automated tools** for detecting sexism in online content. The system not only identifies sexist expressions but also provides **contextual explanations** of *why* content is considered sexist. Such explainability improves:
- **Interpretability** for researchers and moderators  
- **Trustworthiness** of automated systems  
- **Empowerment** for both users and moderators to take informed action

The work is accompanied by a detailed research report outlining the methodology, rationale, and findings.

---

## Objectives
- Detect sexist content in online text with high accuracy  
- Provide **explanations** alongside classification decisions  
- Contribute to safer, more inclusive online communities  
- Advance research on **explainable AI (XAI)** in content moderation  

---

## Methods

### Data
- Curated and annotated datasets of online text, including instances of sexist and non-sexist content  
- Fine-grained labels capturing both *type* and *context* of sexism  

### Models
- **Natural Language Processing (NLP)** techniques leveraging transformer-based architectures (e.g., BERT, RoBERTa)  
- Fine-tuned language models for classification of sexist vs. non-sexist content  
- Post-hoc and intrinsic explanation methods to surface model reasoning  

### Explainability Approaches
- **Attention visualization** to highlight harmful segments of text  
- **Rule-based rationales** aligned with definitions of sexism  
- **Human-readable explanations** generated alongside predictions  

---

## Tools and Technologies
- **Python** (core programming language)  
- **Jupyter Notebook** (experimentation & reporting)  
- **Transformers (HuggingFace)** for NLP modeling  
- **scikit-learn** for preprocessing and evaluation  
- **LIME / SHAP** for model interpretability  
- **Pandas & NumPy** for data manipulation  
- **Matplotlib / Seaborn** for visualization  

---

## Results
- Improved detection of sexist content compared to baseline classifiers  
- Generation of clear, actionable explanations that align with human judgment  
- Demonstrated potential to increase **user trust** and **moderator efficiency**  

---

## Research Report
A comprehensive research report is included with this repository. It details:
- The motivation behind the work  
- Data preparation and annotation strategies  
- Model architectures and training process  
- Evaluation metrics and benchmarks  
- Findings and implications for real-world deployment  

---

Dataset Link : https://drive.google.com/file/d/1R_2PR1UjYCfRku0GUui6MR8ukiUE0L60/view?usp=drive_link
