# Lecture 6 Critique — Computer-Assisted Focused Coding and Text Classification

**Syllabus date:** 13 May
**Syllabus title:** Computer assisted focused coding and text classification
**Current folder:** Lecture 10 (to be renamed Lecture_06)

---

## Note on Duplicate Folder

The `Lecture_classification_quant_analysis/` folder contains near-identical content to this folder. It is a duplicate and should be moved to `archive/`. This folder (`Lecture 10/`) is the authoritative version.

Also: `Lecture 10/slides copy.md` is a stale duplicate — delete it.

---

## What Works

- The refugee solidarity movement worked example (from open coding to focused coding to theoretical contribution: compartmentalisation) is the best empirical illustration in the course. It walks students through the full arc from surprising observation to publishable finding.
- The transition from open to focused coding (different reading mode, different sampling strategy, index cases) is well-structured.
- Törnberg (2024) on LLM annotation best practices is timely and practically important — a strong choice.
- The Carlsen & Toubøl working paper as a reading for the same course example the instructor uses is a clever and cohesive design choice.

---

## Critiques

1. **Duplicate folder must be resolved.** `Lecture_classification_quant_analysis/` is identical content. Archive it.

2. **Several slides are image-only with no text.** Slides `image-5.png` through `image-10.png` are full-background images — content is opaque from the source. Add at minimum a title to each.

3. **Codebook section is thin.** The transition from focused coding to closed coding/codebook (3 slides) is compressed given its analytical importance. MacQueen et al. (1998) at 5 pages is too brief to ground robust codebook practice. The codebook is the pivot to quantification — it deserves more time.

4. **No decision framework for classifier type.** LLM classification, dictionary, and supervised ML are all listed as options but are not compared. Students need a clear decision framework: when do you use each? What are the trade-offs in terms of validity, cost, and required data?

5. **Midway evaluation embedded in lecture.** This recurring course activity takes up space inside a content lecture and creates disruption. Consider giving it a fixed slot (e.g., end of every lecture, or a standing 10-minute opening).

---

## Alternative Organisation

Split the lecture more explicitly into two halves:
- First half: qualitative (focused coding, index cases, worked example — the frame disputes study)
- Second half: the quantitative bridge (codebook, classifier options, validation framework)

Use the worked example as the bridge: "here is the qualitative finding — now here is how we turned it into a measurable variable." This makes the qual-to-quant transition visible and concrete rather than abstract.

---

## Readings

**Keep:**
- Timmermans & Tavory Ch. 6 ("Focused Coding") — essential
- MacQueen et al. (1998) — useful but supplement with more comprehensive codebook guidance
- Törnberg (2024) — essential for LLM classification
- Carlsen & Toubøl working paper — excellent course-integrated example

**Add or substitute:**
- Saldaña, Johnny. "The Coding Manual for Qualitative Researchers." SAGE (2021), ch. 1–2 (~30 pp.) — more comprehensive on codebook development than MacQueen alone
- Licht, Hauke & Slava Jankin. "Automated classification of political text using large language models." *Political Science Research and Methods* (2023) — a worked LLM classification example with proper validation
