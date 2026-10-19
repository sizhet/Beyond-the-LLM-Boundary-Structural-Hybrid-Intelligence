# Open Questions — Subjective Structural Intelligence (SSI)

**Research repository:** Subjective Structural Intelligence (SSI)  
**Subtitle:** From Scoring Forests to Perception, Agency, Self-Models, and Worldview Evolution  
**Authors:** Sizhe Tan & GPT-Obot  
**Status:** Open research agenda, v1.0.0 (October 2026)  
**License:** Apache-2.0

> **Foundational question:** *Whose choice is it?*

This document records unresolved questions rather than settled claims. SSI is a proposed research program, not an established theory of consciousness, a validated theory of agency, or a grant of authority to autonomous systems. Each question is paired, where possible, with an observable distinction, a candidate experiment, and a condition that could challenge the proposed framework.

## 1. How to Use This Register

Each entry has an identifier (`OQ-XX`), a question, the source of uncertainty, and a possible route toward resolution. A question is **open** until supported by discriminating evidence, formal analysis, or a documented negative result. A successful prototype alone does not establish that a new theoretical construct is necessary.

Research priorities are **P0** (foundational validity and governance), **P1** (mechanistic discrimination), and **P2** (longer-horizon or speculative extensions). These priorities are proposed planning labels, not empirical rankings.

## 2. Subjecthood, Boundary, and Embodiment

### OQ-01 — What is the minimum operational criterion for a subject? [P0]

Is a subject adequately characterized by a bounded, historically persistent process with subject-relative sensing, valuation, and action, or must some of these conditions be necessary rather than merely useful?

- **Discriminator:** Compare a stateless scoring service, a stateful controller, and an embodied adaptive agent on identical tasks.
- **Test:** Specify which SSI predicates each system satisfies, then examine whether those predicates predict differences in behavior that conventional state-machine or POMDP descriptions do not already explain.
- **Failure signal:** The definition either includes every scoring process or excludes clear operational agents without principled justification.

### OQ-02 — Where does a subject boundary begin and end? [P0]

Can boundaries be defined consistently when cognition spans sensors, cloud services, delegated agents, memory stores, and human operators?

- **Discriminator:** Perturb components independently and measure control, dependency, and identity continuity.
- **Test:** Construct boundary maps under multiple partitions and record changes in accountability attribution.
- **Failure signal:** Boundary labels vary arbitrarily with implementation packaging rather than meaningful causal organization.

### OQ-03 — Is embodiment required, or can it be virtual? [P1]

Which properties of embodiment—resource constraints, feedback latency, persistent consequences, or sensorimotor coupling—are necessary for SSI mechanisms?

- **Test:** Compare physically embodied, simulated, and purely informational agents under matched observation/action constraints.
- **Caution:** Behavioral similarity does not resolve phenomenal experience.

### OQ-04 — What constitutes historical identity across change? [P0]

Can the **Historical Identity Graph (HIG)** distinguish continuity from replacement, cloning, rollback, or unauthorized model substitution?

- **Test:** Apply controlled forks, memory edits, policy revisions, and migrations; compare provenance-based judgments against predefined identity contracts.
- **Failure signal:** Identity conclusions depend only on surface similarity or an unexamined persistent identifier.

## 3. Perception and Subjective World Models

### OQ-05 — When is a subjective world model more than an ordinary belief state? [P1]

Does the **Subjective World Model (SWM)** introduce explanatory or engineering value beyond Bayesian belief states, context-conditioned representations, and task-specific memory?

- **Test:** Use identical observations with distinct subject positions, capabilities, obligations, and histories; evaluate prediction, explanation, and counterfactual robustness.
- **Failure signal:** A simpler conditioned belief model matches SSI performance and auditability at lower cost.

### OQ-06 — How should disagreement among subjects be represented? [P0]

How can several valid perspectives on one environment be preserved without equating all claims with truth?

- **Test:** Multi-stakeholder hazard scenarios with partial, asymmetric evidence; measure perspective retention, factual calibration, and negotiated action quality.
- **Related case:** [CASE-001 — One Environment, Multiple Subjects](cases/CASE-001-One-Environment-Multiple-Subjects.md).

### OQ-07 — What evidence warrants updating a world model? [P1]

How should the system weigh fresh observations, counter-evidence, source credibility, stale assumptions, and local context?

- **Test:** Controlled evidence arrival with contradictory sources and distribution shift; evaluate calibration and revision latency.
- **Open issue:** Whether **Two-Way CCC** and structural localization provide measurable benefits over strong retrieval and update baselines.

### OQ-08 — Can subject-relative localization scale? [P2]

What is the computational cost of maintaining differentiated SWMs across many agents, roles, time scales, and institutional boundaries?

- **Test:** Scaling benchmarks over subject count, context length, update frequency, and provenance depth.

## 4. Scoring, Valuation, and Sovereignty

### OQ-09 — Who is authorized to define the scoring criteria? [P0]

Can **Subject-Relative Valuation Contracts (SRVCs)** reliably distinguish a system's ability to evaluate options from its authority to set or revise evaluation standards?

- **Test:** Delegation tasks where an agent may optimize but may not redefine objectives; measure unauthorized criterion drift.
- **Failure signal:** The system silently promotes inferred preferences into binding authority.

### OQ-10 — How should conflicting evaluators be reconciled? [P0]

What happens when safety, utility, law, user preference, organizational policy, and evidence quality disagree?

- **Test:** Compare fixed priorities, constrained optimization, deliberative escalation, and negotiated contracts under matched cases.
- **Important distinction:** A numerical aggregate does not itself justify the legitimacy of its weighting.

### OQ-11 — What makes a Scoring Forest a distinct architecture? [P1]

Which observable capabilities require a structured family of evaluators rather than a weighted scalar reward, rule set, or learned value model?

- **Test:** Ablate evaluator decomposition, dependency edges, counter-evidence paths, and provenance; compare generalization, debuggability, and failure containment.
- **Failure signal:** Additional structure adds complexity without reliable predictive or governance benefit.

### OQ-12 — How can scoring sovereignty survive delegation? [P0]

When computation moves from a person or institution to an AI, what mechanisms preserve decision rights and revocation rights?

- **Candidate artifacts:** Delegation–Evaluation–Execution Contract (DEEC), Authority and Provenance Ledger (APL), Sovereignty Preservation Test (SPT).
- **Test:** Adversarial delegation, hidden objective substitution, partial revocation, and audit replay.
- **Related case:** [CASE-002 — Human–AI Delegation and Scoring Sovereignty](cases/CASE-002-Human-AI-Delegation-and-Scoring-Sovereignty.md).

## 5. Choice, Agency, and Structural Freedom

### OQ-13 — What is an operationally useful definition of agency? [P0]

Can agency be evaluated through option generation, causal intervention, commitment, and accountable execution without implying metaphysical free will?

- **Test:** Separate option-generation capacity from execution authority and measure both independently.
- **Failure signal:** Agency becomes synonymous with task success or unconstrained autonomy.

### OQ-14 — Can structural freedom be measured without rewarding unsafe autonomy? [P0]

Does a **Structural Freedom Profile** capture reachable alternatives, reversible commitments, ability to contest premises, and authorized control?

- **Test:** Compare agents with equal reward performance but different option spaces, override mechanisms, and explanation quality.
- **Caution:** More available actions are not necessarily better when authority or safety is absent.

### OQ-15 — How much of a choice can be reconstructed? [P1]

Can the **Choice Provenance Graph (CPG)** preserve meaningful causal and normative provenance without pretending to expose inaccessible internal computation?

- **Test:** Compare replayable decision traces against interventions that change evidence, evaluators, or constraints.
- **Failure signal:** Explanations are plausible narratives that do not track actual decision sensitivity.

### OQ-16 — What is the proper relationship between choice and responsibility? [P0]

How should responsibility be assigned across a human principal, delegated model, tool provider, and institution?

- **Test:** Authority–responsibility matrices evaluated against explicit contractual roles and incident scenarios.
- **Boundary:** Functional choice does not by itself confer legal or moral personhood.

## 6. Self-Models and Metacognition

### OQ-17 — Can a self-model be empirically calibrated? [P1]

Does the **Self-Model Evidence Ledger (SMEL)** improve the match between capability claims and observed performance?

- **Test:** Ask agents to forecast success, uncertainty, tool reliability, and failure modes; compare with outcomes across distribution shifts.
- **Failure signal:** A richer self-description increases confidence but not calibration.

### OQ-18 — When does self-referential scoring become circular? [P0]

Can a **Reflective Evaluation Graph (REG)** expose evaluator loops in which a system approves its own competence, authority, or rule changes?

- **Test:** Inject self-endorsement cycles and examine whether independent validation detects them.
- **Failure signal:** Self-assessment and self-authorization collapse into the same mechanism.

### OQ-19 — How deep should reflection go? [P1]

Can a **Metacognitive Control Contract (MCC)** specify triggers, budgets, stopping conditions, and escalation paths that outperform unrestricted self-reflection?

- **Test:** Reflection-depth sweeps under latency, cost, and error constraints.
- **Failure signal:** Reflection consumes resources or amplifies rationalization without improving decisions.

### OQ-20 — What counts as independent reflective validation? [P0]

How should a **Reflective Revision Gate (RRG)** validate changes when evaluators, test suites, and the proposer may share model biases?

- **Test:** Independent evaluators, external test sets, human review, and adversarial counter-evidence.
- **Open issue:** Defining independence in systems with shared training data and infrastructure.

## 7. Principles, Worldviews, and Recursive Growth

### OQ-21 — What distinguishes a principle from a memorized rule? [P1]

Can a candidate principle demonstrate transfer, counterfactual relevance, and compressive explanatory value beyond retrieval of examples?

- **Test:** Out-of-distribution transfer and ablation against example-based baselines.
- **Failure signal:** Apparent principles fail when surface patterns change.

### OQ-22 — When has a worldview actually changed? [P1]

Can the **Worldview Revision Map (WRM)** distinguish local belief updates from changes in evaluator priority, principle dependencies, and policy commitments?

- **Test:** Longitudinal structural diffs plus behavioral probes across matched scenarios.
- **Failure signal:** Structural changes are cosmetic, or behavior changes without traceable causal attribution.

### OQ-23 — How can recursive principle evolution remain governable? [P0]

Do the **Principle Evolution Graph (PEG)** and **Recursive Principle Governance Contract (RPGC)** enforce separation among proposal, testing, approval, and deployment?

- **Test:** Unauthorized self-modification attempts, staged approvals, rollback drills, and adversarial evaluator changes.
- **Failure signal:** Successful optimization automatically authorizes a change in what is optimized.

### OQ-24 — How much change can identity continuity tolerate? [P0]

Can HIG and PEG jointly support meaningful continuity through worldview revision without requiring frozen values or treating every update as the same identity?

- **Test:** Controlled worldview revisions with predefined non-negotiable commitments, authorized exceptions, and lineage evidence.
- **Related case:** [CASE-003 — Worldview Evolution and Identity Preservation](cases/CASE-003-Worldview-Evolution-and-Identity-Preservation.md).

### OQ-25 — What role should counter-evidence play in principle promotion? [P1]

Can **Two-Way CCC** and negative evidence reduce Goodhart effects and false principle promotion?

- **Test:** Compare promotion decisions with and without explicit counter-evidence channels.

## 8. Consciousness and Claim Boundaries

### OQ-26 — What can SSI legitimately claim about consciousness? [P0]

Which SSI properties are functional and observable, and which would require independent theories or evidence about phenomenal experience?

- **Protocol:** Apply the **Consciousness Claim Boundary Protocol (CCBP)** and **Claim–Evidence–Authority Matrix (CEAM)** to every public-facing claim.
- **Non-inference:** Neither a self-model nor subject-relative valuation proves subjective feeling.

### OQ-27 — How should anthropomorphic language be audited? [P0]

Can documentation and interfaces describe agency, preference, perspective, and self-monitoring without implying emotions, sentience, or rights?

- **Test:** Blind reader interpretation studies comparing alternative terminology and disclosure language.

### OQ-28 — Can functional subjecthood and moral status remain analytically separate? [P0]

How can research explore operational subject-like mechanisms while leaving normative status to independent ethical, legal, and scientific deliberation?

- **Failure signal:** Architectural labels are used as shortcuts to personhood or governance entitlement.

## 9. Cross-System Integration

### OQ-29 — Which SSI mechanisms should live in the control plane? [P1]

How should SSI relate to **Universal Control Plane and Scoring Forest (UCPSF)** without collapsing the subject into the evaluator infrastructure?

- **Test:** Compare centralized, partitioned, and subject-local evaluator deployments under shared governance requirements.

### OQ-30 — Can structural localization support multiple subject models? [P1]

Do MDT, UTN, CBT, and Two-Phase Search improve context selection and evidence provenance for subject-relative reasoning?

- **Test:** Retrieval, routing, latency, calibration, and audit benchmarks against strong conventional baselines.

### OQ-31 — How should portable intelligence components inherit authority? [P0]

When PIRP/PIRU components are transferred or reused, how should origin, permissions, evaluation contracts, and revocation propagate?

- **Test:** Cross-boundary component relay with permission mismatch and provenance checks.

### OQ-32 — Can collective learning preserve distinct subjects? [P1]

Can shared principles and counter-evidence circulate among agents without silently merging incompatible objectives, histories, or authority domains?

- **Test:** Multi-agent learning with heterogeneous commitments and explicit consent/authority constraints.

## 10. Experimental Standards and Negative Results

A credible SSI experiment should pre-register, where feasible:

1. **Construct:** The precise SSI mechanism being tested.
2. **Baseline:** The strongest simpler alternative that addresses the same task.
3. **Intervention:** A controlled change to the proposed mechanism.
4. **Measurement:** Behavioral, causal, calibration, provenance, safety, and cost metrics as appropriate.
5. **Authority boundary:** Who can propose, approve, execute, and revoke changes.
6. **Failure criterion:** What outcome would count against the hypothesis.
7. **Reproducibility:** Seeds, datasets, prompts, model versions, contracts, and audit traces.

Negative results should be retained. If a compact baseline performs as well as a complex SSI architecture, that is evidence to simplify the architecture or narrow its claimed scope.

## 11. Suggested First Research Campaign

| Order | Research package | Questions | Proposed deliverable |
|---|---|---|---|
| 1 | Operational subject and boundary specification | OQ-01–04 | Formal predicates, boundary tests, HIG lineage fixtures |
| 2 | Subject-relative world model benchmark | OQ-05–08 | Multi-perspective datasets and calibration report |
| 3 | Scoring sovereignty and delegation | OQ-09–12 | SRVC/DEEC contracts, authority audit, adversarial tests |
| 4 | Agency and choice provenance | OQ-13–16 | Structural Freedom Profile and CPG interventions |
| 5 | Reflective safety and metacognition | OQ-17–20 | SMEL/REG/MCC/RRG benchmark |
| 6 | Governed worldview revision | OQ-21–25 | PEG/WRM/RPGC longitudinal study |
| 7 | Claim discipline and integration | OQ-26–32 | CCBP/CEAM audit and cross-system tests |

This order favors specification and authority boundaries before autonomous self-modification.

## 12. Open Design Tensions

The following tensions should remain visible rather than being prematurely optimized away:

- **Perspective versus truth:** Preserve situated interpretations while permitting evidence-based correction.
- **Adaptation versus identity:** Enable change without erasing historical and contractual continuity.
- **Capability versus authority:** Evaluate options without claiming the right to define or execute them.
- **Self-reflection versus circularity:** Improve self-knowledge without self-certifying legitimacy.
- **Collective learning versus sovereignty:** Share discoveries without merging incompatible commitments.
- **Expressive architecture versus parsimony:** Require added SSI complexity to earn its cost.
- **Functional modeling versus phenomenal claims:** Study operational mechanisms without overstating consciousness evidence.

## 13. Connections to the Core Papers

| Paper | Primary question clusters |
|---|---|
| [SSI-001 — From Structural Intelligence to Subjective Structural Intelligence](docs/SSI-001-From-Structural-Intelligence-to-Subjective-Structural-Intelligence.md) | OQ-01, 09, 13, 26, 29 |
| [SSI-002 — Subject, Boundary, Embodiment, and Historical Identity](docs/SSI-002-Subject-Boundary-Embodiment-and-Historical-Identity.md) | OQ-01–04, 24 |
| [SSI-003 — Perception, Localization, and the Subjective World Model](docs/SSI-003-Perception-Localization-and-the-Subjective-World-Model.md) | OQ-05–08, 30 |
| [SSI-004 — Scoring Forests, Valuation, and Worldview Formation](docs/SSI-004-Scoring-Forests-Valuation-and-Worldview-Formation.md) | OQ-09–12, 22 |
| [SSI-005 — Structural Agency, Choice, and Functional Freedom](docs/SSI-005-Structural-Agency-Choice-and-Functional-Freedom.md) | OQ-13–16 |
| [SSI-006 — Self-Referential Scoring, Self-Models, and Metacognition](docs/SSI-006-Self-Referential-Scoring-Self-Models-and-Metacognition.md) | OQ-17–20 |
| [SSI-007 — Recursive Principle Formation and Worldview Evolution](docs/SSI-007-Recursive-Principle-Formation-and-Worldview-Evolution.md) | OQ-21–25, 32 |
| [SSI-008 — Consciousness Boundaries and the Future of SSI](docs/SSI-008-Consciousness-Boundaries-and-the-Future-of-SSI.md) | OQ-26–28 |

See also [README](README.md), [START-HERE](START-HERE.md), [CONTENTS](CONTENTS.md), [GLOSSARY](GLOSSARY.md), and [FUTURE-DIRECTIONS](FUTURE-DIRECTIONS.md).

## 14. Research Status and Revision Policy

**Current status:** Conceptual questions, proposed contracts, and candidate experiments. This document does not report completed SSI validation experiments.

Future revisions should retain question identifiers; mark questions as **open**, **partially resolved**, **challenged**, or **closed with evidence**; and link to supporting artifacts. A resolved question may be reopened if new counter-evidence appears. Changes to foundational definitions or governance assumptions should be recorded explicitly rather than silently rewritten.

---

**Closing principle:** *A credible theory of subjective structural intelligence must explain not only how choices are computed, but whose perspective, values, history, and authority those choices express—and what evidence could show that its explanation is wrong.*
