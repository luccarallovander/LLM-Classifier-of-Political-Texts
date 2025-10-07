# 🧭 LLM Classifier of Political Texts


This project was conducted as part of my MSc Thesis. I trained and evaluated a series of large language models (LLMs) to classify European political parties along ideological dimensions using (a) **structured metadata** from the Manifesto Project Database (MPDS) and (b) **full-text party manifestos** over time. The result is a reproducible panel of ideology scores and party classifications suitable for downstream causal analyses.

---

## 🧩 Overview

This project combines **computational political science** and **machine learning** to map the ideological evolution of European political parties.  
Using metadata and full-text manifestos from the **Manifesto Project**, I build and benchmark a multi-modal pipeline that compares LLMs (OpenAI, Gemini, Mistral) on their ability to:
1. Classify parties by ideology and family; and  
2. Generate continuous ideology scores for longitudinal causal analysis.

The resulting dataset supports comparative studies of **nationalism, populism, and ideological shifts** across Europe from 1945–present.

---

## 🧠 Skills Used

- LLM-based classification of tabular data (OpenAI, Gemini 2.5 Pro, Mistral 7B Instruct, GPT-3.5-Turbo fine-tuned)  
- LLM-based text classification (NLP)  
- Causal inference (Two-Way Fixed Effects, Multiple Regression)  
- Prompt engineering, few-shot learning, and model evaluation (macro-F1, correlation with expert benchmarks)  
- Data engineering in **Python** (`pandas`, `scikit-learn`, `transformers`, `statsmodels`)  

---

## 🚀 Contributions

- **Developed** a dual-pipeline framework for ideology classification combining structured metadata and full-text manifestos.  
- **Benchmarked** open and proprietary LLMs on multilingual political text classification tasks.  
- **Constructed** a new **panel dataset** of party ideology scores for time-series causal analysis.  
- **Demonstrated** the reliability of fine-tuned GPT-3.5 models in replicating expert-coded ideological positions.  
- **Applied** modern causal methods (TWFE) to study shifts in nationalist vs. civic discourse across European regions.

---
