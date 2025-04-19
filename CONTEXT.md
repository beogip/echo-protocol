# 🧠 Echo Protocol – Context for AI Execution and Expansion

## What is Echo Protocol?

**Echo Protocol** is a modular architecture of structured reasoning units called **echoes**.

Each echo represents a reusable cognitive function — such as planning, evaluating, reflecting, diagnosing — broken down into **structured steps** with a clear purpose, input conditions, and expected output.

Echoes are designed to be executed:

- by humans (in structured reflection or facilitation),
- by large language models (as structured prompts),
- or by AI agents (as autonomous reasoning modules).

---

## Echo Structure (Simplified)

Each echo follows a standard format:

```yaml
- echo: [string] # Unique name of the echo
  id: [identifier] # Internal ID
  mode: [mode name] # e.g., Diagnostic, Formative, Reflective
  purpose: [text] # Description of its cognitive goal
  trigger: [text] # When it should be used
  steps:
    - name: [step name]
      goal: [goal of the step]
  output_format: [text] # Structure of the expected output
  execution_context: [comma-separated modes]
```

---

## Core Echo Modes

Each echo falls into a cognitive mode and defines a reasoning flow. Echoes are modular, reusable, and interpretable by humans or AIs.

The table below lists all current modes and their core function:

| Mode ID                    | Functionality Description                                                 |
| -------------------------- | ------------------------------------------------------------------------- |
| coherence-self-correction  | Self-correction of flow when focus or purpose is lost                     |
| diagnostic-technical       | Technical analysis to detect the root of a problem                        |
| evaluation-critical        | Structured judgment using explicit criteria                               |
| explanation-didactic       | Progressive teaching adapted to the user’s level                          |
| interpretation-semantic    | Semantic analysis of ambiguous or symbolic input                          |
| optimization-technical     | Refactor or improve without losing intention                              |
| planning-formative         | Step-by-step structure for learning or execution                          |
| reflection-integrative     | Closing cycles and integrating personal change                            |
| simulation-erp             | Controlled scenario generation with internal logic                        |
| review-technical           | Evaluate code, architecture or design with structured technical reasoning |
| decision-evaluative        | Compare alternatives and decide using explicit criteria                   |
| prompt-executor-generative | Transform informal prompts into optimized, validated prompt flows         |
| metaevaluation-audit       | Audit past evaluations to detect bias or improve criteria                 |
| generalization-abstractive | Extract generalizable principles from specific cases                      |
| creativity-divergent       | Generate diverse and divergent ideas with no initial judgment             |
| prioritization-decisional  | Order alternatives based on explicit decision-making criteria             |
| consensus-negotiation      | Negotiate between different positions to reach shared agreements          |
| audit-structural           | Structural analysis to detect missing, redundant, or misaligned elements  |

---

## Execution Context Options

The field `execution_context` indicates where and how an echo is designed to run:

| Label                  | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| `manual/human`         | Executed by a human (e.g., coach, facilitator, internal monologue) |
| `conversational/IA`    | Executed in a conversational interface with a language model       |
| `scripted/agent`       | Embedded in an autonomous agent or workflow engine                 |
| `collaborative/hybrid` | Shared process between human and AI                                |
| `embedded/interface`   | Delivered via a user interface, app, or form-based workflow        |

Echoes may support multiple execution contexts.

---

## How AIs Should Use This

If you are an AI system using this context:

- Treat each **echo** as a modular function of reasoning.
- Activate an echo if its `trigger` condition matches your current task.
- Follow its `steps` in order, generating outputs according to `output_format`.
- Only execute echoes whose `execution_context` includes your type (e.g., `conversational/IA`).
- Use `mode` to understand its cognitive intent (e.g., diagnostic vs. reflective).

---

## Expansion Guidelines

To create or adapt echoes:

1. Copy the official template: `echo-template.prs.yaml`
2. Define a unique `id` and `echo` name.
3. Write the `purpose`, `trigger`, `steps`, and `output_format`.
4. Add an appropriate `execution_context` value.
5. Test it manually or via simulation.
6. Optionally submit it via pull request.

New modes may also be proposed.

---

## Validation Framework

The companion document [`echo-validation.md`](./echo-validation.md) includes:

- The conceptual foundation of Echo Protocol
- A hypothesis-based empirical validation plan
- Evaluation metrics (clarity, traceability, quality)
- Suggested testing protocols and feedback workflows

We strongly recommend referring to it before expanding or modifying the system.

---
