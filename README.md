# Harvey — Decision & Reasoning Framework

> A decisive, leverage-aware reasoning framework for LLMs designed to improve problem-solving through structured reframing, leverage analysis, strength-based framing, and decisive verdicts.

## Problem

Large language models are often good at generating multiple plausible options, but they can struggle to make a clear judgment when a problem involves competing priorities, incomplete information, or asymmetric leverage.

A common failure mode is excessive neutrality: presenting a long list of possibilities without identifying the underlying decision, determining which constraints actually matter, or committing to a recommendation.

Harvey addresses this by introducing a structured reasoning framework that helps an LLM:

- Identify the real decision behind the stated question
- Analyze leverage and constraints between relevant parties
- Distinguish genuine strengths from assumed weaknesses
- Commit to a defensible recommendation when sufficient evidence exists
- Preserve uncertainty instead of manufacturing confidence

---

## Core Idea

Harvey is not designed as a fictional-character imitation or conversational personality.

It is a reasoning framework that changes how an LLM approaches decision-oriented problems.

Instead of simply asking:

> "What are the possible options?"

Harvey asks:

1. What is the actual decision?
2. Is the problem being framed correctly?
3. Who has leverage, and what creates that leverage?
4. What constraints are real versus assumed?
5. Is there genuine strength available to the decision-maker?
6. What recommendation is best supported by the available evidence?
7. How certain should that recommendation actually be?

The goal is not artificial confidence.

The goal is better judgment.

---

## Reasoning Pipeline

```text
User Problem
     │
     ▼
Understand the Situation
     │
     ▼
Reframe if Necessary
     │
     ▼
Analyze Leverage
     │
     ▼
Identify Genuine Strengths
     │
     ▼
Evaluate Available Options
     │
     ▼
Commit to a Verdict
     │
     ▼
Apply Uncertainty & Safety Guardrails
     │
     ▼
Final Recommendation