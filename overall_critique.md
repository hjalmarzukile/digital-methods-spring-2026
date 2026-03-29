# Overall Course Critique: Digital Methods Spring 2026

## Folder Structure Problems

**Duplicate and orphan folders:**
- Two `lecture 3` folders: `lecture 3/` and `lecture 3 Find, evaluate and select datasite(s)/` — need to be merged; the latter is the primary version
- `archieve /lecture 2/` — archive of old lecture 2 content (note: "archieve" is a typo; should be "archive")
- `Lecture_classification_quant_analysis/` — unnumbered folder with content identical to `Lecture 10/`; a duplicate
- `Lecture 10/slides copy.md` and `Lecture_classification_quant_analysis/slides copy.md` — stale duplicate files to delete

**Inconsistent naming conventions:**
- Mixed capitalisation: `Lecture 1`, `lecture 2`, `lecture 3`, `Lecture 5` — needs standardising
- Some folders include long descriptions in the name, others do not

**Critical structural mismatch — slide folders vs. syllabus:**
The current syllabus has 8 lectures but the slide folders run up to Lecture 13 plus extras. Folder numbers do not match syllabus lecture numbers. For example:
- Syllabus Lecture 5 (computer-assisted discovery) corresponds to the **Lecture 9** folder
- Syllabus Lecture 6 (focused coding) corresponds to **Lecture 10**
- **Lecture 5, 6, 7, 8** folders contain material from an older version of the course (interviews, netnography, networks, text-as-data intro) — not in the current syllabus

**Proposed folder structure after tidying:**

| New name | Source folder | Syllabus lecture |
|---|---|---|
| `Lecture_01/` | `Lecture 1/` | L1: What is Mixed Digital Methods |
| `Lecture_02/` | `lecture 2/` | L2: Research Questions and Design |
| `Lecture_03/` | `lecture 3 Find, evaluate and select datasite(s)/` | L3: Find, Evaluate, Select Datasites |
| `Lecture_04/` | `lecture 4/` | L4: Data Design and Collection |
| `Lecture_05/` | `Lecture 9/` | L5: Computer-Assisted Discovery and Open Coding |
| `Lecture_06/` | `Lecture 10/` | L6: Focused Coding and Classification |
| `Lecture_07/` | *(no folder — needs to be created)* | L7: Text Classification and Quantitative Analysis |
| `Lecture_08a/` | `Lecture 11/` | L8: Mixed Analysis Design |
| `Lecture_08b/` | `Lecture 12/` | L8: Quality of Data and Inference |
| `Lecture_Outro/` | `Lecture 13/` | Outro |
| `archive/` | all old/duplicate folders | — |

---

## Overall Strengths

- The sequential qual-to-quant analysis design is a coherent and distinctive pedagogical architecture that distinguishes this course from both pure qualitative and pure computational methods courses.
- Worked examples from the instructor's own research (Ukrainian refugee groups, refugee solidarity frames, prepping communities) are excellent and create continuity across lectures.
- Grounding in Timmermans & Tavory and Kozinets gives students a proper qualitative tradition, not just a computational one.
- The four-milestone structure scaffolds project work well across the semester.

---

## Overall Gaps and Recommendations

### 1. Netnography has no dedicated lecture
The current syllabus covers netnography only via readings (Kozinets Ch. 8 and 10) in Lecture 3, but the slide content in the old `Lecture 6/` folder (netnography) is strong. Consider adding a dedicated session — possibly by splitting L3 into L3a (finding/scouting) and L3b (netnography and ethics), or integrating key netnography concepts explicitly into L3 slides.

### 2. Interviews have no dedicated lecture
The old `Lecture 5/` folder (interview data collection) contains solid content. Even 20 minutes on when and why to do interviews to ground a digital analysis belongs in the course. Grigoropoulou & Small (2022) already motivates this.

### 3. Network analysis is completely absent
The old `Lecture 7/` folder has solid visual network analysis content. The course description explicitly mentions "exploratory network analysis" as a learning outcome, making this a significant omission. A half-lecture on visual network analysis as a tool for representing and sampling one's datasite would close the gap.

### 4. Reading load is uneven
- Lecture 3: ~99 pages (heaviest)
- Lecture 8: 0 pages ("TBA")
Redistribution is needed. Kozinets Ch. 10 (immersion journal, 29 pp.) is used minimally in L3 slides — move it to L5/L6 where it is actually applied.

### 5. Practical/technical guidance is thin
Students collect data via APIs and webscraping, build classifiers, and run quantitative analyses, but the slides contain almost no practical technical guidance. A standing "technical resources" section per lecture, or a dedicated practical skills document linked from the syllabus, would reduce student friction.

### 6. The old Lecture 8 folder (text-as-data background)
This folder covers the conceptual foundation (deductive vs. inductive approaches, grounded theory, computational grounded theory) that is now orphaned. Its content should be absorbed as the opening section of the Lecture 5 slides before the discovery methods are introduced.

### 7. No slides exist for Syllabus Lecture 7
Syllabus L7 (text classification and quantitative text analysis) has no dedicated slide folder. This needs to be created. The `Lecture_classification_quant_analysis/` folder is a partial duplicate of L6 content, not a standalone L7.

### 8. Confirmatory/complementary framing is over-repeated
This framework is introduced in L1, repeated in L4 (data collection design), and again in L8 (analysis design). Either build it progressively with new depth at each stage, or introduce it once with clear forward references.

---

## Reading Load Summary

| Lecture | Current pages | Assessment |
|---|---|---|
| L1 | ~39 pp. | Appropriate |
| L2 | ~34 pp. | Appropriate |
| L3 | ~99 pp. | Too heavy — redistribute |
| L4 | ~68 pp. | Heavy but defensible |
| L5 | ~57 pp. | Appropriate |
| L6 | ~58 pp. (est.) | Appropriate |
| L7 | ~90 pp. | Heavy — trim Nelson |
| L8 | 0 pp. (TBA) | Needs readings |

---

## Proposed New/Replacement Readings

| Lecture | Reading | Reason |
|---|---|---|
| L1 | Rogers, "Doing Digital Methods" ch. 1 (~15 pp.) | Properly grounds "methods of the medium" |
| L1 | boyd & Crawford, "Critical Questions for Big Data" (2012) | Motivates mixed approach from critical angle |
| L2 | Timmermans & Tavory, "Abductive Analysis" ch. 1 (~20 pp.) | Introduces abduction early as epistemological spine |
| L3 | Franzke et al., "Internet Research: Ethical Guidelines 3.0" AoIR (2020) | More current ethics guidance for digital trace data |
| L3 | Salganik, "Bit by Bit" ch. 2 | Structure of found/digital data |
| L4 | Mohr et al., "Measuring Culture" ch. 3 | Digital trace data structure |
| L5 | Grimmer, Roberts & Stewart, "Text as Data" ch. 2 (make required) | Philosophical foundation for computational text analysis |
| L5 | Blei, "Probabilistic Topic Models" CACM (2012) | Accessible LDA explainer |
| L6 | Saldaña, "The Coding Manual" ch. 1–2 | More comprehensive on codebook development |
| L6 | Licht & Jankin, "Automated classification of political text using LLMs" (2023) | Worked LLM classification example with validation |
| L7 | Grimmer, Roberts & Stewart, "Text as Data" ch. 3 | Validation for classifiers |
| L7 | King, Lam & Roberts, "Computer-assisted keyword and document set discovery" AJPS (2017) | Actionable keyword discovery method |
| L8 | Seawright & Gerring, "Case selection techniques" PRQ (2008) | Justifies qualitative case selection |
| L8 | Creswell, "Qualitative Inquiry" ch. on validity | Quality criteria for qualitative work |
| Outro | Markham, "Fabrication as ethical practice" (2012) | Ethics of representation of online subjects |
| Outro | D'Ignazio & Klein, "Data Feminism" ch. 1 | Closing critical provocation |
