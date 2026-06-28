> **Provenance:** Calibrated 2026-06-28 from the verified research corpus (see `01_STERN_ADCOM_KNOWLEDGE_BASE.md`
> and `sources/research_dossier.json`). This is the holistic scoring model the predictor applies to a complete
> applicant file. Anchored to the Class of 2027 (24% admit rate). Re-anchor when new class data publishes.

# NYU Stern FT MBA — Operational Holistic Scoring Rubric

**Anchor cycle:** Class of 2027 (entered Fall 2025), the most recent published profile. Overall admit rate **24%** (Stern self-reported, 4,933 apps / 1,161 admits / 336 enrolled). All calibration anchors below are drawn only from the verified corpus.

**How to use it (deterministic procedure):**
1. Score each of the 11 dimensions on the 1–5 anchored band (integers only; if between two bands, round to the band whose 5/3/1 descriptors match more of the file).
2. Compute **Weighted Dimension Total** = Σ(dimension score ÷ 5 × dimension weight). Weights sum to 100, so the max is 100.
3. Apply **Section D modifiers** as *additive points to the 0–100 total* (not multiplicative), capped as noted.
4. Map the **Adjusted Total** to a probability band via Section C.
5. Two trained readers should land within one band; the anchored descriptors + the explicit modifier table are what enforce that.

---

## (A) Scoring Dimensions and Weights

The corpus repeatedly establishes that Stern reads as **IQ + EQ co-equal** (not EQ-as-tiebreaker), runs **genuine holistic review** (every file read in full by multiple readers across academic potential / professional achievements & aspirations / alignment with Stern values), treats **stats as a gate not a linear scorer**, and that **pool segmentation is the single biggest swing on individual odds**. Weights reflect that hierarchy.

| # | Dimension (merged/renamed) | Weight | Justification from corpus |
|---|---|---|---|
| 1 | **Academic & Quantitative Readiness** (GPA + quant-rigor evidence, *separate from the test*) | 13 | One of three explicit holistic dimensions ("academic potential"). Gate, not linear, so weighted below the story factors. Avg GPA 3.64; quant readiness is the load-bearing element for waiver/quant-light files. |
| 2 | **Test Profile** (score-vs-waiver, normalized to scale) | 9 | Stats are a viability gate; 66% submit GMAT/GRE, only 39% GMAT. Waiver is a *legitimate path* (23% of class) but officially neutral/conditional, so it earns a modest standalone weight plus a Section-D modifier. |
| 3 | **Professional Impact & Trajectory** | 14 | Second explicit holistic dimension ("professional achievements"). Quantified impact and promotion velocity are the core differentiators consultants cite. |
| 4 | **Career Goals Clarity & Realism** | 11 | The 2026-27 load-bearing essay is the 500-word Professional Aspirations ("short-term goals…necessary next chapter…be specific"). Vague goals / no Plan B are named ding drivers. |
| 5 | **Stern-Specific Fit & "Why Stern / Why Now"** | 9 | "Necessary next chapter" wording; non-portable Why-Stern is the #1 career-essay failure mode. Distinct from goals because fit = Stern courses/clubs/NYC ecosystem + values alignment. |
| 6 | **IQ + EQ Evidence** (self-awareness, empathy, communication, self-management) | 11 | Stern's stated **core value**, co-equal to IQ. Surfaced across Pick Six, essays, endorsement, interview. A strong-stats / low-EQ profile is a Stern-specific screen-out. |
| 7 | **Leadership & Character** | 8 | Third holistic dimension ("alignment with Stern values"); the "Character" C that Gallogly says people underweight. Leadership without formal title still counts. |
| 8 | **Differentiation vs. Sub-Pool** | 9 | Corpus: pool segmentation moves individual odds the most. Finance is now 31% (crowded); veterans/non-traditional differentiate. Crowded-bucket files get capped here. |
| 9 | **Communication & Narrative Craft** (incl. Pick Six execution, authenticity gate) | 7 | "Insight over creativity"; Pick Six is the personality/values vehicle. Authenticity is a hard gate (rescission if essays not self-written) — see Section D. |
| 10 | **EQ Endorsement Strength** | 6 | Stern-unique; required from current supervisor; explicitly affects borderline cases. Third-party EQ validation Stern says it can't get any other way. |
| 11 | **Pool & Process Context** (round + demographic/citizenship + veteran institutional pull) | 3 | Round is a *marginal* adjustment per corpus; most of its and the veteran effect is captured in Section-D modifiers to avoid double-counting. Small base weight. |
| | **TOTAL** | **100** | |

---

## (B) Anchored 1–5 Band Scales

For each dimension: **5** = top-decile signal, **3** = at/near class median (competitive core), **1** = below the viability floor / active ding driver. (2 and 4 interpolate.)

### 1. Academic & Quantitative Readiness (w=13)
- **5** — GPA ≥3.89 (top of 80% band) *or* analytical/quant degree (Eng/Math/Sci/Econ) with strong grades; clear evidence of quant rigor (advanced calc/stats/econ, B+ or better). Quant readiness unquestionable.
- **3** — GPA ~3.64 (class avg), within 80% band (3.36–3.89); some quant coursework; no quant red flag. The competitive median.
- **1** — GPA <3.36 (below 10th pct) *with no offset* (no quant coursework, no quant job, no recommender quant testimony). A "weak stats without context" ding profile.

### 2. Test Profile (w=9) — normalize to one scale first
- **5** — GMAT 10th-ed ≥760 / Focus ≥725 / GRE ~167Q+ (top of 80% bands). Score is a clear asset and scholarship lever.
- **3** — At class average: GMAT 737 (10th-ed) / Focus 682 / GRE 164Q-163V; inside 80% bands (10th-ed 690–760; Focus 645–725).
- **1** — >~50 pts below the 80%-floor on the relevant scale (e.g., GMAT <650 10th-ed / Focus <595) *with no offset*; **or** a waiver/no-score from a quant-light, overrepresented profile that cannot demonstrate readiness. (A *granted, well-justified* waiver from a quant-strong profile scores 3, not 1 — see Section D.)

### 3. Professional Impact & Trajectory (w=14)
- **5** — Quantified P&L / cost / efficiency results ($ saved, % improved, scope/headcount), visible promotion velocity, brand-name or distinctive employer, increasing scope. Resume reads in civilian-legible quantified terms.
- **3** — Solid ~5 yrs experience (class avg 5.1), competent progression, real but modestly-quantified accomplishments. Median professional file.
- **1** — Thin/stagnant trajectory, no quantified impact, leads with duties/"readiness" language or jargon instead of results; experience far outside ~3–8 yrs without explanation.

### 4. Career Goals Clarity & Realism (w=11)
- **5** — Specific short-term role + function + org-type (e.g., "strategy at a growth-stage fintech"), credible given background, mapped to Stern's proven NYC pipelines, with a sensible contingency/Plan B.
- **3** — Reasonable goal stated but somewhat generic; plausible but not tightly linked to the applicant's trajectory; Plan B implied not stated.
- **1** — Vague ("leadership," "consulting" with no rationale), unrealistic given profile, or no backup plan. A named ding driver; default-consulting with no link is a blend-in signal.

### 5. Stern-Specific Fit & "Why Stern / Why Now" (w=9)
- **5** — Why-Stern is non-portable: names specific courses/professors/clubs/experiential offerings (e.g., Change:Studio), engages NYC finance/consulting/tech ecosystem, articulates why Stern is the *necessary* next chapter; evidence of alumni/event contact.
- **3** — Genuine but partly generic fit; some Stern specifics, some boilerplate that could fit another top program.
- **1** — Pasteable "Why Stern" usable at any top-15/25 school; prestige-seeking; no NYC/Stern-specific reasoning.

### 6. IQ + EQ Evidence (w=11)
- **5** — Rich, authentic evidence of self-awareness (candidly names a real weakness + growth), empathy, communication, self-management across essays/Pick Six/interview; collaborative, "others want to work with this person."
- **3** — Some EQ signal; pleasant and competent but not deeply self-aware; EQ implied rather than demonstrated.
- **1** — One-note high-achiever / "superhero" presentation; no self-awareness; surface-level answers; EQ absent — a Stern-specific screen-out even with strong stats.

### 7. Leadership & Character (w=8)
- **5** — Clear leadership with measurable team/mission impact (formal title not required), integrity/maturity signals, community/mentorship dimension beyond the job.
- **3** — Some leadership/teamwork evidence; solid but unremarkable; mostly individual-contributor with occasional lead roles.
- **1** — No leadership evidence; exclusively self-focused; poor judgment signal (e.g., inappropriate interview conduct) or character concern.

### 8. Differentiation vs. Sub-Pool (w=9)
- **5** — Distinctive within their micro-pool: rare background, or a common background (e.g., logistics officer, IB analyst) made distinctive via quantified results + a credible non-default goal + dimensions beyond work.
- **3** — Typical member of a represented bucket; competent but resembles many peers in the same sub-pool.
- **1** — Saturated/overrepresented bucket (finance 31%, consulting, generic engineer) presenting as interchangeable — same goal, same framing, no differentiator. SBC's #1 ding reason.

### 9. Communication & Narrative Craft (w=7)
- **5** — Cohesive, insightful (not flashy) narrative; Pick Six is a coherent themed portrait with "why-it-matters" captions; voice-consistent and clearly self-authored.
- **3** — Competent, clear writing; Pick Six adequate but partly literal/"photo-album"; narrative coherent but not memorable.
- **1** — Disjointed/generic essays; Pick Six is a second résumé (trophies/diplomas/office), one repeated trait, or over-engineered; instruction non-compliance. (If essays are not self-written → authenticity gate, Section D.)

### 10. EQ Endorsement Strength (w=6)
- **5** — From current supervisor; vivid, specific EQ anecdote; rates applicant Exceptional/Outstanding on key competencies incl. Emotional Intelligence; complements (not duplicates) the rest of the file.
- **3** — Solid, supportive endorsement from an appropriate endorser; positive but generic; no contradiction.
- **1** — Not from current supervisor without explanation; title-chasing pick; thin/lukewarm; or contradicts the applicant's self-presentation.

### 11. Pool & Process Context (w=3)
- **5** — R1/R2 timing for an overrepresented profile (best-case fill dynamics) *or* under-represented strong profile with full round eligibility; clean process discipline.
- **3** — Standard timing/eligibility, no flags.
- **1** — Late round (R3/R4) for a profile that needed early timing (overrepresented), or citizenship × round mismatch, or process red flags (missed instructions). *(Magnitude largely handled in Section D to avoid double-count.)*

---

## (C) Weighted Total → Admit Probability Band

**Anchoring logic.** The overall admit rate is **24%**, but the corpus is explicit that the headline rate is a *pool base rate, not an individual's odds*, and that a profile inside the middle-80% of admits is a **TARGET** (not a coin-flip 24%), while an on-profile-plus-differentiated file behaves like a **competitive ~50%** case (ARINGO band) and a top-decile file approaches **safe ~75–80%**. I therefore anchor the *middle* of the scale above the 24% mean (because a file that scores well on this rubric has already cleared the gate that most of the 76% rejected pool fails), and anchor the bottom *below* 24% (sub-gate / overrepresented-undifferentiated files are screen-outs). Bands are expressed as ranges, never single numbers (Menlo's "false precision" caution). The interview-invite reality (~20–30% invited, required for admission) means these are *pre-decision file-strength* probabilities; an actual interview invite shifts a file up one band.

| Adjusted Total (0–100, post-modifiers) | Verbal Tier | Admit Probability Band | Reading |
|---|---|---|---|
| **85–100** | Practically guaranteed / Safe | **70–80%** | Top-decile file; competitive for scholarship (R1/R2). |
| **72–84** | Strong / On-target+ | **50–65%** | Inside middle-80% with real differentiation; ARINGO "competitive→strong." |
| **58–71** | On-target | **33–48%** | Solid TARGET file; above the 24% mean because the gate is cleared. |
| **45–57** | Reach | **18–30%** | At/below median with thin differentiation, or one weak load-bearing dimension; near the pool mean. |
| **30–44** | Long reach | **8–16%** | Sub-gate stat with weak offsets, or overrepresented + undifferentiated; ARINGO "stretch." |
| **<30** | Highly unlikely | **2–6%** | Multiple ding drivers (vague goals + low EQ + saturated pool) or an authenticity/eligibility failure. |

> Two-reader determinism note: the band boundaries are 13–14 points wide, larger than the typical disagreement from a single off-by-one dimension score (max swing ≈ weight/5 ≈ 2.8 pts), so single-dimension disagreements keep both readers in the same band.

---

## (D) Explicit Modifiers (additive points to the 0–100 total)

Apply after computing the weighted total. Modifiers interact with profile (per corpus: penalties are *conditional*, not flat). Net modifier cap: **−15 to +12**.

| Modifier | Adjustment | Conditions / corpus basis |
|---|---|---|
| **Test waiver / no score — quant-STRONG profile** | **0 (neutral)** | Granted waiver + analytical degree / CFA-CPA / heavy modeling. Officially neutral; ~23% of class waived. No penalty. |
| **Test waiver / no score — quant-LIGHT or overrepresented profile** | **−6 to −10** | Waiver from a thin-quant or saturated-bucket file competing against peers who submit. Riskiest case; may not even be granted. |
| **Sub-median GPA / quant gap WITH offsets** | **−2** | Low stat but quant job, supplemental calc B+, or recommender quant testimony — "context-able." |
| **Sub-median GPA / quant gap WITHOUT offsets** | **−8 to −12** | "Weak stats without context" — an explicit rejection driver; ~50 pts below 80%-floor signals dropping a tier. |
| **Veteran / active-duty (FT pool)** | **+3** | 9% of class; recognized strength but *not* a standalone differentiator — scores still track class averages. Modest, not large. |
| **Veteran + strong Fertitta candidacy** | **+2 (admit) additional** | Institutional pull (Fertitta program, $30k flat tuition). Note: admission is the gate; no separate Fertitta app. Treat as a small additional admit nudge for a credible, differentiated veteran file. **Do NOT** assume a military test waiver — none exists for the FT MBA. |
| **Round 1** | **+2 overrepresented profile; +1 others** | R1 removes within-cohort fill risk; schools have more GMAT flexibility early; helps crowded buckets most. |
| **Round 2** | **0** | R1≈R2 for most profiles. Baseline. |
| **Round 3** | **−4 (most); −1 if rare/under-represented profile)** | Far fewer seats, often waitlist-driven, frequently no money. |
| **Round 4** | **−7; citizenship-eligibility check** | Thinnest round, largely waitlist; verify any citizenship restriction before relying on it. |
| **Authenticity gate (essays not self-written)** | **Hard fail → cap band at "Highly unlikely"** | Rescission rule; overrides the numeric total. |
| **Process non-compliance** (instruction violations, Pick Six format wrong, missing current-supervisor endorsement unexplained) | **−3 each, −6 cap** | Named ding drivers; detectable negative signals. |

**Scholarship vs. admit — treat separately (corpus-mandated).** Scholarship competitiveness keys heavily on **test score and round**, *independent of* admit probability:
- A granted waiver / no score is roughly **neutral on admit** (if quant-strong) but a **material negative on merit aid** — it removes the strongest scholarship lever.
- **R1/R2 favored** for scholarship; **R3/R4 and waitlist admits frequently arrive with no money.**
- Operationalize as a separate flag: *Scholarship-competitive* requires (score ≥ class avg on its scale) AND (R1 or R2) AND (Adjusted Total ≥72). Otherwise mark *Admit-plausible, scholarship-unlikely.* (Veteran Fertitta funding is a separate, near-automatic track that bypasses this for eligible scholars.)

---

## (E) Worked Example

**Profile:** Sub-median-quant veteran logistics officer, applying **R1 via test waiver** (no score). U.S. citizen. ~6 yrs service. GPA 3.45 (Political Science). Goal: defense-tech supply-chain operations. Strong quantified mission results; current-CO endorsement; coherent Pick Six.

**Step 1 — Dimension scores (×weight/5):**

| Dim | Score | Reasoning | Points |
|---|---|---|---|
| 1 Academic & Quant Readiness | 2 | GPA 3.45 in 80% band but qualitative major, no calc/stats evidence; quant readiness questionable. | 2/5×13 = 5.2 |
| 2 Test Profile | 2 | Waiver, no score; quant-light → cannot fully prove readiness via test. | 2/5×9 = 3.6 |
| 3 Professional Impact & Trajectory | 5 | Quantified logistics results (e.g., cut convoy downtime 40%, $X saved), real command scope. | 5/5×14 = 14.0 |
| 4 Career Goals Clarity & Realism | 4 | Specific (defense-tech supply chain), credible from logistics background, non-default; Plan B reasonable. | 4/5×11 = 8.8 |
| 5 Stern Fit / Why Now | 3 | Solid but only partly Stern-specific; some NYC/supply-chain hooks. | 3/5×9 = 5.4 |
| 6 IQ + EQ Evidence | 4 | Leadership-under-pressure, self-aware weakness named; strong EQ material. | 4/5×11 = 8.8 |
| 7 Leadership & Character | 5 | Command leadership, integrity, mentorship. | 5/5×8 = 8.0 |
| 8 Differentiation vs Sub-Pool | 4 | Logistics-officer pool is crowded, but quantified results + non-default defense-tech goal differentiate. | 4/5×9 = 7.2 |
| 9 Communication & Narrative | 4 | Coherent, civilian-legible, low jargon; themed Pick Six. | 4/5×7 = 5.6 |
| 10 EQ Endorsement | 5 | Current CO, vivid EQ anecdote. | 5/5×6 = 6.0 |
| 11 Pool & Process Context | 4 | R1, full eligibility, clean. | 4/5×3 = 2.4 |

**Weighted total = 5.2+3.6+14.0+8.8+5.4+8.8+8.0+7.2+5.6+6.0+2.4 = 75.0**

**Step 2 — Modifiers:**
- Test waiver, quant-light profile: **−6** (toward the lighter end — partly mitigated by exceptional quantified ops record, which is a quasi-offset).
- Sub-median quant WITH offset (quantified analytical job record): **−2**.
- Veteran (FT): **+3**.
- Veteran + credible Fertitta candidacy: **+2**.
- Round 1: **+1** (not an overrepresented industry bucket in the R1-fill sense, so +1).

Net modifier = −6 −2 +3 +2 +1 = **−2**.

**Step 3 — Adjusted Total = 75.0 − 2 = 73.0**

**Step 4 — Band:** 73 falls in **72–84 → "Strong / On-target+", admit probability ≈ 50–65%.**

**Step 5 — Scholarship flag:** No score + quant-light → fails the general *scholarship-competitive* test (which needs ≥avg score). **BUT** as a credible veteran he routes to the separate **Fertitta track** ($30k flat tuition, merit-based, not guaranteed) — so: *Admit-strong; general merit-aid unlikely; Fertitta scholarship plausible-but-not-automatic.*

**Result:** **~50–65% admit, R1 strong**, driven by elite quantified military trajectory + EQ + differentiation offsetting the quant/no-score drag; funding most likely via Fertitta rather than open merit aid.

---

**Guardrails honored:** every anchor (24% rate, 737/682/164-163, 3.64 GPA / 3.36–3.89 band, 9% veterans, Fertitta $30k, no FT military test waiver, IQ+EQ core value, 2026-27 essay set, R1≈R2, waiver-neutral-but-scholarship-costly) is taken directly from the verified corpus. No Stern facts were invented beyond it.
