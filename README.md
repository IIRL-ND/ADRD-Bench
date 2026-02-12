# ADRD-Bench Benchmark

**ADRD-Bench** is a **benchmark specifically designed for Alzheimer’s Disease and Related Dementias (ADRD)** to rigorously evaluate large language models (LLMs) in both **clinical knowledge** and **daily caregiving contexts**.

---

## Overview

ADRD-Care consists of **two complementary components**:

### ADRD Unified QA

A curated and unified question set synthesized from **seven established medical QA benchmarks**, designed to evaluate LLMs’ **ADRD-related clinical knowledge**.

- **Total questions**: 1,352  
- **Data access note**: Due to original dataset licensing restrictions, we do **not** redistribute the full question texts. Instead, we provide:
  - the **source dataset name**
  - the **original index** of each question within its source benchmark

This design is for **reproducibility and transparency**, while respecting all original data usage policies.


### ADRD Daily Caring QA

A **novel benchmark** focusing on **real-world dementia caregiving scenarios**, derived from a well-validated collaborative care program’s caregiver education materials.

- **Total questions**: 149  
- **Question formats**:
  - Multiple-choice questions: 29
  - True / False questions: 120
- **Design guidance**: developed in collaboration with an **experienced clinician**
- **Focus areas**: daily care, communication, safety, behavioral symptoms, and caregiver decision-making

This component helps mitigate the lack of **practical caregiving context** in existing ADRD-related benchmarks.



## Repository Structure

```text
ADRD-caring-LLM-benchmark/
├── ADRD_Caregiving_QA/
│   ├── ADRD_Caregiving_Multiple_Choice.json
│   └── ADRD_Caregiving_True_or_False.json
├── ADRD_Unified_QA/
│   ├── ADRD_Unified.json
├── README.md
└── LICENSE
```

## Data Usage & Ethics

- ADRD Daily Caring QA is released **for research and evaluation purposes only**
- ADRD Unified QA complies with all original dataset licenses by providing **indices only**
- This benchmark is **not intended for direct medical decision-making**


## Contact

**Project Team**: IIRL-ND  

For questions, collaborations, or access inquiries, please open an issue or contact the authors.
