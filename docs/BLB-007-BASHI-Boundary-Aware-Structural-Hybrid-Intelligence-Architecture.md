# BLB-007 — BASHI: Boundary-Aware Structural Hybrid Intelligence Architecture

**Repository:** Beyond the LLM Boundary: Structural Hybrid Intelligence, Representation Barriers, and the Future of AI Architecture (BLB-SHI)  
**Authors:** Sizhe Tan & GPT-Obot  
**Version:** 1.0.0  
**Date:** October 2026  
**Status:** Conceptual architecture and falsifiable research proposal; not an implemented or validated system

## Abstract

Large language models (LLMs) provide a powerful general-purpose interface to knowledge and computation, but their broad descriptive competence does not establish that a single representation, execution substrate, learning regime, or governance boundary is optimal for every task. The preceding BLB papers examine language coverage, computational representation barriers, scaling economics, perspective sovereignty, structural localization, and CCC-native semantic units. This paper integrates those strands into **Boundary-Aware Structural Hybrid Intelligence (BASHI)**: a proposed architecture that diagnoses task-specific boundaries, localizes relevant structures, selects authorized execution mechanisms, verifies outputs, and grows its structural repertoire under explicit controls. BASHI is a design hypothesis rather than a demonstrated improvement over well-engineered LLM-with-tools systems. Its contribution is a coherent specification of interfaces, invariants, routing decisions, failure modes, and tests capable of establishing when—and when not—structural hybridization is justified.

**Keywords:** structural intelligence; hybrid AI; computational representation barriers; structural localization; CCC; MDT; UTN; sovereign perspectives; policy control plane; verification; continual structural growth.

---

![Fig-007-BASHI-Architecture-and-Open-Ended-Structural-Growth.png](../figures/Fig-007-BASHI-Architecture-and-Open-Ended-Structural-Growth.png)

---

## 1. Problem Statement: From Universal Interface to Boundary-Aware Execution

A universal conversational interface is valuable. It does not follow that every operation should be performed internally through natural-language token prediction. Graph reachability, relational queries, symbolic proof, geometric constraints, real-time control, and privacy-sensitive decision-making can require different representations, runtime guarantees, and authority boundaries.

BASHI begins with four distinctions:

1. **Intelligence coverage is not representation sufficiency.** A model may describe a task without possessing the most appropriate executable representation.
2. **Representation sufficiency is not computational optimality.** An encoding may be possible yet inefficient or difficult to verify.
3. **Computational optimality is not governance adequacy.** A fast, correct operation may still be unauthorized.
4. **Shared intelligence capability is not shared context ownership.** Common infrastructure need not imply pooled goals, memories, or decision rights.

The central design question is therefore not “Can an LLM answer this?” but:

> **Which authorized combination of representation, localization, execution, verification, and control best satisfies the task's requirements?**

BASHI proposes a structured answer while retaining LLMs as first-class components.

## 2. Scope, Terminology, and Claims

### 2.1 Definition

**Boundary-Aware Structural Hybrid Intelligence (BASHI)** is a proposed intelligence-system architecture that:

- identifies relevant representational, computational, learning, perspective, ownership, and governance boundaries;
- locates task-relevant structural knowledge and executable capabilities;
- chooses among LLMs, specialized models, graph algorithms, SQL engines, solvers, tools, and human decision makers;
- checks evidence, counter-evidence, and operational contracts;
- enforces authority constraints throughout execution; and
- proposes, tests, and governs reusable structural changes.

**Boundary-aware** means that task-specific limitations inform routing and control, not that boundaries are immutable or always prohibitive. **Structural** refers to explicitly represented relationships, constraints, contexts, identities, interfaces, and versioned dependencies. **Hybrid** means heterogeneous computational mechanisms can cooperate without being collapsed into one internal representation.

### 2.2 Relationship to existing approaches

BASHI overlaps with retrieval-augmented generation (RAG), mixture-of-experts (MoE), tool-using agents, planners, workflow engines, multi-agent systems, and neuro-symbolic AI. None of these should be dismissed as merely “LLM-only.” The proposed differentiator is the **joint, explicit treatment** of representation boundaries, structural localization, ownership-aware authority, contract-based execution, counter-evidence, and governed structural growth. Whether this joint treatment provides measurable gains is an empirical question.

### 2.3 Non-claims

This paper does **not** claim that (i) LLMs cannot manipulate graphs or mathematical structures, (ii) every task needs specialization, (iii) CCC-native mechanisms are already validated, (iv) distributed sovereignty guarantees privacy, or (v) BASHI is faster, cheaper, safer, or more accurate without controlled measurement.

## 3. Task and Boundary Profiles

### 3.1 Task Structural Profile

Represent a task request as

\[
T = (g, x, c, q, d, e, a, p, o, v),
\]

where:

- \(g\): desired goal and acceptance criteria;
- \(x\): input artifacts and their native formats;
- \(c\): context and dependencies;
- \(q\): quality and correctness requirements;
- \(d\): deadline, latency, and resource limits;
- \(e\): evidence and audit requirements;
- \(a\): requested actions and side effects;
- \(p\): perspective, priorities, and decision preferences;
- \(o\): ownership, data access, and delegation constraints;
- \(v\): applicable versions and contracts.

These fields are a reference schema, not a requirement that every request carry all fields. Missing critical fields should lead to clarification, conservative defaults, or abstention rather than invented authority.

### 3.2 Six-axis Boundary Profile

For candidate execution mechanism \(m\), define

\[
B(T,m) = (B_R,B_C,B_L,B_P,B_O,B_G),
\]

with axes for **representation**, **computation**, **learning**, **perspective**, **ownership**, and **governance**. Each axis may be scored with calibrated, task-dependent estimates, confidence intervals, and supporting evidence. A score is a routing aid, not an objective truth.

Examples:

| Axis | Diagnostic question | Possible mitigation |
|---|---|---|
| Representation \(B_R\) | Does the mechanism preserve relevant native structure? | Typed graph, SQL, solver, geometry engine |
| Computation \(B_C\) | Does it meet accuracy, latency, and resource requirements? | Specialized execution, batching, caching |
| Learning \(B_L\) | Can it adapt with available data and safe updates? | Local structural delta, specialist training |
| Perspective \(B_P\) | Whose goals and tradeoffs determine the decision? | Explicit perspective contract, human approval |
| Ownership \(B_O\) | Who controls data, memory, and derived artifacts? | Sovereign partitions, scoped access |
| Governance \(B_G\) | Are actions authorized, observable, and reversible? | Policy checks, approval gates, audit |

The axes interact: a representation conversion can leak sensitive data; a low-latency optimization can weaken auditability. Boundary diagnosis must therefore include interactions and uncertainty.

### 3.3 Barrier severity versus routing feasibility

A severe barrier for one candidate does not mean the task is impossible. It means that candidate may be unsuitable under current constraints. BASHI distinguishes **candidate-relative barriers** from **task-level feasibility**.

## 4. Canonical BASHI Architecture

BASHI is organized as interacting planes rather than a single opaque chain.

### 4.1 Plane A — Intent and Structural Profiling

Parse user intent, relevant input structures, constraints, acceptance tests, and required authority. Produce a versioned Task Structural Profile. Preserve ambiguity instead of silently replacing it with an assumed goal.

### 4.2 Plane B — Boundary Diagnosis and Route Planning

Estimate representation and operational barriers for plausible routes. Generate alternatives: direct LLM, LLM with tools, structural retrieval plus specialist, multi-step workflow, human escalation, or refusal/abstention.

### 4.3 Plane C — Structural Localization

Find the relevant nodes, principles, constraints, and executable components using complementary mechanisms:

- **MDT:** metric/differential hierarchical localization;
- **CCC:** structured concepts, contexts, constraints, and related evidence;
- **UTN:** stable identities and context-bound structural references;
- **Calling Graph:** task-to-action dependencies and execution paths;
- **Two-Phase Search:** inexpensive candidate localization followed by selective expensive verification or computation.

Localization returns ranked, provenance-bearing candidate structures; it does not automatically authorize execution.

### 4.4 Plane D — Per-Node Hybrid Execution

Choose an executor according to the task and node contract. Candidate executors include general LLMs, specialized/HLM models, graph engines, SQL databases, symbolic and numerical solvers, deterministic programs, domain services, and human operators. The node contract defines accepted inputs, output types, preconditions, side effects, resource bounds, and error semantics.

### 4.5 Plane E — Evidence and Verification

Check output against explicit acceptance criteria, deterministic tests where possible, provenance, consistency constraints, and **Two-Way CCC / Counter-Evidence**. Verification effort should be proportional to consequence and uncertainty. Model-generated agreement alone is not independent verification.

### 4.6 Plane F — Structural Delta Growth

Capture failures, newly discovered distinctions, reusable solutions, and counterexamples as **candidate** structural deltas. Evaluate against held-out cases, regressions, security checks, and governance requirements before promotion. Growth is optional; task completion must not imply automatic learning or policy mutation.

### 4.7 Cross-cutting Policy Control Plane

The policy plane governs *before*, *during*, and *after* execution: data access, delegation, tool permissions, side effects, resource budgets, logging, retention, human approval, rollback, and promotion of learned structures. It is not a final-stage content filter.

### 4.8 Data and control flow

```text
User / Sovereign Perspective / Task Contract
                    |
                    v
        Task Structural Profiler
                    |
                    v
      Boundary Diagnosis & Planning
                    |
                    v
       Structural Localization
      MDT / CCC / UTN / Graph
                    |
                    v
        Authorized Route Selection
                    |
                    v
    Per-Node Hybrid Intelligence
 LLM | HLM | SQL | Graph | Solver | Tool | Human
                    |
                    v
   Verification & Counter-Evidence
                    |
          +---------+----------+
          |                    |
       Accepted           Reject / Retry /
          |                Escalate / Abstain
          v
   Output & Audit Record
          |
          v
 Candidate Structural Delta -> Evaluation -> Governed Promotion

 POLICY CONTROL PLANE: applies across all stages and transitions.
```

**Figure placement:** Insert `figures/Fig-007-BASHI-Architecture-and-Open-Ended-Structural-Growth.png` immediately after this section. Figure 007 should distinguish the operational loop from the governed learning/promotion loop.

## 5. Specifications and Contracts First

### 5.1 Contract categories

BASHI requires interoperable specifications rather than merely interoperable prose. A minimal contract set includes:

| Contract | Required content | Failure response |
|---|---|---|
| Task | Goal, acceptance tests, constraints, provenance | Clarify or abstain |
| Node | Identity, version, typed I/O, pre/postconditions | Reject incompatible dispatch |
| Perspective | Principal, goals, preferences, permitted delegation | Escalate conflicting authority |
| Data ownership | Owner, purpose, scope, retention, derived-data rules | Deny unauthorized transfer |
| Tool/action | Permissions, side effects, limits, idempotency | Block or request approval |
| Evidence | Sources, test method, confidence, freshness | Mark unverified or retry |
| Delta promotion | Change scope, tests, rollback, approval | Keep candidate quarantined |

### 5.2 Three invariants

**Invariant I — Authorization before consequential action.** No selected route may execute an externally consequential operation without satisfying its authority contract.

**Invariant II — Context isolation by default.** Cross-perspective data exchange requires an explicit, purpose-scoped permission; common model infrastructure does not grant cross-owner access.

**Invariant III — Learning does not self-authorize.** Candidate updates cannot modify the policy that approves them, nor be promoted merely because the generating model endorses them.

Additional invariants may be domain-specific, including determinism, transactionality, or human sign-off.

### 5.3 Contract failures are first-class outcomes

An expired capability, ambiguous principal, version mismatch, unavailable verifier, or unresolvable ownership rule should produce a typed failure, not silent fallback to a less constrained route.

## 6. Route Selection as Constrained Optimization

Let \(\mathcal{R}(T)\) be feasible candidate routes for task \(T\). Each route can comprise multiple localized nodes and executors. Define a *conceptual* route utility:

\[
U(r\mid T)=\widehat{Q}(r,T)-\lambda\widehat{C}(r,T)-\mu\widehat{R}(r,T)-\nu\widehat{V}(r,T),
\]

where \(\widehat{Q}\) is expected task quality, \(\widehat{C}\) total cost, \(\widehat{R}\) operational risk, and \(\widehat{V}\) verification burden. Coefficients reflect the authorized perspective's priorities and must not override hard requirements.

The selected route is

\[
r^*\in\arg\max_{r\in\mathcal{R}_{\mathrm{authorized}}(T)} U(r\mid T)
\]

subject to acceptance, privacy, latency, reliability, and other hard constraints. When estimates are uncertain, risk-aware selection may use confidence bounds or robust optimization. If \(\mathcal{R}_{\mathrm{authorized}}(T)=\varnothing\), the correct result is **no authorized route**, not an unconstrained best-effort action.

### 6.1 Full lifecycle cost

Cost should include localization, translation, model/tool inference, network orchestration, verification, human oversight, deployment, maintenance, and rollback. A specialist route can lose its advantage when integration overhead dominates; a general LLM can be optimal for low-volume or rapidly changing tasks.

### 6.2 Multi-objective governance

Some values are not safely reducible to one scalar: legal restrictions, consent, safety-critical thresholds, and ownership permissions are hard constraints. BASHI therefore separates **feasibility and authority filtering** from **utility optimization**.

## 7. BASHI Reference Skeleton Algorithm

The following is architecture-level pseudocode, not executable software or a benchmarked implementation.

```text
BASHI_EXECUTE(request, principal, environment):
    task <- PROFILE(request, principal, environment)
    if TASK_CONTRACT_INCOMPLETE(task):
        return CLARIFY_OR_ABSTAIN(task)

    constraints <- RESOLVE_POLICY_AND_OWNERSHIP(task, principal)
    if constraints.conflict:
        return DENY_OR_ESCALATE(constraints)

    candidates <- PROPOSE_ROUTES(task)
    boundary_profiles <- DIAGNOSE_BOUNDARIES(task, candidates)
    localized <- LOCALIZE_STRUCTURES(task, MDT, CCC, UTN, CallingGraph)

    routes <- COMPOSE_ROUTES(candidates, localized, boundary_profiles)
    authorized <- FILTER_BY_CONTRACTS_AND_POLICY(routes, constraints)
    if authorized is empty:
        return NO_AUTHORIZED_ROUTE

    while authorized has untried feasible routes:
        route <- SELECT_ROBUST_ROUTE(authorized, task)
        if not CHECK_PRECONDITIONS(route):
            record typed failure; continue

        result <- EXECUTE_WITH_RUNTIME_GATES(route)
        verdict <- VERIFY(result, task.acceptance, evidence, counter_evidence)

        if verdict.accepted:
            AUDIT(task, route, result, verdict)
            delta <- PROPOSE_STRUCTURAL_DELTA(task, route, verdict)
            QUARANTINE_FOR_OFFLINE_EVALUATION(delta)
            return AUTHORIZED_RESULT(result, verdict)

        RECORD_FAILURE_AND_COUNTER_EVIDENCE(route, verdict)
        authorized <- UPDATE_REMAINING_FEASIBLE_ROUTES(authorized, verdict)

    return ESCALATE_OR_ABSTAIN_WITH_AUDIT
```

**Important:** Policy must be rechecked at the moment of consequential action, not solely at planning time. Retrying must respect budgets, deadlines, and idempotency. Candidate deltas remain quarantined until separately approved.

## 8. Worked Architectural Cases

### 8.1 Calling Graph analysis

**Task:** Identify the downstream impact of changing an API function in a large codebase.

**Boundary:** Natural-language summaries can omit edges or confuse call direction. **Localization:** identify relevant repository versions and calling-graph neighborhoods. **Execution:** graph traversal and static-analysis tools compute dependencies; an LLM interprets intent and explains the result. **Verification:** compare against source-derived graph edges and tests. **Governance:** repository access and code-change authority remain distinct. **Delta:** propose a reusable impact-analysis pattern after evaluation.

A competent tool-using LLM may implement this entire workflow; BASHI's value must be tested against that strong baseline.

### 8.2 SQL and regulated business data

**Task:** Explain a sales anomaly without exposing customer-level private records.

**Boundary:** Free-form generation is not a reliable replacement for typed aggregation or access control. **Localization:** find approved tables, schema, metric definitions, and time windows. **Execution:** authorized SQL computes aggregates; an LLM narrates the findings. **Verification:** query validation, row-level access checks, reconciliation. **Governance:** purpose and data minimization apply to query planning and outputs. **Delta:** candidate reusable query templates require owner review.

### 8.3 Symbolic mathematics

**Task:** Derive and verify a constraint-sensitive result.

**Boundary:** Plausible symbolic prose is not a formal proof. **Localization:** identify definitions, assumptions, and applicable lemmas. **Execution:** theorem prover or computer algebra system, with LLM assistance for exploration. **Verification:** independent proof checking and explicit assumption reporting. **Governance:** version and provenance controls matter in high-stakes use.

### 8.4 Multi-perspective organizational decision

**Task:** Compare an infrastructure decision for finance, security, and engineering stakeholders.

**Boundary:** Simulating stakeholder voices does not grant authority to choose on their behalf. **Localization:** retrieve each stakeholder's permitted objectives and evidence. **Execution:** shared analytical tools calculate tradeoffs; separate perspective contracts govern recommendations. **Verification:** conflicts and unresolved priorities are exposed. **Governance:** final approval remains with designated decision makers.

## 9. Failure Modes and Countermeasures

| Failure mode | Why it matters | Mitigation or stop condition |
|---|---|---|
| Misdiagnosed barrier | Wrong specialist or unnecessary complexity | Compare against direct LLM baseline; recalibrate |
| Localization miss | Correct capability never considered | Recall audits, fallback search, abstention |
| Translation loss | Meaning changes across representations | Typed schemas, round-trip checks, provenance |
| Router overfitting | Apparent benchmark gains fail in deployment | Held-out domains and temporal evaluation |
| Tool-output injection | Untrusted data alters instructions | Trust boundaries, typed outputs, scoped permissions |
| Authority confusion | Agent acts for the wrong principal | Signed/scoped capabilities, explicit approval |
| Ownership leakage | Sensitive context crosses partitions | Data-flow policy, isolation tests, logging |
| Verification theater | Multiple LLMs agree without independent evidence | Deterministic tests and independent sources |
| Feedback contamination | Incorrect output becomes persistent knowledge | Quarantine, offline evaluation, rollback |
| Orchestration tax | Hybrid overhead exceeds benefit | End-to-end cost accounting; route simplification |
| Policy race | Permissions change during execution | Revalidate at action boundaries |
| Irreversible side effect | Retry duplicates a transaction | Idempotency, transaction semantics, human gates |

BASHI cannot eliminate these risks merely by diagramming separate planes. Implementation details and independent security evaluation are necessary.

## 10. Evaluation and Falsifiability

### 10.1 Baselines

A credible study must compare at least:

- **B0:** strong single-model LLM, with appropriate prompting and context;
- **B1:** strong LLM with retrieval, tools, and structured outputs;
- **B2:** conventional orchestrated specialist/workflow architecture;
- **B3:** BASHI with boundary profiling, localization, policy, and verification;
- **Ablations:** B3 without boundary diagnosis, without structural localization, without counter-evidence, or without ownership-aware contracts.

Matching tool access, data access, budget, and evaluator quality is essential. Otherwise gains may reflect better tools rather than the proposed architecture.

### 10.2 Task portfolio

Use graph dependency analysis, SQL analytics, mathematical verification, geometric/CAD constraints, document synthesis, real-time constrained workflows, and multi-perspective governance tasks. Include tasks where a general LLM is expected to win, to test whether BASHI avoids gratuitous complexity.

### 10.3 Metrics

- task success under independently specified acceptance tests;
- accuracy, completeness, and calibration;
- end-to-end latency and total cost of ownership;
- localization recall, precision, and route-selection regret;
- evidence coverage, false acceptance, and false rejection;
- policy violation rate, data leakage, and unauthorized side effects;
- robustness to representation changes and distribution shift;
- structural delta usefulness, regression rate, and rollback cost.

For high-impact failures, measure severity as well as frequency. Report uncertainty intervals and failure distributions, not only mean performance.

### 10.4 Hypotheses

**H1 — Representation-sensitive routing:** BASHI improves cost-adjusted verified success on tasks with measurable native-representation advantages relative to a tool-equivalent baseline.

**H2 — Localization efficiency:** MDT/CCC/UTN-guided localization reduces unnecessary expensive execution while maintaining target recall.

**H3 — Boundary profiling value:** Explicit boundary estimates improve route choice beyond task-category heuristics, after accounting for profiling overhead.

**H4 — Ownership fidelity:** Perspective and ownership contracts reduce cross-principal leakage and unauthorized actions without unacceptable task degradation.

**H5 — Verification independence:** Evidence and counter-evidence gates reduce false acceptance compared with self-consistency alone.

**H6 — Governed growth:** Quarantined, tested structural deltas yield positive retained improvement with bounded regression and maintenance cost.

Each hypothesis can fail independently; BASHI's architecture should be revised if evidence does not support a component.

### 10.5 Disconfirming evidence

Strong counter-evidence includes: (i) a tool-using LLM matches BASHI across quality, safety, and cost; (ii) localization overhead consistently exceeds savings; (iii) ownership partitioning creates greater error and friction without measurable privacy benefit; (iv) route estimates are too unstable to guide decisions; or (v) candidate structural growth degrades performance over time. Such outcomes should narrow, not rhetorically expand, BASHI's claims.

## 11. Engineering Progression: Specifications Before Runtime

A staged research program reduces risk of premature system-building.

**Stage 0 — Contract specification.** Define typed task, node, perspective, ownership, evidence, and delta schemas. Specify failure semantics and policy invariants.

**Stage 1 — Offline boundary studies.** Collect representative tasks and compare direct language execution with native structured tools, including conversion overhead.

**Stage 2 — Localization-only prototype.** Evaluate MDT/CCC/UTN retrieval and dispatch recall before granting action authority.

**Stage 3 — Read-only hybrid execution.** Add LLM, graph, SQL, and solver routes with independent verification and complete cost accounting.

**Stage 4 — Governed action runtime.** Introduce permission-scoped side effects, approvals, auditing, and rollback under adversarial tests.

**Stage 5 — Candidate structural growth.** Test offline deltas and controlled promotion against regressions and drift.

**Stage 6 — Multi-perspective interoperability.** Evaluate federated/sovereign contexts, explicit delegation, and minimal necessary information sharing.

This progression is a research roadmap, not a claim that the stages have been implemented.

## 12. Relation to CCC-Native Intelligence

BLB-006 proposes progressive CCC integration: reference-level identifiers, CCC-conditioned retrieval/embeddings, and potentially CCC-aware native operations. BASHI does **not** depend on the strongest speculative level. It can operate with ordinary typed metadata and external tools. CCC-native computation should be added only if it improves measured fidelity, efficiency, or composability over simpler interfaces.

Likewise, portable PIRP/PIRU components can be registered as capabilities, but portability requires contracts, compatibility testing, provenance, and authority—not just serialization.

## 13. Open Research Questions

1. How can boundary severity be calibrated across heterogeneous tasks without relying on circular model judgments?
2. Which task features predict that a specialized representation beats an LLM with equal tool access?
3. How much localization structure is necessary before index maintenance outweighs benefits?
4. Can structural identity and versioning remain stable under frequent domain changes?
5. How should policy conflicts between multiple sovereign principals be represented and resolved?
6. Which verification mechanisms provide genuinely independent evidence at reasonable cost?
7. How can hybrid routers remain robust under adversarial tool output and distribution shift?
8. When is the optimal architecture *less* structural—i.e., a direct model call or simple deterministic workflow?
9. What evidence would justify training CCC-native operations instead of using external CCC retrieval?
10. How can structural growth be measured over months without contamination from repeated benchmarks?

## 14. Conclusion

BASHI proposes a boundary-aware alternative to treating a universal language interface as a universal internal architecture. Its organizing principle is to **localize the relevant intelligence, execute in the most suitable authorized representation, verify with appropriate evidence, and govern both actions and learning**. The architecture is intentionally pluralistic: LLMs remain central for interpretation, synthesis, and coordination; structured engines remain central where native operations, guarantees, or authority boundaries matter.

The decisive question is empirical. If explicit boundary diagnosis and structural localization cannot beat strong tool-using baselines after accounting for integration, verification, and governance costs, their complexity is not justified. If they do improve verified task outcomes and preserve stakeholder authority, BASHI offers a concrete path from general language intelligence toward composable, accountable, open-ended structural intelligence.

---

## 15. Position in the BLB-SHI Series

- **BLB-001 — Language Intelligence and the Limits of Universal Coverage:** distinguishes language coverage from universal computational sufficiency.
- **BLB-002 — Computational Representation Barriers Beyond Natural Language:** motivates native representations and representation-translation costs.
- **BLB-003 — The Economics of LLM Scaling and Structural Specialization:** frames marginal specialization economics and hybrid break-even.
- **BLB-004 — Perspective Sovereignty, Ownership, and the All-in-One Boundary:** motivates principal-specific goals, ownership, and authority.
- **BLB-005 — Decoupling Structural Localization from Per-Node Intelligence:** supplies the localization/execution separation.
- **BLB-006 — CCC-Native Intelligence and Structural Semantic Units:** proposes progressively deeper CCC integration.
- **BLB-007 — BASHI: Boundary-Aware Structural Hybrid Intelligence Architecture:** integrates the preceding components into a testable reference architecture.
- **BLB-008 — From LLM Boundaries to Open-Ended Structural Intelligence Growth:** examines long-run structural evolution, ecosystem interfaces, and research priorities.

## References and Related Foundations

The following works provide relevant background, not empirical validation of BASHI:

1. Vaswani, A., et al. (2017). *Attention Is All You Need*. NeurIPS. https://arxiv.org/abs/1706.03762
2. Lewis, P., et al. (2020). *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*. NeurIPS. https://arxiv.org/abs/2005.11401
3. Fedus, W., Zoph, B., & Shazeer, N. (2022). *Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity*. JMLR. https://arxiv.org/abs/2101.03961
4. Schick, T., et al. (2023). *Toolformer: Language Models Can Teach Themselves to Use Tools*. NeurIPS. https://arxiv.org/abs/2302.04761
5. Yao, S., et al. (2023). *ReAct: Synergizing Reasoning and Acting in Language Models*. ICLR. https://arxiv.org/abs/2210.03629
6. Karpas, E., et al. (2022). *MRKL Systems: A Modular, Neuro-Symbolic Architecture that Combines Large Language Models, External Knowledge Sources and Discrete Reasoning*. https://arxiv.org/abs/2205.00445
7. NIST (2023). *Artificial Intelligence Risk Management Framework (AI RMF 1.0).* https://doi.org/10.6028/NIST.AI.100-1
8. Tan, S., & GPT-Obot. *Metric Differential Tree, UTN, and Context-Bound Token Intelligence*. https://github.com/sizhet/Metric-Differential-Tree-UTN-and-Context-Bound-Token-Intelligence
9. Tan, S., & GPT-Obot. *Portable Intelligence Runtime Pieces and Units*. https://github.com/sizhet/Portable-Intelligence-Runtime-Pieces-and-Units
10. Tan, S., & GPT-Obot. *Structural Recursive Self-Improvement*. https://github.com/sizhet/Structural-Recursive-Self-Improvement

---

**Research note:** BASHI is an architectural proposal. Formal definitions, examples, and test protocols are intended to enable scrutiny and implementation; they should not be interpreted as reported experimental results.
