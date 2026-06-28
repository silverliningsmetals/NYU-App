# NYU Stern Admissions Engine

An **AdCom-grade holistic predictor + material-improvement system** for Ryan Degnan's NYU Stern
Full-Time MBA application. It does what a stats calculator can't: it reads the *narrative* file —
essays, EQ endorsement, resume, Pick Six, goals, fit, pool context — and scores it the way a real
Stern admissions board member would, then tells you exactly what to change to move the number.

This is the qualitative complement to the **Grad-School-Blueprint** "Predict" tab (which is a
GMAT/GPA logistic stats model). Same family, different job: GSB answers *"are my numbers in range?"*;
this engine answers *"would a Stern reader admit this person, and how do I make them want to?"*

---

## What's in here

| File | Role |
|---|---|
| **`01_STERN_ADCOM_KNOWLEDGE_BASE.md`** | What a Stern reader *knows*. Class-profile benchmarks, the IQ+EQ doctrine, how every component is read, the FT test-waiver reality, the veteran/Fertitta lens, interview + decision mechanics, deadlines, and the full red-flag/green-flag catalog. Every hard fact is source-linked + confidence-flagged. Built by a 20-agent research+verification sweep across Stern official, Poets&Quants, Clear Admit, Menlo, mbaMission, Stacy Blackman, Service to School, GMAT Club. |
| **`02_STERN_PREDICTOR_RUBRIC.md`** | The scoring model. 11 weighted dimensions × anchored 1–5 bands, Section-D modifiers (waiver, veteran, round), and a calibrated total→probability mapping anchored to Stern's 24% rate. Deterministic enough that two readers land within one band. |
| **`03_APPLICANT_DOSSIER_Degnan.md`** | Ryan's profile, structured as the canonical predictor input. |
| **`03b_CURRENT_MATERIALS_VERBATIM.md`** | The actual current text of every component (what gets graded). Carries the ⚠️ prompt-set-change banner. |
| **`04_ASSESSMENT_Degnan_R1.md`** | **The output.** Admit probability, dimension scorecard, ranked risks, a sequenced upgrade plan, and concrete rewrites (incl. a fresh 500-word Professional Aspirations essay). Produced by a 5-reader adversarial AdCom panel + calibration. Re-generate whenever materials change. |
| **`sources/research_dossier.json`** | Raw verified findings from the research workflow (traceability). |

---

## The headline finding (2026-06-28)

**Stern changed the essay set for Ryan's cycle.** The 2026-27 Full-Time MBA essays (verified against the
live official page) are: **(1) Professional Aspirations, 500 words** — *"What are your short-term career
goals? Why is the Stern MBA the necessary next chapter in your professional story? Please be specific."* —
**(2) Pick Six**, **(3) Additional Information (optional, 500 words).** The **"Change: ___ it" essay and the
150-word short answer are gone.** Ryan's v5 package was built around both. The fix is repositioning, not
restarting — the material is strong and transfers — but it is the single highest-leverage action in the plan.

---

## How to use the engine (the loop)

1. **Keep the inputs current.** When Ryan edits a `.docx`, refresh `03b_CURRENT_MATERIALS_VERBATIM.md`
   (and `03_…_DOSSIER` if the profile facts change).
2. **Re-score.** Re-run the AdCom panel against the rubric to regenerate `04_ASSESSMENT_…`. The probability,
   risks, and upgrade plan update with the materials.
3. **Act on the plan**, top-to-bottom (it's ordered by probability impact × R1 deadline).
4. **Re-verify the facts** when the 2026-27 application formally opens (Summer 2026): class-profile numbers,
   the essay prompts, and deadlines. The knowledge base flags everything that needs a re-check.

---

## Extending to other schools (the generalization path)

The architecture is school-agnostic by design — only the knowledge base and rubric weights are Stern-specific:

- **Columbia & Cornell Johnson** (Ryan's other targets): clone this folder per school, re-run the research
  workflow with that school's official + consultant sources to build its `01_KNOWLEDGE_BASE`, re-weight the
  `02_RUBRIC` to that school's stated values (e.g., CBS's "why now"/cluster fit, Johnson's collaborative/
  immersion lens), then score the same dossier against it. The dossier (`03`) is reused unchanged.
- **Any top-20**: same recipe. The rubric's dimensions are universal; only the weights, benchmarks, and
  component mechanics change per school.
- Eventually this can fold into **Grad-School-Blueprint** as a per-school "holistic read" layer sitting
  beside the existing stats predictor.

---

*Built 2026-06-28. Predictions are decision-support, not guarantees — Stern runs genuine holistic review and
individual outcomes vary. Re-verify all hard facts at application open.*
