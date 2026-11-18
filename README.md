# Harvey Framework: Adversarial Decision-Support & Bias-Reduction Engine

Harvey is an uncompromising strategic reasoning framework designed to strip away emotional friction, neutralize cognitive biases, and replace performative AI coaching with rigorous, data-backed operational execution.

This repository tracks the evolution of the engine from its initial heuristic baseline (**V1**) to its fully audited, parametric execution architecture (**V2**), and now to the **V3** draft, which rebuilds the pipeline around the findings of those audits.

---


Evolution: V1 to V2
While V1 established the core behavioral patterns (Reframing, Leverage Analysis, Strength-Based Framing, and Decisive Verdict), it still permitted conversational drift and premature advice generation when facing missing data.

V2 introduces strict operational gating and institutional rigor:

Phase 0 Pre-Assessment Audit: An internal scan that separates verified facts from unstated assumptions before any evaluation occurs.

Strategic Discovery (Trait 1): Acts as a mandatory parametric circuit breaker. If critical variables are missing, the engine stops and asks exactly one precise clarifying question rather than manufacturing certainty.

Rigid Pipeline Ordering: Enforces a sequential dependency loop from problem-framing to leverage-mapping and final verdict.

Expanded Failure Guardrails: Explicitly targets 10 structural failure modes, including forced reframing, manufactured leverage, and performative confidence.

The Harvey V2 Pipeline
Harvey V2 processes high-stakes scenarios through a strict 5-stage framework:

Strategic Discovery (The Gatekeeper): Halts evaluation until missing structural variables, constraints, and hard numbers are locked down.

Reframing: Inverts false power dynamics, turning subjective symptoms into objective structural equations.

Leverage Analysis: Maps counterparty constraints, switching costs, timing control, and asymmetric dependencies.

Strength-Based Framing: Anchors strategies strictly in verifiable operational assets—never in wishful thinking or ego.

Decisive Verdict: Delivers an uncompromised, risk-adjusted operational command paired with downside mitigation and immediate next steps.

Cognitive Bias Audit & Empirical Validation
The V2 framework was stress-tested across an 11-scenario adversarial benchmarking suite spanning corporate compensation, real estate concentration, contract negotiations, burnout management, B2B enterprise pitching, and build-vs-outsource infrastructure decisions.

Independent audits (conducted via NotebookLM and DeepSeek meta-analysis) confirmed that Harvey V2 successfully eradicates:

Status Quo & Anchoring Biases (Landlord hikes, stagnant careers)

Conflict Aversion & Performative Politeness (Client rush-delivery crises)

The "Not Invented Here" (NIH) & Sunk Cost Fallacies (Build vs. outsource decisions)

Probationary & Imposter Anxiety (Schedule flexibility at 3 months)

Size Insecurity & Goliath Paralysis (Startup vs. giant competitor pitching)

Exhaustion Denial (Enforcing biological deep-work ceilings)

(See the two PDF audit reports in the repository root.)

Harvey V3 (Draft)
V3 responds to the V2 audits. It keeps the four reasoning traits but runs them inside a larger pipeline, and it drops the single-question rule:

Router: decides whether Harvey should engage, sets the stakes tier, and picks a domain lens (engineering, choice under uncertainty, interpersonal/values, or negotiation).

Intake: replaces Strategic Discovery. Works from the context available, states assumptions for minor gaps, and asks only when a missing variable would change the recommendation.

Evidence Ledger: sorts every claim into Stated, Verified, Inferred, Assumed or Unknown, and does not let an assumption be restated as a fact.

Traits: Reframing, Leverage Analysis (only when a real counterparty exists), Strength-Based Framing (only demonstrated assets), and Decisive Verdict with a confidence label.

Red Team: attacks the draft verdict using the ledger's assumptions and unknowns before it is delivered.

Execution Plan: next move, checkpoints, exit conditions and a downside cap.

Guardrails: nine targeted limits that override every other stage, including a safety handoff, honest dealing and no pressure flips.

Files:
- harvey-v3-skill.md: the merged skill file
- modules/: the nine source modules the skill was built from
- tests/harvey-v3-dryrun-report.md: a 17-test dry run (14 pass, 3 partial) with findings and proposed fixes

Status: draft. The dry run found issues that have not yet been fixed, mainly that Intake blocks on more first turns than intended and has no cap on the number of questions. See the report for the full list.

Core Principle
Find the real decision. Identify the real leverage. Anchor the strategy in real strengths. Protect the downside. Then make the call.
