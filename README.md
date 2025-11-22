# Physiotherapy Evidence QA Dataset (TR–EN)

A large-scale bilingual dataset containing **143,712**
expert-curated question–answer pairs focused on evidence-based physiotherapy,
musculoskeletal rehabilitation, outcome measures, and clinical research.

Created by:  
**Serhan Ayberk KILIÇ**,**Fatma Betül Derdiyok**,**Kasım Serbest**

---

## 🔍 Overview

This dataset provides high-quality, structured physiotherapy knowledge covering:

- Lateral epicondylitis (tennis elbow)
- Physiotherapy / rehabilitation interventions
- Diagnostic tools and clinical assessment
- Meta-analysis and statistical methodology
- Evidence interpretation principles

Each entry has aligned **English and Turkish Q&A**, plus metadata such as
difficulty, question type, disease category, keywords, and source references.

---

## 📁 Dataset Structure

All column names are **English-only**:

| Column Name | Description |
|-------------|-------------|
| `question_tr` | Question in Turkish |
| `answer_tr` | Answer in Turkish |
| `question_en` | Question in English |
| `answer_en` | Answer in English |
| `disease_category_en` | Disease category (English) |
| `question_type_en` | Question type (English) |
| `difficulty` | Difficulty level (easy / medium / hard) |
| `keywords_tr` | Keywords in Turkish |
| `keywords_en` | Keywords in English |
| `source_file` | Source article / document name |
| `source_page` | Page or index number |
