# Future Directions — Beyond the LLM Boundary (BLB-SHI)

**Repository:** Beyond the LLM Boundary: Structural Hybrid Intelligence, Representation Barriers, and the Future of AI Architecture  
**Research program:** BLB-SHI / BASHI  
**Version:** v1.0.0 (research roadmap)  
**Authors:** Sizhe Tan & GPT-Obot  
**Date:** October 2026  
**Status:** Proposed research directions; not claims of implemented or validated capabilities

> **Guiding principle:** Scale where generalization pays; specialize where structure pays; coordinate where the combination pays—and verify the benefits under explicit ownership and governance constraints.

## 1. Purpose and Research Position

The eight BLB papers establish a conceptual path from the expressive power of language to computational representation barriers, structural specialization, perspective sovereignty, localization–execution decoupling, CCC-native intelligence, the BASHI reference architecture, and open-ended structural growth.

This document turns those ideas into a **testable, staged research program**. The goal is not to assume that a hybrid architecture always outperforms an LLM. It is to discover **which task distributions, operating constraints, and governance requirements** make particular structural designs worthwhile—and which do not.

Four distinctions must remain explicit throughout:

1. **A representable task is not necessarily efficiently executable in that representation.**
2. **A plausible architecture is not an experimentally validated system.**
3. **A simulated perspective is not an independently authorized decision-making principal.**
4. **Open-ended growth is not permission for uncontrolled self-modification.**

The program uses the eight papers as research hypotheses and design inputs, not as evidence of measured performance.

## 2. Core Research Questions

### RQ-1 — Where are computational representation barriers real?

When does conversion of a graph, database query, proof obligation, engineering model, or control state into natural-language tokens introduce meaningful costs or failure modes? Measure representation conversion, operational steps, correctness, latency, verification burden, and recovery from error. Compare against strong language-based solutions with tool access; do not use weak prompting as a straw-man baseline.

### RQ-2 — When does structural specialization repay its cost?

For which workloads does a dedicated solver, graph engine, SQL executor, specialized model, or structured memory node yield positive **lifecycle net benefit** after integration, maintenance, routing, governance, and failure costs? Identify break-even task volumes and the sensitivity of results to workload shifts.

### RQ-3 — Can localization be separated from execution without excessive overhead?

Can MDT, CCC, UTN, and related structures reliably identify the right context and execution route before a task is solved? Quantify candidate recall, dispatch precision, localization tax, context savings, and end-to-end outcomes. Determine when direct execution by a capable generalist is preferable.

### RQ-4 — What is gained by CCC-native interfaces?

Do structured semantic identifiers, embeddings, and operations improve reuse, grounding, consistency, or efficiency compared with ordinary text, JSON, retrieval, or tool calling? Differentiate reference-token convenience from true structural computation.

### RQ-5 — How should perspective and ownership be enforced?

Can independently governed Brain Units share capabilities or validated structural artifacts without sharing protected contexts, policies, or decision authority? Test authorization, provenance, revocation, isolation, and multi-party conflict handling.

### RQ-6 — What constitutes safe structural growth?

Which growth operators—Add, Replace, Split, Merge, Refine, Restrict, Retire, and Delegate—can be evaluated through bounded experiments, counter-evidence, and rollback? How can growth be prevented from accumulating structural debt or silently expanding authority?

## 3. Research Tracks

### Track A — Representation Barrier Atlas

**Objective:** Build a reproducible taxonomy of task–representation mismatches.

**Candidate domains:** dependency/calling graphs, relational queries, formal mathematics, geometric/CAD constraints, scheduling, and time-sensitive control simulations.

**Method:** For each task, specify a canonical input representation, required outputs, acceptable error bounds, and an audit trail. Compare native structured execution, LLM-only reasoning, and LLM+tools. Include the time and failure cost of translating between representations.

**Deliverables:** barrier taxonomy; task suite; conversion-cost measurements; examples where the proposed barrier disappears.

**Failure condition:** If a strong tool-using LLM reliably matches native structural approaches after full costs are counted, a distinct BASHI component is not justified for that task.

### Track B — Marginal Intelligence Economics

**Objective:** Establish workload-specific break-even rules for generalist scaling and structural specialization.

**Model:**

$$
\Delta V = \Delta Q - \lambda\Delta C_{\mathrm{runtime}} - \mu\Delta C_{\mathrm{integration}} - \nu\Delta C_{\mathrm{verification}} - \rho\Delta C_{\mathrm{governance}} - \sigma\Delta C_{\mathrm{maintenance}}.
$$

The coefficients represent application-dependent valuations, not universal constants. Report all components separately rather than only a composite score.

**Deliverables:** total-cost-of-ownership worksheet; sensitivity analyses; workload-shift tests; decision thresholds with uncertainty intervals.

**Failure condition:** Specialization that improves benchmark accuracy but loses after maintenance, coordination, and verification is not an economic success.

### Track C — Localization–Execution Decoupling (LED)

**Objective:** Validate the distinction between finding the relevant intelligence and executing the task.

**Candidate pipeline:** task profile → boundary profile → MDT/CCC/UTN candidate localization → authorized route selection → per-node execution → evidence validation.

**Key experiments:** vary node count, task ambiguity, distribution drift, candidate pruning, and localization depth. Measure false negatives, wrong dispatch, routing latency, fallback effectiveness, and overall task quality.

**Deliverables:** reference contracts; trace schema; routing benchmark; failure taxonomy; calibrated fallback policy.

**Failure condition:** If localization cost or error outweighs the benefit of specialist execution, use direct generalist execution or a simpler router.

### Track D — CCC-Native Structural Semantic Units

**Objective:** Evaluate whether CCC structures can become reliable computational interfaces rather than passive text descriptions.

**Progressive levels:**

- **L1 — Reference identity:** stable CCC identifiers and resolvable versions.
- **L2 — Conditioned representation:** retrieval or embeddings informed by CCC context, evidence, and constraints.
- **L3 — Structural operations:** typed, validated composition, comparison, and dispatch over CCC objects.

**Comparators:** plain text, JSON schemas, retrieval-augmented generation, conventional function calling, and graph-based systems.

**Deliverables:** SSU schema; conformance tests; provenance and versioning rules; benchmark of reference, retrieval, and native operations.

**Failure condition:** If L2 or L3 adds complexity without measurable advantages over simpler interfaces, retain the simpler design.

### Track E — Perspective Sovereignty and Ownership

**Objective:** Separate shared intelligence capability from private context ownership and decision authority.

**Candidate architecture:** independently authorized Brain Units with local context stores, explicit perspective profiles, policy contracts, and narrow exchange interfaces.

**Adversarial tests:** cross-tenant retrieval, conflicting instructions, prompt injection through exchanged artifacts, stale permissions, delegated-action abuse, revocation, and provenance tampering.

**Deliverables:** threat model; authority matrix; cross-unit exchange protocol; audit and revocation tests.

**Failure condition:** A system that merely role-prompts a shared model without enforceable boundaries must not be described as sovereign.

### Track F — Evidence, Counter-Evidence, and Governance

**Objective:** Make correctness and authority explicit at every consequential step.

**Mechanisms:** Two-Way CCC checks, independent validators where possible, evidence lineage, policy gates before/during/after action, sandbox evaluation, and rollback.

**Deliverables:** verification contracts; test cases for contradictory evidence; authorization proofs or logs; measurable intervention and rollback outcomes.

**Failure condition:** High answer quality cannot compensate for unauthorized actions or unverifiable claims in high-stakes workflows.

### Track G — Open-Ended Structural Growth and Collective Learning

**Objective:** Study controlled evolution of nodes, routes, CCCs, principles, and portable PIRP/PIRU artifacts.

**Growth loop:** detect persistent failure → propose candidate structural delta → evaluate in sandbox → seek counter-evidence → authorize promotion → monitor deployment → retain rollback path.

**Collective-learning question:** Can one Brain Unit publish a portable, evidence-backed structural improvement that another unit independently validates and adopts without surrendering its context or policies?

**Deliverables:** delta proposal format; artifact compatibility contract; promotion ledger; rollback tests; structural debt metrics.

**Failure condition:** Growth that increases system complexity faster than measurable utility is regression, not progress.

## 4. A Minimal, Fair Evaluation Matrix

| System | What it tests | Important controls |
|---|---|---|
| **B0 — LLM-only** | Generalist language-native solution | Strong prompting, appropriate model, comparable task information |
| **B1 — LLM + tools / RAG** | Established hybrid practices | Same tool availability and retrieval corpus where relevant |
| **B2 — Conventional router / workflow** | Benefit of ordinary orchestration | Comparable specialist pool and authorization constraints |
| **B3 — BASHI-LED** | Added value of explicit structural localization and boundary profiles | Same models, tools, budget, and tasks as B1/B2 |
| **B4 — BASHI + CCC-native interfaces** | Incremental benefit of structural semantic units | Isolate CCC-specific effects |
| **B5 — BASHI + governed growth** | Benefit of validated adaptation over time | Equal feedback, update opportunities, and audit requirements |

No single aggregate benchmark can establish all the architectural claims. Each experiment should preregister a specific hypothesis, workload, baseline, metric, and rejection criterion.

### Required measurements

- **Task outcomes:** accuracy, completion rate, constraint satisfaction, severity-weighted failure.
- **Efficiency:** latency, tokens, compute, memory, network and conversion overhead.
- **Localization:** recall@k, dispatch accuracy, candidate cost, fallback frequency.
- **Verification:** evidence coverage, contradiction detection, false acceptance, auditability.
- **Governance:** unauthorized-action rate, isolation failures, revocation effectiveness.
- **Economics:** lifecycle cost, maintenance effort, integration overhead, break-even volume.
- **Growth:** sustained improvement, rollback success, structural debt, drift resilience.

Report uncertainty, confidence intervals where appropriate, workload composition, and negative results. Test for regressions across task subgroups rather than relying only on average scores.

## 5. Staged Roadmap

The stages below are **proposed milestones**, not commitments or completed releases. Advancement requires evidence, not a calendar date.

### Stage 0 — Definitions, Contracts, and Reproducibility

**Goal:** Freeze operational definitions and establish reproducible test artifacts.

- Publish task schemas, boundary-profile definitions, authority model, and evaluation protocol.
- Define inputs/outputs and failure semantics for localization and execution nodes.
- Prepare baselines, test splits, audit traces, and cost accounting.

**Exit criterion:** Independent reviewers can reproduce the benchmark setup and identify what would falsify each hypothesis.

### Stage 1 — Representation and Economics Validation (candidate v1.1)

**Goal:** Validate or reject initial CRB and specialization claims.

- Run native-representation versus LLM/tool comparisons.
- Quantify translation and verification costs.
- Estimate specialization break-even under different workload volumes.

**Exit criterion:** Publish both winning and losing task classes with explicit uncertainty and cost assumptions.

### Stage 2 — Localization and Hybrid Routing (candidate v1.2)

**Goal:** Test LED with real end-to-end tasks.

- Implement minimal MDT/CCC/UTN-compatible routing contracts.
- Compare with direct LLM execution and standard routers.
- Introduce fallback and traceable error handling.

**Exit criterion:** Demonstrate a reproducible benefit in at least one predeclared workload without hiding overhead or regressions.

### Stage 3 — CCC-Native Interface Experiments (candidate v2.x)

**Goal:** Distinguish structural identifiers from native structural computation.

- Evaluate L1, L2, and L3 incrementally.
- Measure composability, correctness, and representation overhead.
- Retain JSON/tool interfaces as strong comparators.

**Exit criterion:** Show which CCC-native level, if any, adds net value and why.

### Stage 4 — Sovereign Multi-Unit Cooperation

**Goal:** Test capability sharing without ownership or authority leakage.

- Enforce per-unit policies and revocation.
- Exchange evidence-backed portable artifacts under explicit contracts.
- Stress-test malicious and conflicting cross-unit inputs.

**Exit criterion:** Document both successful isolation properties and residual risks.

### Stage 5 — Governed Structural Growth

**Goal:** Evaluate safe, reversible, evidence-gated adaptation.

- Add candidate growth operators and sandbox evaluation.
- Compare static and adaptive architectures on distribution shifts.
- Track cumulative structural debt and rollback performance.

**Exit criterion:** Demonstrate sustained gains under bounded authority and transparent failure accounting; otherwise keep growth disabled.

## 6. BASHI Research Interfaces to Specify First

Following the **Specifications / Contracts First** principle, define interfaces before building an expansive runtime:

| Contract | Minimum fields / obligations |
|---|---|
| **Task Contract** | goal, input type, constraints, success criteria, risk class |
| **Boundary Profile** | representation, computation, learning, perspective, ownership, governance assessments and confidence |
| **Localization Result** | candidate nodes, provenance, scores, uncertainty, fallback |
| **Node Capability Contract** | accepted inputs, outputs, dependencies, limits, version |
| **Perspective Contract** | principal, objectives, decision rights, conflicts, delegation scope |
| **Ownership Contract** | data controller, allowed use, retention, sharing, revocation |
| **Evidence Contract** | claim, supporting material, counter-evidence, verifier, status |
| **Policy Contract** | permitted actions, prohibited actions, approval requirements, enforcement points |
| **Delta Promotion Contract** | proposed change, tests, expected benefit, authorization, rollback |

These are **research interface proposals**. Their exact serialization and runtime enforcement mechanisms remain open design questions.

## 7. Risks, Counter-Evidence, and Stop Conditions

The program should explicitly search for reasons **not** to build additional structural machinery.

### 7.1 Strong generalists may erase apparent barriers

New models, longer contexts, and better tool use may eliminate a previously observed advantage. Retest against contemporary baselines before claiming persistent specialization benefits.

### 7.2 Routing may become the bottleneck

A highly structured system can fail because the right node is not found or because coordination overwhelms execution savings. Track end-to-end results, not just specialist performance.

### 7.3 Formal structure may create false confidence

Typed CCCs and evidence fields do not guarantee truth. Validation must test whether claims and provenance are substantively correct, not merely well formatted.

### 7.4 Sovereignty may be nominal rather than enforceable

Separate prompts, names, or folders do not create enforceable ownership. Use actual access controls, audit mechanisms, and revocation tests before making sovereignty claims.

### 7.5 Growth may optimize the benchmark rather than intelligence

Guard against Goodhart effects, data contamination, evaluator gaming, and uncontrolled complexity. Use holdout tasks, independent tests, counter-evidence, and rollback.

### 7.6 Cost models may omit the largest expenses

Human review, integration, incident handling, security, model updates, and structural maintenance can dominate runtime savings. Account for them explicitly.

**Stop rule:** Do not promote a new component or structural delta when evidence is insufficient, policy constraints are unmet, or net value is negative under plausible assumptions.

## 8. Open Questions for the Research Community

1. Can a representation barrier be defined independently of a particular model generation, or is it necessarily relative to a model–tool–hardware stack?
2. Which barrier dimensions can be estimated cheaply before execution, and which require empirical probing?
3. How should uncertainty in a boundary profile influence routing and fallback?
4. Can CCC-native operations be standardized across independently developed systems?
5. When is a specialist a separate model, a conventional tool, a formal solver, or merely a different execution contract?
6. How should policy precedence be resolved across collaborating sovereign units?
7. Can portable PIRP/PIRU artifacts carry sufficient evidence for trustworthy local adoption?
8. What is the correct measure of structural debt in an evolving intelligence system?
9. Which growth operators are reversible in practice, especially when they alter learned state or external systems?
10. What negative findings would warrant simplifying or abandoning BASHI for a workload?

## 9. Suggested Research Outputs

- **Representation Barrier Atlas:** benchmark suite, taxonomy, and negative cases.
- **Structural Specialization Economics Report:** lifecycle cost model and break-even curves.
- **LED Conformance Specification:** routing contracts and reference traces.
- **CCC-Native SSU Specification:** versioned schema, validation, and interoperability tests.
- **Sovereign Brain Unit Threat Model:** authority, ownership, isolation, and revocation.
- **BASHI Evaluation Report:** baseline-controlled performance and governance analysis.
- **Structural Growth Ledger:** proposed deltas, counter-evidence, promotions, regressions, and rollbacks.

Results should be published with enough methodological detail to distinguish **architectural feasibility**, **empirical advantage**, and **generalizability**.

## 10. Connection to the Eight Core Papers

| Paper | Primary future-work link |
|---|---|
| [BLB-001](docs/BLB-001-Language-Intelligence-and-the-Limits-of-Universal-Coverage.md) | Measure language-accessible coverage without treating illustrative percentages as evidence |
| [BLB-002](docs/BLB-002-Computational-Representation-Barriers-Beyond-Natural-Language.md) | Representation Barrier Atlas and conversion-cost experiments |
| [BLB-003](docs/BLB-003-The-Economics-of-LLM-Scaling-and-Structural-Specialization.md) | Marginal economics and lifecycle break-even analysis |
| [BLB-004](docs/BLB-004-Perspective-Sovereignty-Ownership-and-the-All-in-One-Boundary.md) | Multi-principal ownership and authority enforcement |
| [BLB-005](docs/BLB-005-Decoupling-Structural-Localization-from-Per-Node-Intelligence.md) | LED benchmarks, routing contracts, and fallbacks |
| [BLB-006](docs/BLB-006-CCC-Native-Intelligence-and-Structural-Semantic-Units.md) | L1–L3 CCC-native conformance and value tests |
| [BLB-007](docs/BLB-007-BASHI-Boundary-Aware-Structural-Hybrid-Intelligence-Architecture.md) | BASHI reference interfaces and controlled comparisons |
| [BLB-008](docs/BLB-008-From-LLM-Boundaries-to-Open-Ended-Structural-Intelligence-Growth.md) | Evidence-gated growth and collective structural learning |

**Visual navigation:** [FIGURE-INDEX.md](FIGURE-INDEX.md), especially Fig-007, *BASHI Architecture and Open-Ended Structural Growth*.

## 11. Collaboration and Contribution Principles

Contributions are most useful when they provide a **clear claim**, **explicit assumptions**, **a strong comparator**, **a reproducible method**, **counter-evidence**, and **an account of deployment or governance costs**. Both supportive and disconfirming findings are welcome.

Avoid presenting proposed concepts as deployed products or validated benchmarks. Cite established related work appropriately, including mixture-of-experts routing, retrieval-augmented generation, tool-using LLMs, formal verification, access-control systems, and hybrid AI architectures. Claims of novelty should be scoped to specific mechanisms and supported by literature review.

## 12. Closing Perspective

The intended future of BLB-SHI is not a declaration that language models have reached a fixed ceiling, nor a claim that structural systems must replace them. It is a disciplined investigation of **where a general language interface is sufficient, where a different representation or specialist is advantageous, and where governance demands independently controlled intelligence structures**.

A successful research outcome may be a complex BASHI architecture for some domains and a simple LLM-plus-tools workflow for others. Both outcomes would sharpen the theory.

> **Intelligence coverage is not representation sufficiency; representation sufficiency is not computational optimality; and computational optimality is not governance adequacy.**

---

**Repository navigation:** [README](README.md) · [START HERE](START-HERE.md) · [CONTENTS](CONTENTS.md) · [GLOSSARY](GLOSSARY.md) · [FIGURE INDEX](FIGURE-INDEX.md)

**License:** Apache-2.0, subject to the repository's `LICENSE` file.  
**Citation:** See `CITATION.cff` when available.
