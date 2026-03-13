# LODE
## Locus of Obligation under Directive Enscription
### A Precision-Field Theory of Written Instructional Authority in Social-Expressive Contexts

*"The instruction was the same. The medium was different."*
— Field notes, Washington Square Park, 13 March 2026

---

## Provenance

This framework is extracted from two field sessions, not designed in advance. Derivations are backward from data, not from prior theory.

**Session 1 (ODES founding experiment)**: Large white sheet, elaborate hand-drawn poster (ART ≠ IDEAS / TAKE SOME PAPER), instruction DRAW A LINE, N unknown. Every participant drew. Every participant took paper. Expressive marks began as tally strokes and escalated through loops, fills, figurative marks, and propositional text.

**Session 2 (LODE founding experiment)**: Plain DRAW A LINE in block capitals at sheet center. Post-it notes offered verbally by the experimenter after drawing. N unknown, session documented at 12:29 PM, 12:43 PM, and 1:04 PM. Drawing compliance: approximately 100%. Souvenir compliance: approximately 80%. The ~20% who declined the post-it had all drawn — they were not disengaged.

**Limitations that govern all claims:** N is unknown for both sessions. The 20% refusal estimate has no computable confidence interval. No participant timing was recorded. There was no control condition, no randomization, and no blinding. All quantitative claims in this framework are pilot estimates requiring controlled replication before being treated as established.

Three observations are unexplained by ODES and motivate LODE:

1. Drawing compliance was ~100%; souvenir compliance was ~80%. The difference is not explained by behavioral difficulty, content, or engagement level. The only variable that distinguishes them is delivery modality: one was inscribed; one was verbally offered.

2. Expressive complexity escalated earlier in Session 2 (register τ₃ present at first photograph) than in Session 1, despite Session 1 having a richer founding prompt. ODES-T4 predicts the opposite sign. This is a falsification, not a minor discrepancy.

3. The Session 1 souvenir compliance (100%) is fully explained by the souvenir being inscribed — "TAKE SOME PAPER" on the founding poster. Moving it to a verbal offer reduced compliance by ~20%. Content was equivalent; medium was not.

---

## Part I — What ODES Leaves Open

ODES-T1 (Attention Reallocation) governs what happens after an agent enters the expressive interaction: how attention shifts from the instruction signal to the accumulated surface as session complexity grows. ODES-T2 (The Invariant) explains why near-zero bandwidth behaviors maintain compliance under this reallocation.

ODES provides no account of three adjacent questions:

**Compliance onset**: What governs whether an agent enters the interaction in the first place, and why this rate is insensitive to individual social variation for inscribed instructions?

**Founder effect direction**: Why do artful founding prompts suppress rather than accelerate early register escapes, reversing ODES-T4?

**Compliance differential**: Why does moving a behavior from written to verbal reduce compliance by ~20%, independent of the behavior's content?

LODE answers these three questions. It is not a replacement for ODES — it governs the compliance phase upstream of the expressive dynamics ODES models.

---

## Part II — Core Assumptions

All derivations in LODE are conditional on these assumptions. They are stated here as assumptions, not theorems.

**[A1] Active Inference Architecture**: Agents are active inference systems minimizing variational free energy F = E_q[log q(s) − log p(o,s)] by selecting policies π that minimize expected free energy G(π). This assumption follows the Free Energy Principle (Friston, 2010) and is consistent with the FERN framework in this family.

**[A2] Precision-Weighted Priors**: The influence of an instructional signal on the agent's posterior over actions is proportional to the precision π assigned to the prior it creates. Precision is determined by the agent's generative model of the signal's reliability, which is a function of the delivery medium. This is a standard consequence of the Laplace approximation in active inference (Friston, 2010; Friston et al., 2021).

**[A3] Medium-Precision Correspondence**: Agents in this experimental population assign systematically higher precision to written instructions than to verbal offers from strangers, due to prior experience with written instructions as stable, institutionally embedded, re-verifiable norms. This is an empirical assumption about this population, not a universal claim.

**[A4] Bandwidth Coupling of Verbal Evaluation**: Social exchange evaluation (deciding whether to accept a verbal offer from a stranger) requires the same finite cognitive bandwidth κ that competes with Pressure Landscape navigation in ODES-T1. Written instruction compliance, once the prior is set, does not require ongoing bandwidth allocation.

**[A5] Aesthetic Inhibition Mechanism**: Agents in a public expressive context experience an elevated effective crossing cost for marks that would fall in the register occupied by a visually dominant founding artifact. This social cost — the perceived risk of appearing derivative or presumptuous relative to a skilled founding mark — is positive and increases with the founding mark's aesthetic authority A₀.

---

## Part III — Formal Definitions

### 3.1 The Inscription Field

A written directive I in a social context defines a scalar compliance potential field over the space A of all possible agent behaviors:

**Φ_I : A → [0, Φ₀]**

**Φ_I(a) = Φ₀ · exp(−d_sem(a, I) / σ_I)**

where:
- **d_sem(a, I)** is the semantic distance between action a and directive I [§ Measurement Protocols, MP-1]
- **σ_I** is the semantic scope of I — the e-folding scale of the field; narrow for specific instructions, wide for general ones
- **Φ₀** is the inscription potential — the field amplitude, determined by medium precision π(medium) [§ 3.3]

The exponential kernel is the minimum-assumption model consistent with: (i) maximum field strength at the semantic core, (ii) continuous decay with semantic distance, (iii) asymptotic approach to zero for actions far outside the instruction's scope. Alternative kernels (Matérn, squared-exponential) are possible; testing between them requires multiple behaviors at known d_sem values.

### 3.2 Source Independence

A fundamental property distinguishing the Inscription Field from a verbal offer: Φ_I acts on all agents encountering the context regardless of their relationship to the instruction-writer, the writer's presence, or the time elapsed since writing. This property follows from the definition — the field is a function of the context, not of a bilateral social relationship. A verbal offer lacks this property: it is directed at a specific addressee at a specific moment, and its force does not persist after the offer is made.

This definition-level distinction maps onto Berger and Luckmann's (1966) objectivation: the written instruction has been sedimented into a persistent external object whose authority is independent of its author. The Inscription Field formalizes objectivation as a potential function, replacing the binary (objectivated / not objectivated) with a continuous field that decays with semantic distance.

### 3.3 Medium Precision

The inscription potential Φ₀ is a monotone function of the medium precision π(medium):

**π(medium) = w₁ · τ̃_persist + w₂ · ρ̃_institutional + w₃ · ν̃_authority**

where the three components are:

| Component | Symbol | Operational definition | Units |
|---|---|---|---|
| Temporal persistence | τ̃_persist | log₁₀(medium half-life in hours) | log-hours |
| Institutional density | ρ̃_institutional | Proportion of compliant agents citing written authority as reason (post-session survey, [MP-2]) | [0,1] |
| Authority indexicality | ν̃_authority | Mean authority rating from independent sample [MP-3] | [0,1] |

Weights w₁, w₂, w₃ are to be estimated empirically from the Medium Hierarchy Replication [§ Predictions, P-2]. Until estimated, the framework treats them as equal (w₁ = w₂ = w₃ = 1/3).

**Predicted medium ordering (high to low π)**: formal printed signage > expressive hand-drawn poster > plain handwritten instruction > typed personal message > verbal offer with observer present > verbal offer without observer.

This ordering is a conjecture [C1], not a derivation. It follows from A3 applied to the natural ranking of media on the three components, but requires the Medium Hierarchy Replication to confirm.

### 3.4 Semantic Distance d_sem

For the specific behaviors in this experiment:
- d_sem(draw a mark on the sheet | DRAW A LINE) ≈ 0: the action is the semantic core of the instruction
- d_sem(take a post-it | DRAW A LINE) ≈ 1: different behavioral category, no overlap in semantic scope

General measurement protocol: see [MP-1]. d_sem is not free-floating — it is empirically determined from a separate rating sample before analyzing compliance data.

### 3.5 Aesthetic Authority A₀

The aesthetic authority of a founding mark m₀ is its Fisher-Rao distance from the population's modal aesthetic prototype M̄_E:

**A₀ = D_F(m₀, M̄_E)**

where the Fisher-Rao metric D_F uses the perceptual Riemannian metric g_E of the Expressive Field (ODES, Part II). High A₀ indicates that m₀ is far from what the typical participant in this population would produce unprompted. Low A₀ indicates that m₀ is near the modal output — as for a plain text instruction, which occupies no position in the visual-expressive register of E at all (A₀ ≈ 0 by construction).

Measurement protocol: [MP-4].

---

## Part IV — Derivations

Only formally derived results appear here. All derivations are conditional on the stated assumptions.

### Derivation 1: Precision-Weighted Compliance Differential [D1]

**Setup**: An agent evaluates two policies — comply (a_I) and not comply (a_¬I). Under A1, the agent selects policy π by:

p(π) ∝ exp(−G(π))

where G(π) is expected free energy. Under the Laplace approximation (Friston, 2010, eq. 14), the log-odds of compliance are:

ln[P(comply) / P(not comply)] = π_signal · [E(comply) − E(not comply)] + ln[p₀(comply) / p₀(not comply)]

where π_signal is the precision of the instructional signal, E(comply) − E(not comply) is the expected utility contrast, and p₀ is the baseline social prior over actions.

**For a written instruction** (precision π_w by A2 and A3):

ln[P(comply) / P(not comply)] = π_w · Δ_utility + ln[p₀_ratio]

As π_w → ∞, this log-odds → ∞ and P(comply) → 1, independently of the agent's individual social prior p₀. The prior is overwhelmed by the high-precision signal.

**For a verbal offer** (precision π_v << π_w by A2 and A3):

ln[P(comply) / P(not comply)] = π_v · Δ_utility + ln[p₀_ratio]

Since π_v is low, the second term — the individual social prior — substantially influences the posterior. For agents with p₀_ratio < 1 (agents whose baseline is to decline unsolicited social exchange from strangers), the verbal offer may fail to shift the posterior to compliance. The refusal rate R = P(p₀_ratio < threshold | π_v · Δ_utility) is non-trivial and population-distributed.

**Result [D1]**: Under A1, A2, A3, written instructions with π_w >> π_v achieve P(comply) → 1 as π_w → ∞, independently of individual social priors. Verbal offers with finite π_v achieve P(comply) = F(π_v, population prior distribution), which is less than 1 and individually variable. The compliance differential is:

ΔP = P(comply | written) − P(comply | verbal) > 0

This is the **Inscription Premium**. Its magnitude is determined by the gap π_w − π_v and the population distribution of social priors. It is not further derivable without empirical estimates of both.

---

### Derivation 2: Bandwidth Asymmetry [D2]

**Setup**: From ODES-T1, the agent's attention allocated to instruction signal I_A at session time t is:

α_A(t) = κ · I_A / (I_A + I_B(t))

which decreases monotonically as I_B(t) increases.

From A4: verbal offer evaluation uses bandwidth from the same pool that ODES-T1 governs (the residual after Pressure Landscape navigation). The bandwidth available for social exchange evaluation at time t is bounded above by α_A(t) · κ.

**Result [D2]**: The effective precision available for verbal offer evaluation at session time t is:

π_v^eff(t) ≤ π_v · α_A(t) = π_v · κ · I_A / (I_A + I_B(t)) → 0 as I_B(t) → ∞

Since P(comply | verbal, t) is monotone in π_v^eff(t) by D1, the compliance probability for verbal offers decreases monotonically with session time.

For written instructions, compliance is governed by the field Φ_I whose amplitude Φ₀ is set at time of inscription and does not depend on session dynamics. P(comply | written, t) ≈ P(comply | written, 0) for all t.

**Consequence**: The compliance differential ΔP(t) = P(comply | written, t) − P(comply | verbal, t) is strictly increasing in t.

**Empirical prediction [C2]**: Souvenir refusal rate should be lower in the first third of a session than in the final third. Early-session refusal ≈ 10–15%; late-session refusal ≈ 25–30%, integrating to the observed aggregate ≈ 20%. This prediction requires participant timing to be recorded in replication.

---

### Derivation 3: Bifurcation Asymmetry [D3]

**Setup**: From ODES, the Register Bifurcation Condition is:

P_within(t; H₀) ≤ C_eff(τ_current → τ_next)

where P_within(t; H₀) is the maximum available pressure within the current register and C_eff is the effective crossing cost.

From A5, C_eff includes the shadow cost:

C_eff(A₀) = C_ridge + C_shadow(A₀)    where C_shadow'(A₀) > 0

T_escape is the session time at which P_within = C_eff. Differentiating implicitly with respect to H₀:

dT_escape/dH₀ = −(∂P_within/∂H₀ + ∂C_eff/∂A₀ · dA₀/dH₀) / (∂P_within/∂t)

Since ∂P_within/∂t < 0 (pressure within a register decreases as the session progresses), the denominator is negative. The sign of dT_escape/dH₀ is determined by the numerator:

**When A₀ ≈ 0 (non-artful founding prompt)**: dA₀/dH₀ ≈ 0, and dT_escape/dH₀ ∝ −∂P_within/∂H₀. Since richer founding marks preemptively compress within-register pressure (∂P_within/∂H₀ < 0), the sign is negative: T_escape decreases with H₀. ODES-T4 holds.

**When A₀ grows with H₀ (artful founding prompt)**: dA₀/dH₀ > 0, and the shadow cost term ∂C_eff/∂A₀ · dA₀/dH₀ > 0 counteracts the preemptive occupancy term. Sign reversal occurs when:

**|∂C_eff/∂A₀ · dA₀/dH₀| > |∂P_within/∂H₀|**

That is: the rate at which aesthetic authority increases with complexity outpaces the rate at which preemptive occupancy compresses within-register pressure. Under these conditions dT_escape/dH₀ > 0: T_escape increases with H₀, and ODES-T4 is reversed.

**Result [D3]**: ODES-T4 is a special case of a more general result. It holds when aesthetic authority and visual complexity are decoupled (A₀ ≈ 0 or dA₀/dH₀ ≈ 0). It fails when aesthetic authority co-scales with complexity, which is the typical case for artistically accomplished founding prompts. The condition for ODES-T4 reversal is:

∂C_shadow/∂A₀ · dA₀/dH₀ > |∂P_within/∂H₀|

The founding experiment's plain text instruction (A₀ ≈ 0) satisfies the ODES-T4 domain; its artful poster (high A₀, high dA₀/dH₀) violates it. The empirical result — earlier escalation under the plainer prompt — is consistent with D3.

---

## Part V — Propositions, Observations, and Conjectures

### Propositions [P] — claims that follow from the model given stated assumptions, but are not formally derived from first principles

| ID | Statement |
|---|---|
| P1 | The Inscription Premium ΔP is monotone increasing in π(medium) − π_verbal. As medium precision rises, compliance with inscribed behaviors approaches 1 while verbal offer compliance remains population-variable. |
| P2 | For equivalent semantic content, moving a behavior from the verbal to the written medium raises its compliance by ΔP. The medium change is sufficient; content change is not required. |
| P3 | The Founder's Shadow suppression of early register escapes is stronger in populations with higher mean aesthetic literacy (higher sensitivity to the distance D_F(m₀, M̄_E)), because C_shadow(A₀) scales with the agent's ability to perceive the authority gap. |
| P4 | The source-independence of the Inscription Field implies that compliance with inscribed behaviors should be statistically indistinguishable between conditions where the experimenter is visibly present versus absent, controlling for all other factors. Verbal offer compliance will be sensitive to experimenter presence. |

### Pilot Observations [O] — what was actually measured in the founding experiments, with their limitations

| ID | Observation | Uncertainty |
|---|---|---|
| O1 | Drawing compliance ≈ 100% in both sessions | N unknown; no CI computable; no observer-effect control |
| O2 | Souvenir compliance ≈ 80% in Session 2 (verbal offer) | N unknown; refusal count is informal; estimate could be 12–28% |
| O3 | Souvenir compliance ≈ 100% in Session 1 (inscribed souvenir) | Same limitations as O1 |
| O4 | Register τ₃ marks present at first photograph (12:29 PM, Session 2) | Photographs are snapshots; exact participant timing unknown |
| O5 | Session 2 post-it stack colors changed between 12:43 and 1:04 PM | Evidence of souvenir-taking activity; consistent with O2 |
| O6 | Founding yellow mark in Session 2 had two intentional endpoints (directed vector, not tally stroke) | Visible in photograph; interpretation of intentionality is inferential |

### Conjectures [C] — testable predictions

| ID | Statement | Primary test |
|---|---|---|
| C1 | Medium Precision Hierarchy: compliance rates follow the predicted ordering (formal signage > expressive poster > handwritten > verbal) | Medium Hierarchy Replication [§ Replication] |
| C2 | Temporal Refusal Gradient: souvenir refusal rate increases monotonically across session time | Session 2 replication with participant timestamps |
| C3 | Inscription Transfer: writing "TAKE A POST-IT" on the sheet collapses souvenir refusal to ≈ 0% | Direct experiment with one modification |
| C4 | Source Independence: inscribed behavior compliance is statistically equivalent whether experimenter is present or absent; verbal offer compliance is not | 2×2 design (inscribed/verbal × present/absent) |
| C5 | A₀ Predicts Bifurcation Timing: A₀ computed prior to the session from [MP-4] significantly predicts T_escape across sessions | Regression across minimum 8 sessions with varying founding prompts |
| C6 | Bandwidth-Coupled Refusal: providing souvenir offer in written card form (intermediate medium precision) produces intermediate refusal rate between verbal (~20%) and inscribed-on-sheet (~0%) | Three-condition replication |

---

## Part VI — Measurement Protocols

All key quantities require operational definitions before the framework can be tested. These are stated here as protocols, not as realized measurements.

### MP-1: Semantic Distance d_sem

**Procedure**: Recruit a calibration sample (N ≥ 30) from the same population as the experimental participants. Present each participant with the instruction I and a list of candidate behaviors. For each behavior a, ask: "On a scale of 0–10, how much does [behavior a] count as following the instruction [I]?" d_sem(a, I) = 1 − (mean rating / 10). A rating of 10 → d_sem = 0 (behavior is the semantic core); a rating of 0 → d_sem = 1 (behavior has no relation to the instruction).

**For this experiment**: d_sem(draw any mark on the sheet | DRAW A LINE) would be calibrated by this procedure. The expectation is d_sem ≈ 0.05–0.15 (near-complete semantic alignment). d_sem(take a post-it note | DRAW A LINE) is expected to be ≈ 0.85–0.95 (near-complete semantic non-overlap). These are predictions, not measurements — the calibration sample would determine actual values.

### MP-2: Institutional Density ρ_institutional

**Procedure**: At session end, ask each participant who complied: "Why did you [draw on the sheet / take a piece of paper]?" Record verbatim. Code responses for presence of medium-attribution language: "it said to," "it was written," "the sign said," "I read," "it was on the poster." ρ_institutional = proportion of compliant participants whose response includes medium-attribution language.

### MP-3: Authority Indexicality ν_authority

**Procedure**: Photograph the instruction medium (poster, sheet, card, etc.). Recruit a separate rating sample (N ≥ 30). Present photograph and ask: "On a scale of 0–10, how much authority does this instruction seem to have?" ν_authority = mean rating / 10.

### MP-4: Aesthetic Authority A₀

**Procedure**: (i) Calibration sample (N ≥ 30, same population) given blank paper and asked to "make a mark without any instruction." Collect all marks. (ii) Code each mark by register τ and position in E (scale λ, weight w, color c, orientation θ). (iii) Compute modal mark M̄_E from the distribution — the most frequently occurring register and modal parameter values within that register. (iv) For founding mark m₀, compute perceptual distance from M̄_E using register distance d(τ_m₀, τ_M̄) (which counts register gaps as discrete steps) plus Euclidean distance in the continuous parameters (λ, w, c, θ) weighted by the perceptual sensitivity coefficients from ODES. This compound measure is A₀.

A plain text instruction occupies no register in E's visual-expressive parameterization; by convention A₀ = 0 for text-only instructions.

### MP-5: Compliance Rate with Confidence Interval

**Procedure**: Record every participant: whether they drew (binary), whether they were offered the souvenir (binary), whether they accepted the souvenir (binary), and approximate time of interaction. With N ≥ 50 participants, refusal rates can be estimated with 95% CI of approximately ±7 percentage points (assuming binomial sampling). With N = 100, ±5 percentage points. The founding experiment's N is unknown and below any computable precision threshold — all its estimates are order-of-magnitude only.

---

## Part VII — Where the Framework is Incomplete

These are not rhetorical hedges. They are the open problems this framework has not solved.

**σ_I is unspecified**: The semantic scope parameter σ_I of the Inscription Field governs how sharply the field decays with distance from the semantic core. It is not derivable from first principles — it must be estimated from the compliance rates of multiple behaviors at known d_sem values within the same instruction context. A single two-behavior observation (drawing vs. souvenir) provides one constraint on σ_I but does not determine it.

**The compliance threshold distribution F(ε) is undetermined**: D1 establishes that the Inscription Premium depends on F(ε) — the population distribution of individual social compliance thresholds. The founding experiments give two data points: F(·) ≈ 1.0 for the inscribed condition, F(·) ≈ 0.80 for the verbal condition. This is insufficient to determine the shape of F. Multiple medium precisions and multiple behavioral contexts are needed.

**C_shadow(A₀) is not specified**: D3 shows that the sign of the bifurcation asymmetry depends on ∂C_shadow/∂A₀ · dA₀/dH₀. The functional form of C_shadow — whether it is linear, concave, or convex in A₀ — is not derivable from current assumptions. It requires measurement across sessions with systematically varying A₀.

**A4 (bandwidth coupling of verbal evaluation) is an assumption, not a derivation**: The key step in D2 — that verbal offer evaluation competes for the same bandwidth as instruction-attention in ODES-T1 — is stated as an assumption. A direct test would measure response time to verbal offers as a function of sheet complexity; slower response times under higher I_B(t) would confirm the coupling.

**Cross-cultural generalizability is untested**: A3 (medium-precision correspondence) is stated as an empirical claim about the specific experimental population (urban New York City, 2026). The ordering of media by precision may differ across cultural contexts where written authority is differently institutionalized. LODE's theorems hold within the domain defined by A3; their generalizability is a conjecture, not a derivation.

**N was not recorded in either founding session**: This is the most consequential gap. All quantitative estimates from both founding sessions are order-of-magnitude guesses. Any replication must record participant count and approximate session timing for each interaction.

---

## Part VIII — Predictions for Replication

If LODE is correct, the following should hold. Each prediction is linked to the derivation or conjecture it tests.

**Replication 1 — Inscription Transfer (tests C3, D1)**
Single modification to Session 2 design: add "TAKE A POST-IT" to the written instruction on the sheet. Expected result: souvenir compliance → ~100%. Required N ≥ 50 to detect a 20-percentage-point change at 80% power (two-proportion z-test, α = 0.05).

**Replication 2 — Medium Hierarchy (tests C1, P1)**
Five parallel sessions with identical drawn-instruction content but varying souvenir delivery medium: (a) inscribed on sheet, (b) printed card, (c) handwritten card, (d) verbal with observer present, (e) verbal alone. Prediction: compliance rates follow this ordering. Required N ≥ 40 per condition to detect ordering with adequate power.

**Replication 3 — Temporal Refusal Gradient (tests C2, D2)**
Session 2 replication with participant timestamps recorded. Compute souvenir refusal rate by tertile of session time. Prediction: refusal rate in final tertile significantly exceeds refusal rate in first tertile. Linear trend test across tertiles.

**Replication 4 — Founder's Shadow (tests C5, D3)**
Minimum 8 sessions with systematically varying founding prompts: 2 high-A₀ / 2 moderate-A₀ / 2 low-A₀ / 2 A₀ = 0 (plain text). A₀ computed from MP-4 prior to each session. T_escape recorded as participant count before first non-linear mark appears. Prediction: T_escape is higher in high-A₀ sessions than low-A₀ sessions, controlling for H₀. OLS regression of T_escape on A₀ and H₀ with interaction term.

**Replication 5 — Source Independence (tests P4, C4)**
2×2 design: (inscribed vs. verbal souvenir) × (experimenter present vs. absent during souvenir decision). Prediction: main effect of medium on compliance; no main effect of presence for inscribed condition; significant effect of presence for verbal condition.

---

## Part IX — The LODE-ODES Interface

LODE and ODES govern formally adjacent but mechanistically distinct phases of the same interaction.

**LODE governs the compliance phase**: the agent approaches the shared surface, the Inscription Field exerts a compliance potential, the agent enters the expressive interaction (or does not). Output: binary entry decision. Governing object: Φ_I. P(enter for inscribed behavior) → 1 for π(medium) > π*.

**ODES governs the expressive phase**: the agent navigates the Pressure Landscape P(q|S_t) of the accumulated surface, places a mark at argmax_{q ∈ E\S_t} P(q|S_t) within bandwidth constraint, and exits. Governing object: P(q|S_t). The written instruction has no role in this phase — it was fully processed at entry.

The instruction does not drift in the ODES phase. It was completed in the LODE phase. Every mark placed — including marks that bear no resemblance to a line — is the result of fully compliant LODE entry followed by ODES-governed navigation. Complexity escalation does not indicate non-compliance. It indicates that the Pressure Landscape, not the instruction, governs expression once entry is achieved.

**The Invariant restated**: ODES-T2 explains why paper-taking (Session 1) persists under expressive drift — near-zero bandwidth cost protects it from attention competition. LODE adds the upstream account: paper-taking persisted because it was inside the Inscription Field's semantic core (inscribed on the poster as "TAKE SOME PAPER"). The Invariant is the joint product of LODE compliance onset and ODES bandwidth protection. Remove either mechanism and the invariant may break: remove the inscription (Session 2, verbal souvenir) and LODE compliance onset drops to ~80%, exposing the twenty percent whose behavior ODES-T2 cannot protect because they never entered the compliance field for that behavior at all.

---

## Part X — Connections to Prior Work

Each citation is linked to the specific formal element it supports.

**Friston (2010); Friston et al. (2021)** — Mechanistic foundation for D1. The precision-weighted prior formalism is the active inference framework's standard treatment of how the reliability of a signal governs its influence on the posterior. LODE's contribution is identifying medium permanence as the empirical determinant of instructional prior precision, which is not stated in Friston's foundational accounts.

**Berger and Luckmann (1966)** — Source-independence (§3.2). Objectivation is the sociological name for the property that LODE formalizes as source-independence: the written instruction's authority is independent of its author's presence. The Inscription Field is objectivation expressed as a potential function. Berger-Luckmann treat objectivation as binary; LODE replaces the binary with the continuous Inscription Field.

**Clark and Chalmers (1998)** — Supports A4 and MP-1. The extended mind hypothesis implies that written instructions function as genuine cognitive components rather than merely as external prompts. This supports the assumption that written instruction compliance does not require ongoing bandwidth (the instruction is part of the cognitive system, not a competitor for bandwidth). It also supports MP-1: semantic distance to the instruction is cognitive distance within the agent's extended system.

**Tomasello et al. (2005)** — Scope condition on all LODE claims. Compliance with written instructions requires the shared intentionality infrastructure for understanding written language as a directive addressed to a general reader. This is a culturally acquired cognitive capacity. LODE's theorems apply within the population of agents who have acquired this capacity; their cross-cultural generalizability is untested.

**Mauss (1925)** — The three obligations of gift exchange (to give, to receive, to reciprocate) explain the social dynamics of souvenir refusal in the verbal offer condition. Agents declining the post-it are not being disengaged — they are declining the obligation-structure of the gift-exchange frame. LODE formalizes this: moving the souvenir out of the Inscription Field's semantic core places it in the social exchange domain where Mauss's obligations govern. The twenty percent who declined are the fraction for whom reciprocity avoidance outweighs compliance tendency at the verbal offer's precision level π_v.

**Prigogine and Nicolis (1977); Prigogine Nobel Lecture (1977)** — The bifurcation structure underlying D3. The Register Bifurcation Condition from ODES (P_within ≤ C_eff) is formally equivalent to the bifurcation condition in dissipative chemical systems (driving parameter exceeds critical threshold). LODE's modification of C_eff via C_shadow(A₀) shifts the bifurcation threshold without changing the underlying mechanism.

**Rao (1945); Chentsov (1982)** — Operationalization of A₀ via Fisher-Rao distance. Chentsov's theorem establishes that the Fisher-Rao metric is the unique invariant metric on the space of probability distributions. For the Expressive Field E, the perceptual Riemannian metric g_E approximates the Fisher-Rao metric (the unique measure of pure informational distinguishability between marks, independent of parameterization). A₀ = D_F(m₀, M̄_E) is therefore the appropriate measure of aesthetic distinctiveness — not a chosen metric but the natural one given ODES's geometric structure.

---

## Part XI — Formal Status Summary

| ID | Statement | Type | Conditional on |
|---|---|---|---|
| D1 | Precision-weighted compliance: P(comply\|written) → 1; P(comply\|verbal) = F(π_v, priors) | [D] | A1, A2, A3 |
| D2 | Bandwidth asymmetry: P(comply\|verbal, t) monotone decreasing in t | [D] | A1, A2, A3, A4, ODES-T1 |
| D3 | Bifurcation asymmetry: sign of dT_escape/dH₀ depends on ∂C_shadow/∂A₀ · dA₀/dH₀ | [D] | A5, ODES bifurcation condition |
| P1 | ΔP is monotone in π(medium) − π_verbal | [P] | D1 + medium precision order |
| P2 | Medium change (verbal → written) raises compliance without content change | [P] | D1 + A3 |
| P3 | Founder's Shadow is stronger in high aesthetic-literacy populations | [P] | A5 + population variation |
| P4 | Source independence: inscribed compliance invariant to experimenter presence | [P] | §3.2 definition |
| O1 | Drawing compliance ≈ 100% (both sessions) | [O] | Pilot; N unknown; no CI |
| O2 | Souvenir compliance ≈ 80% (Session 2, verbal) | [O] | Pilot; N unknown; no CI |
| O3 | Session 2 register τ₃ at first photograph | [O] | Pilot; timestamps only |
| C1 | Medium Hierarchy ordering | [C] | Replication 2 |
| C2 | Temporal refusal gradient | [C] | Replication 3 |
| C3 | Inscription Transfer collapses refusal | [C] | Replication 1 |
| C4 | Source independence test | [C] | Replication 5 |
| C5 | A₀ predicts T_escape across sessions | [C] | Replication 4 |
| C6 | Partial inscription yields intermediate refusal | [C] | Replication 2 variant |

**Assumptions that require empirical validation**: A3 (medium-precision correspondence in this population), A4 (bandwidth coupling of verbal evaluation), A5 (aesthetic inhibition mechanism). None of the three is derivable from first principles. They are supported by prior literature (Berger-Luckmann for A3; ODES-T1 structure for A4; Gombrich schema-correction for A5) but not established for this experimental context.

---

## Summary Table

| Concept | Formal definition | Status |
|---|---|---|
| Inscription Field Φ_I | Φ₀·exp(−d_sem(a,I)/σ_I); compliance potential over A | Definition |
| Locus of obligation | a ∈ A with d_sem(a,I) ≈ 0; maximum field potential | Definition |
| Source independence | Φ_I acts on all agents in context, independent of social relationship to author | Definition (objectivation) |
| Medium precision π | w₁τ̃ + w₂ρ̃ + w₃ν̃; weights to be estimated empirically | Model assumption |
| Inscription Premium ΔP | P(comply\|written) − P(comply\|verbal); pilot estimate ≈ 0.20 | Observation + D1 |
| Aesthetic authority A₀ | D_F(m₀, M̄_E) under g_E | Definition + MP-4 |
| Founder's Shadow | C_shadow(A₀) inflates effective crossing cost; delays early bifurcation | D3 |
| Bandwidth asymmetry | Φ_v(t) decreasing; Φ_w(t) constant | D2 |
| Bilateral vector | Verbal offer: directed between two parties, socially evaluated, not a field | Definition |
| LODE-ODES interface | LODE governs compliance entry; ODES governs expressive navigation post-entry | Architecture |

---

## The Claim

A written instruction and a verbal offer with identical semantic content produce systematically different compliance rates because they are different geometric objects, not because their content differs.

A written instruction is a field: a potential function that acts on all agents who enter the context, independently of their relationship to the instruction-writer. Inside its semantic core, the potential is high and individual variation in social disposition is suppressed. Outside the semantic core, the field decays and social cognition governs.

A verbal offer is a vector: directed, transient, and socially evaluated. It requires the full machinery of social exchange cognition to process. Approximately twenty percent of the relevant population in this experimental context experiences the social exchange activation energy of a verbal offer as exceeding their compliance tendency. The written instruction had been suppressing this fraction throughout the interaction by operating as a high-precision prior. The verbal offer, arriving outside the written scope, exposes it.

The twenty percent did not become visible because they were reluctant. They became visible because the Inscription Field had ended.

---

## Citations

**Active Inference**
Friston, K.J. (2010). The free-energy principle: a unified brain theory? *Nature Reviews Neuroscience* 11: 127–138. [Mechanistic basis for D1: precision-weighted priors, variational free energy, action as inference]

Friston, K.J., Wiese, W., and Hobson, J.A. (2021). Sentience and the existential imperative. *Entropy* 23(12): 1675. [Precision as the principal control parameter for active inference agents; supports A2]

Ramstead, M.J.D., Badcock, P.B., and Friston, K.J. (2018). Answering Schrödinger's question: a free-energy formulation. *Physics of Life Reviews* 24: 1–16. [Hierarchical precision; Markov blankets; collective active inference; precursor to FERN]

**Institutional Reality and Objectivation**
Austin, J.L. (1962). *How to Do Things with Words.* Oxford. [Speech act taxonomy; preparatory and sincerity conditions; illocutionary force — constraints on the claim that written instructions are "declarations"]

Searle, J.R. (1995). *The Construction of Social Reality.* Free Press. [Constitutive rules; background institutions; the conditions under which written text creates social facts]

Berger, P.L. and Luckmann, T. (1966). *The Social Construction of Reality.* Doubleday. [Objectivation as source-independence; sedimentation of norms into persistent objects; foundational mechanism for §3.2]

**Extended Mind and Distributed Cognition**
Clark, A. and Chalmers, D. (1998). The extended mind. *Analysis* 58(1): 7–19. [Written instruction as extended cognitive component; supports A4 and the source-independence claim]

Hutchins, E. (1995). *Cognition in the Wild.* MIT Press. [Distributed cognition across agent and artifact; frames Inscription Field as cognitive infrastructure]

**Communication and Relevance**
Sperber, D. and Wilson, D. (1986). *Relevance: Communication and Cognition.* Harvard. [Medium permanence as amplifier of relevance implicature; supports the medium precision ordering]

**Shared Intentionality**
Tomasello, M., Carpenter, M., Call, J., Behne, T., and Moll, H. (2005). Understanding and sharing intentions: the origins of cultural cognition. *Behavioral and Brain Sciences* 28(5): 675–691. [Scope condition: LODE applies only to populations with shared intentionality for written directives]

**Social Compliance**
Cialdini, R.B. (1984). *Influence: The Psychology of Persuasion.* HarperCollins. [Commitment and consistency; reciprocity — behavioral context for the ~20% baseline refusal]

Mauss, M. (1925/1990). *The Gift.* Trans. Halls. Routledge. [Three obligations of gift exchange; mechanism for souvenir refusal in the verbal condition — explains what agents are declining when they decline the post-it]

**Bifurcation and Non-Equilibrium Dynamics**
Prigogine, I. and Nicolis, G. (1977). *Self-Organization in Non-Equilibrium Systems.* Wiley. [Bifurcation theory underlying D3; dissipative structure conditions]

Prigogine, I. (1977). Time, Structure and Fluctuations. Nobel Lecture, 8 December 1977. [Bifurcation introduces history into physics; the constructive role of irreversibility]

**Fisher-Rao Geometry**
Rao, C.R. (1945). Information and accuracy attainable in the estimation of statistical parameters. *Bulletin of the Calcutta Mathematical Society* 37: 81–91. [Fisher information metric; basis for A₀ operationalization]

Chentsov, N.N. (1982). *Statistical Decision Rules and Optimal Inference.* AMS. [Uniqueness of the Fisher-Rao metric on the manifold of probability distributions; justifies using D_F to measure A₀]

**Cultural Transmission**
Kirby, S., Cornish, H., and Smith, K. (2008). Cumulative cultural evolution in the laboratory. *PNAS* 105(31): 10681–10686. [Structural inverse of ODES — compression rather than divergence pressure; Founder's Shadow predicts new results in this paradigm when high-A₀ founding stimuli are introduced]

---

Framework: **LODE · ODES · FELD · FERN · GRAIN**

Status tags: [D] = Formally derived from stated assumptions · [P] = Model proposition · [O] = Pilot observation (N unknown, no CI) · [C] = Testable conjecture · [A] = Explicit assumption · [H] = Working hypothesis

*Derived from two field sessions at Washington Square Park, New York City, 2026. N unknown in both. Session 2's anomalous observations are the founding data. All quantitative claims are pilot estimates pending controlled replication.*

![20260313_180907000_iOS](https://github.com/user-attachments/assets/e938ebe1-5655-4d46-8f55-d3c0c0b03b7f)
![20260313_180845000_iOS](https://github.com/user-attachments/assets/b8407459-5aa7-4a57-bada-eefecc38cbc4)
<img width="590" height="1278" alt="20260313_180949000_iOS" src="https://github.com/user-attachments/assets/d3411eed-ac05-4b93-b51a-23ef742dc717" />
![20260313_180914000_iOS](https://github.com/user-attachments/assets/d26aed27-8f49-4d83-94e1-5cc06d854051)

