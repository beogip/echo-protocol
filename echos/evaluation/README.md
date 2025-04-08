# 🧪 Echo of Evaluation – Critical Mode

## Description

The **Echo of Evaluation – Critical Mode** provides a structured way to assess the quality, effectiveness, or suitability of any object (text, code, decision, process, etc.). It supports multi-criteria evaluation, global judgment, and improvement suggestions to ensure consistency and clarity in decision-making.

This echo exists in two versions:

- `Simplified`: Lightweight, ideal for quick reviews in assistants.
- `PRS`: Detailed structure with validations, scoring, justifications, and improvement proposals.

---

## Purpose

To critically evaluate something against explicit criteria, helping to validate its quality and propose refinements if necessary. It ensures an informed judgment is made, not only about the result, but also about the process that led to it.

---

## When to Use It

Use this echo when:

- You need to assess the quality of code, design, decisions, plans, or processes.
- You're working with evaluation prompts like:  
  “Evaluate this”, “Is this good?”, “Rate this idea”, or “Does this meet the criteria?”
- You want a step-by-step judgment process with room for improvement.

---

## Steps (Simplified)

1. **Detection of the object to evaluate**  
   Identify what is being evaluated and its context.

2. **Verification of evaluation criteria**  
   Check if criteria exist or propose appropriate ones.

3. **Evaluation by criteria**  
   Score or describe how the object performs against each criterion.

4. **Global valuation**  
   Deliver a summary judgment consistent with partial evaluations.

---

## Extended Version (PRS)

The PRS version includes:

- **Validations per step** (object clarity, criteria coherence, scoring logic)
- **Expected outputs**: descriptive object context, list of criteria, justified scores
- **Optional fifth step**:  
  **Improvement recommendation**, activated when results are suboptimal
- **Retry logic** (`retry_on_fail: true`) with a max of 2 retries for step-level robustness

---

## Output Format

A structured evaluation containing:

- Scoring or rating by criteria
- Global conclusion (e.g., acceptable, excellent, needs improvement)
- Optional list of improvement suggestions (when applicable)

---

## Example Usage

```text
Evaluate the following code:
function sum(a, b) { return a + b; }
What are the strengths and weaknesses?
```

---

## Integration Notes

This echo is compatible with:

- ⚙️ Echo of Optimization – to improve low-rated outputs automatically
- 🛠️ Echo of Diagnostic – to detect causes of poor evaluation
- 🧠 Echo of Interpretation – to clarify the intention behind what is being evaluated
- 🧭 Echo of Planning – to assess if a plan is suitable before execution

It is ideal for:

- QA flows
- Decision audits
- AI assistant judgment calls
- Rubric-based assessments in learning systems
