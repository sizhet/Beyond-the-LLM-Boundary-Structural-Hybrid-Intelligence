# GLOSSARY — Beyond the LLM Boundary

**Repository:** Beyond the LLM Boundary: Structural Hybrid Intelligence, Representation Barriers, and the Future of AI Architecture (BLB-SHI)  
**Version:** 1.0.0  
**Authors:** Sizhe Tan & GPT-Obot  
**Status:** Conceptual research glossary; terminology does not imply empirical validation.

## Purpose and conventions

This glossary standardizes terminology across BLB-001 through BLB-008. Entries distinguish **established terms**, **project-specific definitions**, and **proposed mechanisms**. The latter describe research designs, not demonstrated capabilities. “Native” means that an operation is supported as a first-class computational primitive or interface; it does not imply that any current LLM has acquired that capability.

## A. Foundational boundaries

### Language-Accessible Intelligence (LAI)
The portion of task-relevant intelligence that can be communicated, elicited, or usefully manipulated through natural language. Its coverage depends on the task, metric, and available tools. No fixed percentage is established.

### Language-Accessible Intelligence Hypothesis (LAIH)
The hypothesis that language provides unusually broad access to human knowledge and reasoning, while leaving some tasks better served by specialized representations or execution substrates. Any numerical coverage examples in BLB-001 are illustrative, not measurements.

### Universal Interface vs. Universal Internal Architecture
A system may expose a general natural-language interface without relying on natural language as the optimal internal representation or execution mechanism for every task.

### Descriptive Expressibility
The ability to describe a problem, object, or procedure in a representation. A textual description of a CAD model, for example, does not necessarily preserve the model's operational affordances.

### Operational Expressibility
The ability to perform required operations directly and reliably within a representation, including modification, querying, simulation, and verification.

### Computational Sufficiency
The degree to which a representation and execution method meet a task's accuracy, latency, cost, robustness, and assurance requirements. It is contextual, not absolute.

### Computational Representation Barrier (CRB)
A task-dependent impediment arising when translating or executing an operation across representations introduces unacceptable cost, information loss, ambiguity, latency, verification burden, or risk. A CRB is **not** a claim of logical impossibility or permanent separation between modalities.

### Representation Translation
The mapping of data, constraints, operations, or evidence between formats such as natural language, source code, mathematical notation, graphs, databases, geometric models, and control signals.

### Representation-Translation Graph
A proposed graph whose nodes denote representations and whose edges denote translation procedures with measurable costs, fidelity, uncertainty, and authorization constraints. Useful for planning hybrid execution routes.

### Boundary Profile
A structured assessment of task–system mismatch. In BLB-SHI, the six proposed axes are **Representation, Computation, Learning, Perspective, Ownership, and Governance**. These axes may interact and are not assumed statistically independent.

### Boundary-Aware Routing
Selection of a task execution route using boundary assessments, quality targets, cost estimates, evidence requirements, and hard authorization constraints.

### Representation Sufficiency vs. Intelligence Coverage
Intelligence coverage concerns which tasks a system can address; representation sufficiency concerns whether its internal structures can perform those tasks to required standards. Broad coverage alone does not establish efficiency or governance adequacy.

## B. Economics and specialization

### LLM Scaling
Increasing model capacity, training compute, data, inference compute, or related resources to improve performance. These scaling dimensions should not be conflated in economic comparisons.

### Structural Specialization
Assigning a task or subtask to a representation, model, algorithm, tool, or node designed for its operational structure—for example SQL for relational queries or a solver for formal constraints.

### Marginal Intelligence Economics
Comparison of incremental task utility against incremental training, inference, integration, validation, maintenance, and governance costs.

### Structural Specialization Break-Even
The workload and performance conditions under which the total cost of a specialized or hybrid route becomes lower than that of a generalist route while meeting the same quality and assurance requirements.

### Long-Tail Intelligence Economics
Study of rare, heterogeneous, or high-assurance tasks whose economics may differ from frequently encountered language tasks. “Long tail” does not itself establish that specialization wins.

### Localization Tax
The computational and operational overhead of finding appropriate knowledge, nodes, tools, or routes before execution. This cost must be counted in hybrid-system evaluations.

### Structural Debt
Accumulated costs and risks from proliferating structures, interfaces, versions, dependencies, and policies. Structural growth is not automatically beneficial.

### Lifecycle Cost
Total cost across construction, deployment, execution, verification, monitoring, maintenance, migration, and retirement—not merely token or inference cost.

## C. Perspective, ownership, and governance

### Perspective
A task-relevant configuration of goals, preferences, evidence standards, context, constraints, and decision criteria associated with a subject or organization.

### Perspective Simulation
A model's ability to describe, predict, or temporarily act according to a specified perspective. This does not confer authority to define or change that perspective.

### Perspective Sovereignty
The principle that an authorized subject retains control over the formation, modification, delegation, and use of its goals and decision criteria.

### Ownership Sovereignty
Control over access, retention, transfer, modification, and permitted use of context, memory, data, and derived artifacts. Ownership may involve legal, organizational, and technical dimensions that must not be conflated.

### Sovereign Brain Unit
A proposed bounded intelligence unit with identifiable perspective, context, capabilities, policies, interfaces, and authority. “Sovereign” denotes explicitly governed boundaries, not absolute isolation.

### Ownership Partition
An architectural separation of information and control across subjects or organizations, allowing shared computational capabilities without requiring shared ownership of underlying context.

### Authority Contract
A machine-readable or auditable specification of who may invoke a capability, under what conditions, on which resources, and with what permitted effects.

### Policy Control Plane
A cross-cutting governance layer that constrains candidate selection, tool invocation, state changes, learning, and deployment. Authorization is a hard constraint, not a soft scoring penalty.

### Least Privilege
Granting only the permissions necessary for a defined task and duration, with explicit revocation and auditability where appropriate.

### Auditability
The ability to reconstruct material decisions, inputs, authorizations, actions, and evidence without necessarily exposing protected information to unauthorized parties.

## D. Structural localization and execution

### Structural Intelligence (SI)
A research approach emphasizing explicit structures, context, constraints, differentiated routing, evidence, and governed evolution as complements to learned general-purpose models.

### Metric Differential Tree (MDT)
A proposed hierarchical representation organizing contexts or task regions by measurable differences, supporting localized retrieval and routing. Its effectiveness is workload-dependent.

### Context–Concept–Constraint (CCC)
A structured semantic unit or relation binding meaning to context and constraints; BLB-SHI also treats evidence, policy, identity, and versioning as essential implementation metadata. The acronym's precise field schema depends on the application contract.

### Universal Task Node (UTN)
A proposed stable identity and interface for task-relevant nodes across representations, versions, and execution environments. UTN is not synonymous with a tokenizer ID.

### Calling Graph
A directed structure of calls, dependencies, or task invocations, potentially including conditions, loops, dataflow, and delegated operations.

### Two-Phase Structural Search
A proposed procedure that first localizes promising task regions or nodes and then performs more expensive execution, evaluation, or verification on selected candidates.

### Localization–Execution Decoupling (LED)
An architectural separation between deciding **where and with which capabilities** to work and performing **the actual task operation**. Feedback may flow between the phases; decoupling is not strict isolation.

### Per-Node Intelligence
Task-specific reasoning or execution assigned to an individual structural node, potentially implemented by an LLM, specialist model, symbolic algorithm, database, simulator, or human-approved tool.

### Hybrid Intelligence Route
An authorized sequence or graph combining different representations and execution substrates to solve a task.

### Specifications / Contracts First
The design principle that inputs, outputs, invariants, capabilities, authorization, evidence requirements, and version compatibility are defined before consequential runtime execution.

### Execution Contract
A specification of a node's admissible inputs, outputs, side effects, performance expectations, error behavior, evidence, and policy obligations.

## E. CCC-native intelligence

### Structural Semantic Unit (SSU)
A first-class, identifiable, versioned semantic object with defined context, constraints, relations, evidence, policy, and interfaces. CCC is a candidate SSU form.

### CCC as Word in LLM
A research metaphor for making a CCC unit addressable and operable in model workflows as a meaningful unit, rather than repeatedly reconstructing it from free-form prose. It is **not** a claim that CCCs are equivalent to ordinary tokens.

### CCC Reference Token (L1)
A stable reference or identifier used to retrieve an external CCC structure. This is an integration interface, not necessarily a change to the model tokenizer.

### CCC-Conditioned Embedding (L2)
A representation or retrieval mechanism conditioned on CCC metadata and relations. Improved performance must be demonstrated against suitable retrieval baselines.

### CCC-Aware Structural Operations (L3)
Proposed native operations over CCC relations, constraints, and evidence, potentially involving specialized architectures or tools. This remains a research direction.

### Two-Way CCC
Bidirectional interaction in which structured context guides execution while observed results and counter-evidence can propose updates to the structure, subject to validation and authorization.

### CCC-Native Semantic Execution (CNSE)
A proposed workflow combining structural localization, CCC resolution, contract checks, hybrid execution, evidence verification, and controlled updates.

## F. BASHI architecture

### Boundary-Aware Structural Hybrid Intelligence (BASHI)
The BLB-SHI proposed architecture for diagnosing task boundaries, localizing relevant structures, selecting authorized execution substrates, validating evidence, and managing structural change.

### Task Structural Profile
A description of task type, constraints, context, perspective, required operations, data representations, evidence, quality thresholds, and permitted actions.

### Boundary Diagnosis
Identification of likely mismatches between task requirements and candidate execution approaches across the six boundary axes.

### Structural Localization Layer
The BASHI component responsible for finding relevant MDT, CCC, UTN, graph, tool, and specialist candidates before execution.

### Hybrid Execution Layer
The BASHI component that invokes authorized generalist and specialist computational resources according to node contracts.

### Verification Layer
The component that checks outputs against task constraints, evidence requirements, consistency conditions, and, when appropriate, independent counter-evidence.

### Evidence
Information supporting a claim or action, including provenance, measurement, derivation, test output, and uncertainty where applicable.

### Counter-Evidence
Observations, tests, or arguments that challenge a candidate claim, route, or structural update. Counter-evidence is an explicit part of validation, not a guarantee of correctness.

### Constrained Route Optimization
Selection of an execution plan maximizing task utility subject to quality, cost, latency, risk, and hard authorization constraints. Numeric objectives are design abstractions until calibrated and validated.

## G. Open-ended structural growth

### Open-Ended Structural Intelligence Growth (OESIG)
A proposed capacity to discover, evaluate, integrate, revise, and retire representations, capabilities, and interfaces over time. “Open-ended” does not mean unconstrained or monotonically improving.

### Structural Delta
A proposed modification to a structure, such as adding a node, changing a relation, refining a constraint, or replacing an execution route.

### Growth Operator
An authorized transformation on the structural system. Proposed operators include **Add, Replace, Split, Merge, Refine, Restrict, Retire, and Delegate**.

### Evidence-Gated Growth
A process that admits structural updates only after relevant tests, counter-evidence review, policy checks, and explicit promotion criteria.

### Delta Promotion
The controlled transition of a candidate structural change from experimentation into an approved operational version, ideally with rollback support.

### Sandbox Validation
Evaluation of proposed capabilities or structural changes in a bounded environment before live deployment; sandboxing reduces but does not eliminate risk.

### Rollback
Restoration of a prior authorized state or version when a deployment fails, regresses, or violates policy. Not all real-world side effects are reversible.

### Portable Intelligence Runtime Piece (PIRP)
A proposed portable intelligence component or fragment intended for reuse, adaptation, or exchange across environments, subject to interface and governance constraints.

### Portable Intelligence Runtime Unit (PIRU)
A more formally specified and packaged portable unit with explicit contracts, dependencies, and validation requirements.

### Collective Structural Learning (CSL)
Cross-agent or cross-organization improvement through exchange of validated structural knowledge or components, while respecting ownership, licensing, provenance, and policy boundaries.

## H. Research methodology

### Baseline
A comparison system used to test incremental value. Relevant baselines include **LLM-only**, **LLM with tools**, and established **hybrid or specialist systems**.

### Ablation Study
An experiment removing one proposed mechanism—such as boundary diagnosis, localization, CCC metadata, or evidence gating—to estimate its contribution.

### Falsifiable Hypothesis
A claim paired with observations or experimental outcomes that could disconfirm it. BLB-SHI hypotheses are research propositions, not validated findings.

### Counterexample
A concrete task or deployment where a proposed advantage fails, such as a generalist LLM outperforming a complex hybrid system after integration overhead is included.

### Fair Comparison
An evaluation controlling for task mix, quality targets, tools, model versions, compute budgets, human effort, and total lifecycle cost as appropriate.

### Provenance
The documented origin, transformations, and authority of data, evidence, models, or structural units used in a decision.

## I. Key distinctions at a glance

| Do not conflate | With |
| --- | --- |
| Language coverage | Representation sufficiency |
| Descriptive expressibility | Operational efficiency |
| Representation translation | Lossless or inexpensive translation |
| Perspective simulation | Perspective sovereignty |
| Shared intelligence capability | Shared context ownership |
| Localization | Execution |
| CCC identifier | CCC-native computation |
| Verification evidence | Guaranteed correctness |
| Candidate structural delta | Authorized deployment |
| Open-ended growth | Unbounded or inevitable improvement |
| Lower inference cost | Lower total lifecycle cost |
| Architecture proposal | Empirically validated system |

## J. Paper cross-reference

| Paper | Primary vocabulary |
| --- | --- |
| [BLB-001](docs/BLB-001-Language-Intelligence-and-the-Limits-of-Universal-Coverage.md) | LAIH, language coverage, sufficiency, boundary profile |
| [BLB-002](docs/BLB-002-Computational-Representation-Barriers-Beyond-Natural-Language.md) | CRB, translation, representation graph |
| [BLB-003](docs/BLB-003-The-Economics-of-LLM-Scaling-and-Structural-Specialization.md) | Marginal economics, break-even, structural debt |
| [BLB-004](docs/BLB-004-Perspective-Sovereignty-Ownership-and-the-All-in-One-Boundary.md) | Perspective sovereignty, ownership partition, policy |
| [BLB-005](docs/BLB-005-Decoupling-Structural-Localization-from-Per-Node-Intelligence.md) | LED, MDT, UTN, contracts, per-node intelligence |
| [BLB-006](docs/BLB-006-CCC-Native-Intelligence-and-Structural-Semantic-Units.md) | CCC, SSU, L1–L3, CNSE |
| [BLB-007](docs/BLB-007-BASHI-Boundary-Aware-Structural-Hybrid-Intelligence-Architecture.md) | BASHI, boundary diagnosis, route optimization |
| [BLB-008](docs/BLB-008-From-LLM-Boundaries-to-Open-Ended-Structural-Intelligence-Growth.md) | OESIG, structural delta, evidence-gated growth, CSL |

## K. Terminology maintenance

1. Preserve the six boundary axes across papers; document any proposed additions separately.
2. Do not use “native,” “sovereign,” “verified,” or “optimal” without specifying the implementation or evidence standard.
3. Keep **policy authorization** distinct from soft cost/risk optimization.
4. Distinguish **research hypotheses** from **benchmarked results** and **implemented interfaces**.
5. Record definition changes in `CHANGELOG.md`, and update the affected papers and navigation files.

---

**Suggested citation:** Sizhe Tan & GPT-Obot (2026). *Beyond the LLM Boundary: Structural Hybrid Intelligence, Representation Barriers, and the Future of AI Architecture*, v1.0.0. See `CITATION.cff` for release-specific citation metadata.

**License:** Apache-2.0, subject to the repository's `LICENSE` file.
