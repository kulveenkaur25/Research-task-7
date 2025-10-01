# Research-task-7
# Task 07 – Decision-Making Report

## Overview
This repository contains all materials for **Research Task 07**, which required transforming prior LLM-based analyses (Task 5 & Task 6) into a stakeholder-facing decision report with actionable recommendations, ethical considerations, and full process documentation.

The focus is on **process transparency** and **reproducibility** rather than the final outcome.

---

## Repository Structure

```
Task_07_Decision_Making/
│
│   ├── Task_07_Decision_Report.docx     # Full report (Word)
│
│   ├── combined_summary_stats.csv       # Aggregated 2023 NFL season stats
│
│   ├── Research_task.ipynb              # Notebook with descriptive stats, validations, and visualizations
│
│   ├── prompts.md                       # Task 5 prompts and responses
│
├── README.md
```

---

## 📝 Report Contents
The stakeholder report includes:
- **Executive Summary** with tiered recommendations.
- **Background & Decision Question** (stakeholders, risks).
- **Data & Methods** (provenance, limitations, validation).
- **Findings** with descriptive results and visualizations.
- **Uncertainty & Robustness** (bootstrap CI, sanity checks).
- **Recommendations** (operational, investigatory, strategic).
- **Ethical & Legal Concerns** (transparency, deep fake misuse).
- **Bias & Fairness Checks** (aggregation bias, mitigation).
- **Next Steps & Validation Plan**.
- **Appendices** (prompts, outputs, scripts, dataset lineage).

---

## How to Reproduce
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/Task_07_Decision_Making.git
   cd Task_07_Decision_Making
   ```

2. Install dependencies (Python 3.10+ recommended):
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook notebooks/Research_task.ipynb
   ```

4. Run cells to regenerate descriptive statistics and figures.

---

## Transparency Notes
- **LLM Transparency Notice:** Prompts and outputs from Task 5 and Task 6 are included in `/prompts`. Sections of the report marked *[LLM-generated]* originate from GPT-4, with edits annotated in the appendix.
- **Data Provenance:** Stats derived from publicly available 2023 NFL play-by-play data, aggregated to summary form.
- **Limitations:** Aggregated data may obscure player-level context or subgroup variability.

---

