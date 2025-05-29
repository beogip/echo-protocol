# 🧪 Echo of Evaluation – Structured Mode

## Description

The **Echo of Evaluation – Structured Mode** provides a modular way to assess the quality, effectiveness, or technical solidity of any object (proposal, code, plan, output, etc.). It supports both general (critical) and technical evaluations, offering explicit criteria, user confirmation checkpoints, and actionable recommendations.

This echo exists in two versions:

- `Simplified`: Lightweight, ideal for quick evaluations in assistants.
- `PRS`: Full version with step validations, user checkpoints, and adaptive criteria logic.

---

## Purpose

To evaluate a deliverable, idea, or technical artifact using explicit criteria confirmed by the user. It ensures traceable, fair, and structured judgments, and supports feedback loops for refinement.

---

## When to Use It

Use this echo when:

- You want to evaluate a result, code, decision, proposal, or design.
- You see prompts like:  
  “Can you review this?”, “How good is this?”, “Should we use this version?”
- You want the evaluation to be clear, criteria-based, and actionable.
- You need to distinguish between general criticism and technical review.

---

## Steps (Simplified)

1. **Detection of the object to evaluate**  
   Clarify what is being evaluated and its purpose.

2. **Selection of evaluation mode**  
   Choose between _critical_ (general) or _technical_ evaluation.  
   _🛑 User input required._

3. **Definition of evaluation criteria**  
   Suggest and confirm which criteria to apply.  
   _🛑 User input required._

4. **Evaluation by criteria**  
   Analyze the object against each confirmed criterion.

5. **Global valuation and recommendation**  
   Conclude with a structured judgment and suggest what to do next.

---

## Extended Version (PRS)

The PRS version includes:

- **Dynamic submodes**: `critical` for general quality, `technical` for code/architecture
- **Explicit user checkpoints**:
  - One after selecting the mode
  - One after setting the criteria
- **Step validations**: Object clarity, mode adaptation, per-criterion logic
- **Output formatting**: clear, modular, and usable in assistant pipelines
- **Retry logic**: `retry_on_fail: true`, up to 3 retries for robust flow integrity

---

## Output Format

A structured evaluation containing:

- Description of the evaluated object
- Confirmed evaluation mode and criteria
- Per-criterion analysis (strengths, weaknesses, justification)
- Final judgment and recommendation

---

## Example Usage

```text
Please review this function:
function validateUserInput(input) {
  if (!input.email.includes("@")) return "Invalid";
  return "OK";
}
Is it good enough for production?
```

---

## Integration Notes

This echo is compatible with:

- ⚙️ Echo of Optimization – to improve objects after weak evaluations
- 🧐 Echo of Metaevaluation – to audit and reflect on prior judgments
- 🛠️ Echo of Diagnostic – when low performance hints at underlying structural issues
- 🧭 Echo of Planning – to validate the structure of a proposal before execution

It is ideal for:

- Code reviews and architectural assessments
- Assistant reasoning checkpoints
- Plan and prompt evaluation in AI systems
- Any system requiring evaluative traceability
