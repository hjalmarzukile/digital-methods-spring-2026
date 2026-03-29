# Lecture 4 Critique — Data Design and Data Collection

**Syllabus date:** 29 April
**Syllabus title:** Data Design and Data collection

---

## What Works

- The data integration typology (integrated, hierarchical/nested, transformation) is genuinely underrepresented in methods textbooks and highly useful for this course's design.
- Worked examples drawn from the instructor's own research (Ukrainian refugee solidarity groups, Danish Facebook pages via snowball sampling) are credible and motivating.
- Rafail (2018) on non-probability sampling for Twitter is an underused reference in digital methods courses and well-chosen.
- The sampling types taxonomy (actor-based, topic-based, location-based, mixed) is practical and directly applicable.

---

## Critiques

1. **~20 image-only slides in sequence.** Slides `image-10.png` through `image-22.png` are full-background images with no accompanying text in the markdown. The logical content is only visible in the rendered presentation and is opaque from the source file. Consider adding at minimum a title and one-line caption to each of these slides.

2. **Broken image reference.** The slide referencing `../lecture 2 Design and Research Question/analysisdesign_2.png` points to a folder that does not exist. Fix to a local copy of `analysisdesign_2.png` (available in `lecture 2/`).

3. **"What are important features of large-scale data" is an afterthought.** This slide (does the data have open text? scale? metadata?) is important but appears as a throwaway final item. It should be a structured checklist that connects forward to the text analysis pipeline.

4. **No practical tools guidance.** The lecture discusses API and webscraping in abstract terms without pointing to any practical resources. Many tools in common use (CrowdTangle, the old Twitter API) are now deprecated or changed. Students need at least a pointer to current working tools (PRAW for Reddit, Apify, etc.).

5. **Sequential design diagram references a non-existent folder path** (`../lecture 2 Design and Research Question/`). After folder tidying this will need updating.

6. **Confirmatory/complementary framework is repeated again here** (also in L1 and L8). If kept here, give it a new angle: this is the first time students are making actual data collection decisions based on this framework.

---

## Alternative Organisation

Consider restructuring as:
- First half: data integration types (conceptual, with worked examples) + mixed sampling ideals
- Second half: hands-on — students attempt a small test data collection in class using their chosen datasites, applying the sampling framework discussed

This shifts the lecture from conceptual to applied and gives students early exposure to the technical challenges before Milestone 2.

---

## Readings

**Keep:**
- Frederiksen, Toubøl & Carlsen data design chapter — core
- Rafail (2018) — non-probability sampling for social media
- Bang Carlsen, Gårdhus & Toubøl (2023) — use more explicitly as a worked example in slides

**Add:**
- Mohr, John W. et al. "Measuring culture" ch. 3 (~15 pp.) — on the structure of digital trace data, or substitute Salganik "Bit by Bit" ch. 2 if not assigned in Lecture 3
- A practical tool reference: current API documentation (PRAW, snscrape, or Apify) as a linked resource, not a reading
