# Task 08 — Bias Detection in LLM Data Narratives  
### Syracuse University • IST / OPT Research Activity  
### Author: Aman Keskar  

---

## 📘 Overview  
This repository contains the materials for **Task 08: Bias Detection in LLM Data Narratives**, part of my ongoing OPT-compliant research activities.  
The goal of this task was to investigate whether different Large Language Models (LLMs) produce **systematically different narratives** from the *same dataset* when exposed to variations in **prompt framing**.

The models used:

- **ChatGPT (OpenAI GPT-4o)**
- **Claude 3 Sonnet (Anthropic)**
- **Gemini Advanced (Google)**

All three models were queried independently using a controlled set of prompts.

---

## 🎯 Objectives  
This task aimed to evaluate four key bias categories:

1. **Framing Effects**  
   - Does negative or emotional wording change the conclusions an LLM gives?

2. **Model Differences**  
   - Do ChatGPT, Claude, and Gemini diverge in narrative tone or focus?

3. **Confirmation Bias**  
   - Will models “confirm” a user’s hypothesis even without evidence?

4. **Selection Bias**  
   - When forced to choose a “worst” or “liability,” do models fixate on the same player?

---

## 📊 Dataset  
A simplified, anonymized subset of MLB sprint speed statistics was used:

- **Player A** – Fastest  
- **Player B** – Average  
- **Player C** – Slowest  

The underlying ordering (A > B > C) remained constant across every prompt and every model.

This structure was derived from earlier work in **Task 05 (MLB Sprint Speed Analysis)**.

---

## 🧪 Methodology  

### 1. **Prompt Design**  
- 15 prompt pairs (30 prompts total)  
- Each pair includes a **neutral** and a **biased** version  
- Covers: emotional framing, loaded terms, age/seniority bias, confirmation prompts, forced comparisons, and “liability” framings  

### 2. **Cross-Model Testing**  
Each prompt was submitted to all three LLMs:

- ChatGPT  
- Claude  
- Gemini  

### 3. **Qualitative Coding**  
Outputs were analyzed for:  
- Sentiment shifts  
- Narrative style  
- Language severity  
- Degree of bias amplification or resistance  

### 4. **Structured Comparison**  
A sentiment trend table and cross-model behavior table were included in the final report.

---

## 🧾 Contents  

