# LODE
## Locus of Obligation under Directive Enscription
### A Precision-Field Theory of Written Instructional Authority in Social-Expressive Contexts

---

> *"The instruction was the same. The medium was different."*
> — Field notes, Washington Square Park, 13 March 2026

---

## What This Is

LODE is a formal theory of why written instructions and verbal offers with identical semantic content produce systematically different compliance rates — and what that difference reveals about the structure of instructional authority in social-expressive contexts.

The core claim is geometric: a written instruction and a verbal offer are not the same kind of object. A written instruction is a **field** — a potential function that acts on all agents who enter the context, independently of their relationship to the instruction-writer, suppressing individual variation in social disposition inside its semantic core. A verbal offer is a **vector** — directed, transient, and subject to the full machinery of social exchange cognition. Moving a behavior from written to verbal does not change its content. It changes its geometric type. And that change in type produces measurable, predictable, replicable differences in compliance.

LODE derives three formal results — a precision-weighted compliance differential (D1), a bandwidth asymmetry that deepens over session time (D2), and a bifurcation asymmetry that formally reverses a prediction of its parent framework ODES (D3) — from five explicit assumptions grounded in the active inference literature. All derivations are conditional on their stated assumptions. The quantitative estimates are pilot observations with unknown N and no computable confidence intervals. The framework is built from two field sessions. That ordering — data first, theory after — is stated at the front and governs every claim.

LODE answers three questions that ODES leaves open, operates upstream of ODES's expressive dynamics, and connects the precision-weighting mechanism of FERN to the concrete empirical structure of instructional media.

---

## Contents

- [Provenance](#provenance)
- [Part I — What ODES Leaves Open](#part-i--what-odes-leaves-open)
- [Part II — Core Assumptions](#part-ii--core-assumptions)
- [Part III — Formal Definitions](#part-iii--formal-definitions)
- [Part IV — Derivations](#part-iv--derivations)
- [Part V — Propositions, Observations, and Conjectures](#part-v--propositions-observations-and-conjectures)
- [Part VI — Measurement Protocols](#part-vi--measurement-protocols)
- [Part VII — Predictions for Replication](#part-vii--predictions-for-replication)
- [Part VIII — The LODE-ODES Interface](#part-viii--the-lode-odes-interface)
- [Part IX — Where the Framework Is Incomplete](#part-ix--where-the-framework-is-incomplete)
- [Part X — Connections to Prior Work](#part-x--connections-to-prior-work)
- [Part XI — Formal Status Summary](#part-xi--formal-status-summary)
- [The Claim](#the-claim)
- [Citations](#citations)

---

## Provenance

This framework is extracted from two field sessions. It was not designed in advance. All derivations run backward from data, not forward from prior theory.

**Session 1 — ODES founding experiment.** Large white sheet, elaborate hand-drawn poster bearing *ART ≠ IDEAS / TAKE SOME PAPER* in layered expressive letterforms, verbal instruction *DRAW A LINE* delivered by the experimenter at the moment of engagement. N unknown. Drawing compliance: ~100%. Souvenir compliance: ~100%. The souvenir instruction — *TAKE SOME PAPER* — was inscribed on the founding poster. Marks escalated from near-vertical tally strokes through loops, filled shapes, figurative marks, and terminated in a written propositional refutation of the poster's founding claim.

**Session 2 — LODE founding experiment.** Plain *DRAW A LINE* in block capitals at sheet center. Post-it notes offered verbally by the experimenter after drawing. Documented at 12:29 PM, 12:43 PM, and 1:04 PM. N unknown. Drawing compliance: ~100%. Souvenir compliance: ~80%. The ~20% who declined the post-it had all drawn. They were not disengaged.

**Limitations that govern every claim in this framework:** N is unknown for both sessions. The 20% refusal estimate has no computable confidence interval. No participant timing was recorded. No control condition, no randomization, no blinding. All quantitative claims are pilot estimates requiring controlled replication before being treated as established findings.

Three observations from these sessions are unexplained by ODES and motivate LODE:

**Observation 1 — The compliance split.** Drawing compliance was ~100%; souvenir compliance was ~80%. The difference is not explained by behavioral difficulty, content, or engagement level. The only variable distinguishing them is delivery modality: one was inscribed, one was verbally offered.

**Observation 2 — The falsification.** Expressive complexity escalated earlier in Session 2 (register τ₃ present at the first photograph, 12:29 PM) than in Session 1, despite Session 1 having a richer founding prompt. ODES-T4 predicts the opposite sign. This is a falsification of ODES-T4 within the domain where aesthetic authority co-scales with visual complexity — not a minor discrepancy, a sign reversal.

**Observation 3 — The inscription control.** Session 1 souvenir compliance (100%) is fully explained by the souvenir instruction being inscribed. Session 2's verbal offer reduced compliance by ~20%. Content was equivalent. Medium was not.

---

## Part I — What ODES Leaves Open

ODES-T1 (Attention Reallocation) governs what happens after an agent enters the expressive interaction: how attention shifts from the verbal instruction signal to the accumulated surface as session complexity grows. ODES-T2 (The Invariant) explains why near-zero bandwidth behaviors maintain compliance under this reallocation.

ODES provides no account of three adjacent questions:

**Compliance onset.** What governs whether an agent enters the interaction in the first place, and why this onset rate is insensitive to individual social variation for inscribed instructions?

**Founder effect direction.** Why do artistically accomplished founding prompts suppress rather than accelerate early register escapes, reversing ODES-T4?

**The compliance differential.** Why does moving a behavior from written to verbal reduce compliance by ~20%, independent of that behavior's content?

LODE answers these three questions. It is not a replacement for ODES. It governs the compliance phase that is upstream of the expressive dynamics ODES models. The two frameworks are architecturally adjacent, not competing.

---

## Part II — Core Assumptions

All derivations in LODE are conditional on these assumptions. They are stated as assumptions, not theorems. Each is supported by prior literature and identified as requiring empirical validation for this experimental population and context.

**[A1] Active Inference Architecture.** Agents are active inference systems minimizing variational free energy `F = E_q[log q(s) − log p(o,s)]` by selecting policies π that minimize expected free energy G(π). This assumption follows the Free Energy Principle (Friston, 2010) and is consistent with the FERN framework in this family.

**[A2] Precision-Weighted Priors.** The influence of an instructional signal on the agent's posterior over actions is proportional to the precision π assigned to the prior it creates. Precision is determined by the agent's generative model of the signal's reliability, which is a function of the delivery medium. This is a standard consequence of the Laplace approximation in active inference (Friston, 2010; Friston et al., 2021).

**[A3] Medium-Precision Correspondence.** Agents in this experimental population assign systematically higher precision to written instructions than to verbal offers from strangers, due to prior experience with written instructions as stable, institutionally embedded, re-verifiable norms. This is an empirical assumption about this population, not a universal claim. Cross-cultural generalizability is untested.

**[A4] Bandwidth Coupling of Verbal Evaluation.** Social exchange evaluation — deciding whether to accept a verbal offer from a stranger — requires the same finite cognitive bandwidth κ that competes with Pressure Landscape navigation in ODES-T1. Written instruction compliance, once the prior is set, does not require ongoing bandwidth allocation.

**[A5] Aesthetic Inhibition Mechanism.** Agents in a public expressive context experience an elevated effective crossing cost for marks that would fall in the register occupied by a visually dominant founding artifact. This social cost — the perceived risk of appearing derivative or presumptuous relative to a skilled founding mark — is positive and increases with the founding mark's aesthetic authority A₀.

---

## Part III — Formal Definitions

### 3.1 The Inscription Field

A written directive I in a social context defines a scalar **compliance potential field** over the space A of all possible agent behaviors:

```
Φ_I : A → [0, Φ₀]

Φ_I(a) = Φ₀ · exp(−d_sem(a, I) / σ_I)
```

where:

- `d_sem(a, I)` is the semantic distance between action `a` and directive I (§ Measurement Protocols, MP-1)
- `σ_I` is the semantic scope of I — the e-folding scale of the field; narrow for specific instructions, wide for general ones
- `Φ₀` is the inscription potential — the field amplitude, determined by medium precision π(medium) (§ 3.3)

The exponential kernel is the minimum-assumption model consistent with three requirements: (i) maximum field strength at the semantic core, (ii) continuous decay with semantic distance, (iii) asymptotic approach to zero for actions outside the instruction's scope. Alternative kernels (Matérn, squared-exponential) are possible; distinguishing between them requires multiple behaviors at known `d_sem` values within the same context.

### 3.2 Source Independence

A fundamental property distinguishing the Inscription Field from a verbal offer: `Φ_I` acts on all agents who encounter the context regardless of their relationship to the instruction-writer, the writer's presence, or the time elapsed since writing. This property follows from the definition — the field is a function of the context, not of a bilateral social relationship. A verbal offer lacks this property: it is directed at a specific addressee at a specific moment, and its force does not persist after the offer is made.

This definition-level distinction maps onto Berger and Luckmann's (1966) *objectivation*: the written instruction has been sedimented into a persistent external object whose authority is independent of its author. The Inscription Field formalizes objectivation as a potential function, replacing the binary (objectivated / not objectivated) with a continuous field that decays with semantic distance from the instruction's core.

### 3.3 Medium Precision

The inscription potential Φ₀ is a monotone function of the **medium precision** π(medium):

```
π(medium) = w₁ · τ̃_persist + w₂ · ρ̃_institutional + w₃ · ν̃_authority
```

where the three components are:

| Component | Symbol | Operational definition | Units |
|---|---|---|---|
| Temporal persistence | τ̃_persist | log₁₀(medium half-life in hours) | log-hours |
| Institutional density | ρ̃_institutional | Proportion of compliant agents citing written authority as reason (post-session survey, MP-2) | [0,1] |
| Authority indexicality | ν̃_authority | Mean authority rating from independent sample (MP-3) | [0,1] |

Weights w₁, w₂, w₃ are to be estimated empirically from the Medium Hierarchy Replication (§ Part VII, Replication 2). Until estimated, the framework treats them as equal: `w₁ = w₂ = w₃ = 1/3`.

**Predicted medium ordering (high to low π):** formal printed signage > expressive hand-drawn poster > plain handwritten instruction > typed personal message > verbal offer with observer present > verbal offer without observer.

This ordering is a conjecture [C1], not a derivation. It follows from A3 applied to the natural ranking of media on the three components, and requires the Medium Hierarchy Replication to confirm.

### 3.4 Semantic Distance d_sem

`d_sem(a, I)` measures the behavioral distance between action `a` and the semantic core of instruction I. For this experiment:

- `d_sem(draw a mark on the sheet | DRAW A LINE) ≈ 0` — the action is the semantic core
- `d_sem(take a post-it | DRAW A LINE) ≈ 1` — different behavioral category, no overlap in semantic scope

These are predicted values. The calibration sample described in MP-1 determines actual values before compliance data are analyzed.

### 3.5 Aesthetic Authority A₀

The aesthetic authority of a founding mark m₀ is its Fisher-Rao distance from the population's modal aesthetic prototype M̄_E:

```
A₀ = D_F(m₀, M̄_E)
```

where D_F uses the perceptual Riemannian metric g_E of the Expressive Field (ODES, Part II) — the unique metric measuring pure informational distinguishability between marks, independent of parameterization, established by Chentsov's theorem (1982).

High A₀ indicates that m₀ is far from what the typical participant in this population would produce unprompted. Low A₀ indicates proximity to the modal output. A plain text instruction occupies no position in the visual-expressive register of E; by construction, `A₀ = 0` for text-only instructions.

Measurement protocol: MP-4.

---

## Part IV — Derivations

Only formally derived results appear here. All derivations are conditional on the stated assumptions. No derivation claims more than its assumptions permit.

---

### Derivation 1 — Precision-Weighted Compliance Differential [D1]

**Setup.** An agent evaluates two policies: comply (`a_I`) and not comply (`a_¬I`). Under A1, the agent selects policy π by:

```
p(π) ∝ exp(−G(π))
```

where G(π) is expected free energy. Under the Laplace approximation (Friston, 2010, eq. 14), the log-odds of compliance are:

```
ln[P(comply) / P(not comply)] = π_signal · [E(comply) − E(not comply)] + ln[p₀(comply) / p₀(not comply)]
```

where π_signal is the precision of the instructional signal, `E(comply) − E(not comply)` is the expected utility contrast, and p₀ is the baseline social prior over actions.

**For a written instruction** (precision π_w by A2 and A3):

```
ln[P(comply) / P(not comply)] = π_w · Δ_utility + ln[p₀_ratio]
```

As `π_w → ∞`, this log-odds `→ ∞` and `P(comply) → 1`, independently of the agent's individual social prior p₀. The prior is overwhelmed by the high-precision signal.

**For a verbal offer** (precision `π_v << π_w` by A2 and A3):

```
ln[P(comply) / P(not comply)] = π_v · Δ_utility + ln[p₀_ratio]
```

Since π_v is low, the individual social prior substantially influences the posterior. For agents with `p₀_ratio < 1` — agents whose baseline is to decline unsolicited social exchange from strangers — the verbal offer may fail to shift the posterior to compliance. The refusal rate `R = P(p₀_ratio < threshold | π_v · Δ_utility)` is non-trivial and population-distributed.

**Result [D1].** Under A1, A2, A3:

- Written instructions with `π_w >> π_v` achieve `P(comply) → 1` as `π_w → ∞`, independently of individual social priors.
- Verbal offers with finite π_v achieve `P(comply) = F(π_v, population prior distribution) < 1`.

The **Inscription Premium** is:

```
ΔP = P(comply | written) − P(comply | verbal) > 0
```

Its magnitude is determined by the gap `π_w − π_v` and the population distribution of social priors. It is not further derivable without empirical estimates of both.

---

### Derivation 2 — Bandwidth Asymmetry [D2]

**Setup.** From ODES-T1, the attention allocated to instruction signal I_A at session time t is:

```
α_A(t) = κ · I_A / (I_A + I_B(t))
```

which decreases monotonically as `I_B(t)` — the information content of the accumulated surface — increases.

From A4: verbal offer evaluation uses bandwidth from the same pool that ODES-T1 governs. The bandwidth available for social exchange evaluation at time t is bounded above by `α_A(t) · κ`.

**Result [D2].** The effective precision available for verbal offer evaluation at session time t is:

```
π_v^eff(t) ≤ π_v · α_A(t) = π_v · κ · I_A / (I_A + I_B(t))  →  0   as I_B(t) → ∞
```

Since `P(comply | verbal, t)` is monotone in `π_v^eff(t)` by D1, verbal offer compliance decreases monotonically with session time.

For written instructions, compliance is governed by Φ_I whose amplitude Φ₀ is set at inscription and does not depend on session dynamics:

```
P(comply | written, t) ≈ P(comply | written, 0)   for all t
```

**Consequence.** The compliance differential `ΔP(t) = P(comply | written, t) − P(comply | verbal, t)` is **strictly increasing in t**.

**Empirical prediction [C2]:** Souvenir refusal rate should be lower in the first third of a session than in the final third. Early-session refusal ≈ 10–15%; late-session refusal ≈ 25–30%, integrating to the observed aggregate ≈ 20%. This prediction requires participant timing to be recorded in replication.

---

### Derivation 3 — Bifurcation Asymmetry [D3]

**Setup.** From ODES, the Register Bifurcation Condition is:

```
P_within(t; H₀) ≤ C_eff(τ_current → τ_next)
```

where `P_within(t; H₀)` is the maximum available pressure within the current register and `C_eff` is the effective crossing cost.

From A5, the effective crossing cost includes the **Founder's Shadow** — an aesthetic inhibition cost that scales with A₀:

```
C_eff(A₀) = C_ridge + C_shadow(A₀)     where C_shadow'(A₀) > 0
```

`T_escape` is the session time at which `P_within = C_eff`. Differentiating implicitly with respect to founding prompt richness H₀:

```
dT_escape/dH₀ = −(∂P_within/∂H₀ + ∂C_eff/∂A₀ · dA₀/dH₀) / (∂P_within/∂t)
```

Since `∂P_within/∂t < 0` (pressure within a register decreases as the session progresses), the denominator is negative. The sign of `dT_escape/dH₀` is determined by the numerator.

**Case 1 — Non-artful founding prompt (A₀ ≈ 0):** `dA₀/dH₀ ≈ 0`. The shadow cost term vanishes and `dT_escape/dH₀ ∝ −∂P_within/∂H₀`. Since richer founding marks preemptively compress within-register pressure, `∂P_within/∂H₀ < 0`, and the sign is negative: T_escape decreases with H₀. **ODES-T4 holds.**

**Case 2 — Artful founding prompt (A₀ grows with H₀):** `dA₀/dH₀ > 0`. The shadow cost term `∂C_eff/∂A₀ · dA₀/dH₀ > 0` counteracts the preemptive occupancy term. Sign reversal occurs when:

```
|∂C_eff/∂A₀ · dA₀/dH₀|  >  |∂P_within/∂H₀|
```

That is: the rate at which aesthetic authority increases with complexity outpaces the rate at which preemptive occupancy compresses within-register pressure. Under these conditions `dT_escape/dH₀ > 0`: T_escape increases with H₀. **ODES-T4 is reversed.**

**Result [D3].** ODES-T4 is a special case of a more general result. It holds when aesthetic authority and visual complexity are decoupled (`A₀ ≈ 0` or `dA₀/dH₀ ≈ 0`). It fails when aesthetic authority co-scales with complexity — the typical case for artistically accomplished founding prompts. The reversal condition is:

```
∂C_shadow/∂A₀ · dA₀/dH₀  >  |∂P_within/∂H₀|
```

Session 2's plain text instruction (`A₀ ≈ 0`) satisfies the ODES-T4 domain and produced earlier escalation. Session 1's artful poster (high A₀, high `dA₀/dH₀`) violates it and produced later escalation. The empirical result is consistent with D3.

---

## Part V — Propositions, Observations, and Conjectures

### Propositions [P] — follow from the model given stated assumptions; not derived from first principles

| ID | Statement |
|---|---|
| P1 | **Inscription Premium scaling:** ΔP is monotone increasing in `π(medium) − π_verbal`. As medium precision rises, compliance with inscribed behaviors approaches 1 while verbal offer compliance remains population-variable. |
| P2 | **Medium transfer:** for equivalent semantic content, moving a behavior from verbal to written raises its compliance by ΔP. Medium change is sufficient; content change is not required. |
| P3 | **Founder's Shadow is stronger in high-aesthetic-literacy populations:** C_shadow(A₀) scales with the agent's ability to perceive the authority gap `D_F(m₀, M̄_E)`, so populations with higher sensitivity to aesthetic distance experience stronger bifurcation suppression under artful founding prompts. |
| P4 | **Source independence test:** compliance with inscribed behaviors should be statistically indistinguishable between conditions where the experimenter is visibly present versus absent, controlling for all other factors. Verbal offer compliance will be sensitive to experimenter presence. |

### Pilot Observations [O] — what was actually measured, with their limitations stated

| ID | Observation | Uncertainty |
|---|---|---|
| O1 | Drawing compliance ≈ 100% in both sessions | N unknown; no CI computable; no observer-effect control |
| O2 | Souvenir compliance ≈ 80% in Session 2 (verbal offer) | N unknown; refusal count informal; estimate range 12–28% |
| O3 | Souvenir compliance ≈ 100% in Session 1 (inscribed souvenir) | Same limitations as O1 |
| O4 | Register τ₃ marks present at first photograph (12:29 PM, Session 2) | Photographs are snapshots; exact participant timing unknown |
| O5 | Session 2 post-it stack colors changed between 12:43 and 1:04 PM | Evidence of souvenir-taking activity; consistent with O2 |
| O6 | Founding yellow mark in Session 2 had two intentional endpoints (directed vector, not tally stroke) | Visible in photograph; interpretation of intentionality is inferential |

### Conjectures [C] — testable predictions from the model

| ID | Statement | Primary test |
|---|---|---|
| C1 | **Medium Hierarchy:** compliance rates follow the predicted ordering (formal signage > expressive poster > handwritten > verbal) | Medium Hierarchy Replication |
| C2 | **Temporal refusal gradient:** souvenir refusal rate increases monotonically across session time | Session 2 replication with participant timestamps |
| C3 | **Inscription Transfer:** writing *TAKE A POST-IT* on the sheet collapses souvenir refusal to ≈ 0% | Direct experiment, one modification |
| C4 | **Source independence:** inscribed compliance is statistically equivalent whether experimenter is present or absent; verbal compliance is not | 2×2 design (inscribed/verbal × present/absent) |
| C5 | **A₀ predicts T_escape:** A₀ computed prior to a session from MP-4 significantly predicts T_escape across sessions with varying founding prompts | OLS regression across minimum 8 sessions |
| C6 | **Partial inscription:** souvenir offered in written card form (intermediate medium precision) produces intermediate refusal rate between verbal (~20%) and inscribed-on-sheet (~0%) | Three-condition replication |

---

## Part VI — Measurement Protocols

All key quantities require operational definitions before the framework can be tested. These are stated as protocols, not realized measurements.

### MP-1: Semantic Distance d_sem

Recruit a calibration sample (N ≥ 30) from the same population as the experimental participants. Present each participant with instruction I and a list of candidate behaviors. For each behavior a, ask: "On a scale of 0–10, how much does [behavior a] count as following the instruction [I]?" Compute `d_sem(a, I) = 1 − (mean rating / 10)`. A rating of 10 → d_sem = 0 (semantic core); a rating of 0 → d_sem = 1 (no relation to the instruction).

*Expected values for this experiment:* `d_sem(draw any mark | DRAW A LINE) ≈ 0.05–0.15`. `d_sem(take a post-it | DRAW A LINE) ≈ 0.85–0.95`. These are predictions; the calibration sample determines actual values.

### MP-2: Institutional Density ρ_institutional

At session end, ask each compliant participant: "Why did you [draw on the sheet / take a piece of paper]?" Record verbatim. Code responses for medium-attribution language: "it said to," "it was written," "the sign said," "I read," "it was on the poster." ρ_institutional = proportion of compliant participants whose response includes medium-attribution language.

### MP-3: Authority Indexicality ν_authority

Photograph the instruction medium. Recruit a separate rating sample (N ≥ 30). Present photograph and ask: "On a scale of 0–10, how much authority does this instruction seem to have?" ν_authority = mean rating / 10.

### MP-4: Aesthetic Authority A₀

(i) Calibration sample (N ≥ 30, same population) given blank paper and asked to "make a mark without any instruction." Collect all marks. (ii) Code each mark by register τ and position in E (scale λ, weight w, color c, orientation θ). (iii) Compute modal mark M̄_E — the most frequently occurring register and modal parameter values within that register. (iv) For founding mark m₀, compute perceptual distance from M̄_E using register distance `d(τ_m₀, τ_M̄)` (discrete register gaps) plus Euclidean distance in the continuous parameters (λ, w, c, θ) weighted by the perceptual sensitivity coefficients from ODES.

*Convention:* A plain text instruction occupies no register in E's visual-expressive parameterization. A₀ = 0 by construction for text-only instructions.

### MP-5: Compliance Rate with Confidence Interval

Record for every participant: whether they drew (binary), whether they were offered the souvenir (binary), whether they accepted the souvenir (binary), and approximate time of interaction. With N ≥ 50, refusal rates can be estimated with 95% CI of approximately ±7 percentage points (binomial). With N = 100, ±5 percentage points. The founding experiments' N is unknown and below any computable precision threshold — all estimates are order-of-magnitude only.

---

## Part VII — Predictions for Replication

Each replication is linked to the derivation or conjecture it tests.

**Replication 1 — Inscription Transfer** *(tests C3, D1)*
Single modification to Session 2 design: add *TAKE A POST-IT* to the written instruction on the sheet. Expected result: souvenir compliance → ~100%. Required N ≥ 50 to detect a 20-percentage-point change at 80% power (two-proportion z-test, α = 0.05).

**Replication 2 — Medium Hierarchy** *(tests C1, P1)*
Five parallel sessions with identical drawn-instruction content but varying souvenir delivery medium: (a) inscribed on sheet, (b) printed card, (c) handwritten card, (d) verbal with observer present, (e) verbal alone. Prediction: compliance rates follow this ordering. Required N ≥ 40 per condition.

**Replication 3 — Temporal Refusal Gradient** *(tests C2, D2)*
Session 2 replication with participant timestamps recorded. Compute souvenir refusal rate by tertile of session time. Prediction: refusal rate in the final tertile significantly exceeds the first tertile. Linear trend test across tertiles.

**Replication 4 — Founder's Shadow** *(tests C5, D3)*
Minimum 8 sessions with systematically varying founding prompts: 2 high-A₀ / 2 moderate-A₀ / 2 low-A₀ / 2 A₀ = 0 (plain text). A₀ computed from MP-4 prior to each session. T_escape recorded as the participant count before the first non-linear mark appears. Prediction: T_escape higher in high-A₀ sessions than low-A₀ sessions, controlling for H₀. OLS regression of T_escape on A₀ and H₀ with interaction term.

**Replication 5 — Source Independence** *(tests P4, C4)*
2×2 design: (inscribed vs. verbal souvenir) × (experimenter present vs. absent during souvenir decision). Prediction: main effect of medium on compliance; no main effect of presence for the inscribed condition; significant effect of presence for the verbal condition.

---

## Part VIII — The LODE-ODES Interface

LODE and ODES govern formally adjacent but mechanistically distinct phases of the same interaction.

**LODE governs the compliance phase.** The agent approaches the shared surface. The Inscription Field exerts a compliance potential. The agent enters the expressive interaction — or does not. Output: binary entry decision. Governing object: Φ_I. `P(enter | inscribed behavior) → 1` for `π(medium) > π*`.

**ODES governs the expressive phase.** The agent navigates the Pressure Landscape `P(q|S_t)` of the accumulated surface, places a mark at the high-pressure frontier within bandwidth constraint, and exits. Governing object: `P(q|S_t)`. The written instruction has no role in this phase — it was fully processed at entry.

**The instruction does not drift in the ODES phase.** It was completed in the LODE phase. Every mark placed — including marks that bear no resemblance to a line — is the result of fully compliant LODE entry followed by ODES-governed navigation. Expressive complexity escalation does not indicate non-compliance. It indicates that the Pressure Landscape, not the instruction, governs expression once entry has been achieved.

**The Invariant, restated.** ODES-T2 explains why paper-taking persisted under expressive drift in Session 1 — near-zero bandwidth cost protects it from attention competition with the growing surface. LODE adds the upstream account: paper-taking persisted because it was inside the Inscription Field's semantic core, inscribed on the poster as *TAKE SOME PAPER*. The Invariant is the joint product of LODE compliance onset and ODES bandwidth protection.

Remove either mechanism and the invariant breaks. Remove the inscription (Session 2, verbal souvenir) and LODE compliance onset drops to ~80%, exposing the twenty percent whose behavior ODES-T2 cannot protect — because they never entered the Inscription Field for that behavior at all.

---

## Part IX — Where the Framework Is Incomplete

These are not rhetorical hedges. They are the open problems this framework has not solved.

**σ_I is unspecified.** The semantic scope parameter σ_I governs how sharply the Inscription Field decays with semantic distance from the instruction's core. It is not derivable from first principles — it must be estimated from compliance rates of multiple behaviors at known `d_sem` values within the same instruction context. A single two-behavior observation (drawing vs. souvenir) provides one constraint but does not determine σ_I.

**The compliance threshold distribution F(ε) is undetermined.** D1 establishes that the Inscription Premium depends on F(ε) — the population distribution of individual social compliance thresholds. The founding experiments give two data points: F(·) ≈ 1.0 for the inscribed condition, F(·) ≈ 0.80 for the verbal condition. This is insufficient to determine the shape of F.

**C_shadow(A₀) is not specified.** D3 shows that the sign of the bifurcation asymmetry depends on `∂C_shadow/∂A₀ · dA₀/dH₀`. The functional form of C_shadow — whether it is linear, concave, or convex in A₀ — is not derivable from current assumptions. It requires measurement across sessions with systematically varying A₀.

**A4 is an assumption, not a derivation.** That verbal offer evaluation competes for the same bandwidth as instruction-attention in ODES-T1 is stated as an assumption. A direct test would measure response time to verbal offers as a function of sheet complexity; slower response times under higher `I_B(t)` would confirm the coupling.

**Cross-cultural generalizability is untested.** A3 is stated as an empirical claim about this population (urban New York City, 2026). The ordering of media by precision may differ across cultural contexts where written authority is differently institutionalized. LODE's derivations hold within the domain defined by A3.

**N was not recorded in either founding session.** This is the most consequential gap. All quantitative estimates from both founding sessions are order-of-magnitude guesses. Any replication must record participant count and approximate interaction timing for each participant.

---

## Part X — Connections to Prior Work

Each citation is linked to the specific formal element it supports, not cited as general background.

**Friston (2010); Friston et al. (2021)** — Mechanistic foundation for D1. The precision-weighted prior formalism is the standard active inference treatment of how signal reliability governs posterior influence. LODE's contribution is identifying medium permanence as the empirical determinant of instructional prior precision — a specification not present in Friston's foundational accounts.

**Berger and Luckmann (1966)** — Source independence (§3.2). Objectivation is the sociological name for the property LODE formalizes as source-independence: written instruction authority independent of the author's presence. The Inscription Field is objectivation expressed as a potential function. Berger-Luckmann treat objectivation as binary; LODE replaces the binary with a continuous field decaying with semantic distance.

**Clark and Chalmers (1998)** — Supports A4 and MP-1. The extended mind hypothesis implies written instructions function as genuine cognitive components rather than merely external prompts, supporting the claim that written instruction compliance does not require ongoing bandwidth allocation once the prior is set.

**Tomasello et al. (2005)** — Scope condition. Compliance with written instructions requires the shared intentionality infrastructure for understanding written language as a directive addressed to a general reader. LODE's theorems apply within populations who have acquired this capacity.

**Mauss (1925)** — Mechanism for souvenir refusal in the verbal offer condition. The three obligations of gift exchange (to give, to receive, to reciprocate) explain what agents are declining when they decline the post-it. Moving the souvenir outside the Inscription Field's semantic core places it in the social exchange domain where Mauss's obligations govern. The twenty percent who declined are the fraction for whom reciprocity avoidance outweighs compliance tendency at precision π_v.

**Berger (1967); Searle (1995)** — Constitutive rules and the conditions under which written text creates social facts; supports the formal distinction between inscribed directives and verbal offers as different types of speech act with different authority structures.

**Prigogine and Nicolis (1977)** — Bifurcation structure underlying D3. The Register Bifurcation Condition from ODES is formally equivalent to the bifurcation condition in dissipative chemical systems. LODE's modification of C_eff via C_shadow(A₀) shifts the bifurcation threshold without changing the underlying mechanism.

**Rao (1945); Chentsov (1982)** — Operationalization of A₀ via Fisher-Rao distance. Chentsov's theorem establishes that the Fisher-Rao metric is the unique invariant metric on the space of probability distributions, making `A₀ = D_F(m₀, M̄_E)` the natural measure of aesthetic distinctiveness — not a chosen metric but the one mandated by the geometry of the Expressive Field.

**Sperber and Wilson (1986)** — Medium permanence as amplifier of relevance implicature; supports the medium precision ordering and the claim that inscribed instructions carry stronger epistemic authority than spoken equivalents.

---

## Part XI — Formal Status Summary

| ID | Statement | Type | Conditional on |
|---|---|---|---|
| D1 | Precision-weighted compliance: `P(comply\|written) → 1`; `P(comply\|verbal) = F(π_v, priors)` | [D] | A1, A2, A3 |
| D2 | Bandwidth asymmetry: `P(comply\|verbal, t)` monotone decreasing in t | [D] | A1, A2, A3, A4, ODES-T1 |
| D3 | Bifurcation asymmetry: sign of `dT_escape/dH₀` depends on `∂C_shadow/∂A₀ · dA₀/dH₀` | [D] | A5, ODES bifurcation condition |
| P1 | ΔP is monotone in `π(medium) − π_verbal` | [P] | D1 + medium precision order |
| P2 | Medium change (verbal → written) raises compliance without content change | [P] | D1 + A3 |
| P3 | Founder's Shadow is stronger in high aesthetic-literacy populations | [P] | A5 + population variation |
| P4 | Source independence: inscribed compliance invariant to experimenter presence | [P] | §3.2 definition |
| O1 | Drawing compliance ≈ 100% (both sessions) | [O] | Pilot; N unknown; no CI |
| O2 | Souvenir compliance ≈ 80% (Session 2, verbal) | [O] | Pilot; N unknown; no CI |
| O3 | Souvenir compliance ≈ 100% (Session 1, inscribed) | [O] | Pilot; N unknown; no CI |
| O4 | Session 2 register τ₃ at first photograph | [O] | Pilot; timestamps only |
| C1 | Medium Hierarchy ordering holds | [C] | Replication 2 |
| C2 | Temporal refusal gradient | [C] | Replication 3 |
| C3 | Inscription Transfer collapses refusal | [C] | Replication 1 |
| C4 | Source independence test | [C] | Replication 5 |
| C5 | A₀ predicts T_escape across sessions | [C] | Replication 4 |
| C6 | Partial inscription yields intermediate refusal | [C] | Replication 2 variant |

**Assumptions requiring empirical validation:** A3 (medium-precision correspondence in this population), A4 (bandwidth coupling of verbal evaluation), A5 (aesthetic inhibition mechanism). None is derivable from first principles. Each is supported by prior literature but not established for this experimental context.

### Concept Glossary

| Concept | Formal definition | Status |
|---|---|---|
| Inscription Field Φ_I | `Φ₀·exp(−d_sem(a,I)/σ_I)`; compliance potential over behavior space A | Definition |
| Locus of obligation | `a ∈ A` with `d_sem(a,I) ≈ 0`; region of maximum field potential | Definition |
| Source independence | Φ_I acts on all agents in context, independent of social relationship to author | Definition (objectivation) |
| Medium precision π | `w₁τ̃ + w₂ρ̃ + w₃ν̃`; weights to be estimated empirically | Model assumption |
| Inscription Premium ΔP | `P(comply\|written) − P(comply\|verbal)`; pilot estimate ≈ 0.20 | Observation + D1 |
| Aesthetic authority A₀ | `D_F(m₀, M̄_E)` under g_E | Definition + MP-4 |
| Founder's Shadow | C_shadow(A₀) inflates effective crossing cost; delays early register escape | D3 |
| Bandwidth asymmetry | `π_v^eff(t)` decreasing; `Φ_w(t)` constant | D2 |
| Bilateral vector | Verbal offer: directed, transient, socially evaluated; not a field | Definition |
| LODE-ODES interface | LODE governs compliance entry; ODES governs expressive navigation post-entry | Architecture |

---

## The Claim

A written instruction and a verbal offer with identical semantic content produce systematically different compliance rates because they are different geometric objects — not because their content differs.

A written instruction is a **field**: a potential function that acts on all agents who enter the context, independently of their relationship to the instruction-writer. Inside its semantic core, the potential is high and individual variation in social disposition is suppressed. Outside the semantic core, the field decays and social cognition governs.

A verbal offer is a **vector**: directed, transient, and socially evaluated. It requires the full machinery of social exchange cognition to process. Approximately twenty percent of the relevant population in this experimental context experiences the social exchange activation energy of a verbal offer as exceeding their compliance tendency at precision π_v. The written instruction had been suppressing this fraction throughout the interaction by operating as a high-precision prior. The verbal offer, arriving outside the written scope, exposed it.

The twenty percent did not become visible because they were reluctant.

They became visible because the Inscription Field had ended.

---

## Citations

**Active Inference**

Friston, K.J. (2010). The free-energy principle: a unified brain theory? *Nature Reviews Neuroscience* 11: 127–138.

Friston, K.J., Wiese, W., and Hobson, J.A. (2021). Sentience and the existential imperative. *Entropy* 23(12): 1675.

Ramstead, M.J.D., Badcock, P.B., and Friston, K.J. (2018). Answering Schrödinger's question: a free-energy formulation. *Physics of Life Reviews* 24: 1–16.

**Institutional Reality and Objectivation**

Austin, J.L. (1962). *How to Do Things with Words.* Oxford University Press.

Searle, J.R. (1995). *The Construction of Social Reality.* Free Press.

Berger, P.L. and Luckmann, T. (1966). *The Social Construction of Reality.* Doubleday.

**Extended Mind and Distributed Cognition**

Clark, A. and Chalmers, D. (1998). The extended mind. *Analysis* 58(1): 7–19.

Hutchins, E. (1995). *Cognition in the Wild.* MIT Press.

**Communication and Relevance**

Sperber, D. and Wilson, D. (1986). *Relevance: Communication and Cognition.* Harvard University Press.

**Shared Intentionality**

Tomasello, M., Carpenter, M., Call, J., Behne, T., and Moll, H. (2005). Understanding and sharing intentions: the origins of cultural cognition. *Behavioral and Brain Sciences* 28(5): 675–691.

**Social Compliance**

Cialdini, R.B. (1984). *Influence: The Psychology of Persuasion.* HarperCollins.

Mauss, M. (1925/1990). *The Gift.* Trans. Halls. Routledge.

**Bifurcation and Non-Equilibrium Dynamics**

Prigogine, I. and Nicolis, G. (1977). *Self-Organization in Non-Equilibrium Systems.* Wiley.

Prigogine, I. (1977). Time, Structure and Fluctuations. Nobel Lecture, 8 December 1977.

**Fisher-Rao Geometry**

Rao, C.R. (1945). Information and accuracy attainable in the estimation of statistical parameters. *Bulletin of the Calcutta Mathematical Society* 37: 81–91.

Chentsov, N.N. (1982). *Statistical Decision Rules and Optimal Inference.* American Mathematical Society.

**Cultural Transmission**

Kirby, S., Cornish, H., and Smith, K. (2008). Cumulative cultural evolution in the laboratory. *PNAS* 105(31): 10681–10686.

---

*Framework: LODE · ODES · FELD · FERN · GRAIN*

*Status tags: [D] = Formally derived from stated assumptions · [P] = Model proposition · [O] = Pilot observation (N unknown, no CI) · [C] = Testable conjecture · [A] = Explicit assumption*

*Derived from two field sessions at Washington Square Park, New York City, 13 March 2026. N was not recorded in either session. This limitation defines exactly what must be controlled in replication.*

![20260313_180845000_iOS](https://github.com/user-attachments/assets/deb8c40b-492c-46c6-8638-e3a98018d3ef)

![20260313_180907000_iOS](https://github.com/user-attachments/assets/3a6070e8-3fce-4c4a-a7ef-acd36f3a7b51)

![20260313_180914000_iOS](https://github.com/user-attachments/assets/fa228d9a-3f71-4aba-8688-5de5eb7f8e0c)

<img width="590" height="1278" alt="20260313_180949000_iOS" src="https://github.com/user-attachments/assets/6e3f6694-1fce-4790-83bc-f381c603987e" />






