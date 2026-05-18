# Lecture 7 Critique — Text Classification (Continued) and Quantitative Text Analysis

**Syllabus date:** 20 May
**Syllabus title:** Text classification (continued) and Quantitative (text) analysis

---

## Note on Missing Slides

**There are no dedicated slides for Syllabus Lecture 7.** This is the most underdeveloped lecture in the course. A new slide deck needs to be created.

This folder (`Lecture_classification_quant_analysis/`) is a duplicate of `Lecture 10/` (focused coding and classification) and should be moved to `archive/` after its content is reviewed. It does **not** serve as Lecture 7 slides — it is an earlier version of the Lecture 6 material.

A new `Lecture_07/` folder should be created with fresh slides covering classifier validation and quantitative text analysis.

---

## What is Needed

Syllabus Lecture 7 should cover:
1. Classifier validation (precision, recall, F1, confusion matrix) — practical and applied
2. From classification to measurement (what the quantitative variable captures and what it does not)
3. Quantitative analysis options: frequency distributions, temporal trends, group comparisons, correlation with engagement metrics, regression with text-derived variables
4. Labelling a test set (the exercise activity listed in the syllabus)

---

## Critiques of Current Readings

1. **Nelson (2021) is 59 pages — too long for a single lecture.** Students risk surface-level engagement. Assign only the methods section and one substantive analysis section (~20 pp.) and use the rest as a reference.

2. **Greve et al. (2022) is primarily about Twitter network analysis and bots**, not text classification or quantitative text analysis per se. Its fit with the lecture title is loose. It may be better placed in a networks-adjacent session, or reframed explicitly as a mixed methods case study.

3. **Neither reading explicitly teaches how to do quantitative analysis with text-derived variables.** Students need worked examples of: how to visualise classifier output, how to build a simple time series from labelled data, how to interpret a regression with a text variable as the outcome.

---

## Alternative Organisation

Restructure around three parts:
1. Classifier validation in depth — use the students' own codebooks and test sets as the workshop material
2. From labels to measures — what distributions look like, how to visualise and interpret them
3. Nelson as worked example — deconstruct her pipeline explicitly: discovery → coding → classification → quantitative claim

---

## Readings

**Keep:**
- Nelson (2021) — assign selectively (methods + one analysis section, ~20 pp.)
- Greve et al. (2022) — reframe as mixed methods example; consider making optional

**Add:**
- Grimmer, Roberts & Stewart, "Text as Data" ch. 3 on validation (~15 pp.) — essential for understanding why and how to validate classifiers
- King, Gary, Patrick Lam & Margaret Roberts. "Computer-assisted keyword and document set discovery from unstructured text." *AJPS* 61.4 (2017): 971–988 — directly actionable for students building keyword lists
- Salganik, "Bit by Bit" ch. 3 on asking questions at scale (~20 pp.) — bridges qualitative coding to quantitative measurement
