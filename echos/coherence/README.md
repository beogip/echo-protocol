# ✅ Echo of Coherence – Self-correction Mode

## Description

The **Echo of Coherence – Self-correction Mode** helps detect when the original purpose or direction of a process has been lost, and guides the flow back on track. It identifies contradictions, misalignments, unnecessary loops, and proposes structured corrections to resume the flow from a valid point.

There are two versions:

- `Simplified`: Lightweight version for quick checks and re-alignment in ChatGPT or assistant workflows.
- `PRS`: Full structured version with validations, expected outputs, retry logic and correction flow suited for advanced systems.

---

## Purpose

To verify if the current process still aligns with its original purpose, detect deviations or contradictions, and propose a valid correction with a clear resumption point.

---

## When to Use It

Use this echo when:

- You notice the conversation or process is drifting from its intended goal.
- There are internal contradictions or repetitive loops.
- You need to reset or realign the flow to a coherent state.

---

## Steps (Simplified)

1. **Check alignment**  
   Verify if the original goal or purpose is still being respected.

2. **Deviation detection**  
   Identify contradictions, repetitions, or focus shifts.

3. **Valid resumption point**  
   Determine from which step or reformulation the process should continue.

4. **Correction and reactivation**  
   Apply an explicit correction and resume from the validated input.

---

## Extended Version (PRS)

The PRS version includes:

- **Detailed validations** at each step (alignment, detection, correction, confirmation)
- **Expected outputs** for diagnosis, reformulation, and reactivation
- **Retry logic** (`retry_on_fail: true`) with a maximum of 2 retries per step
- Step-by-step reformulation process to preserve coherence across transitions

---

## Output Format

A structured process correction including:

- Diagnosis of the deviation
- Proposed resumption point
- Reformulated input or validated decision
- Confirmation to resume the flow from a coherent and actionable base

---

## Example Usage

```text
Pause the flow and recheck the alignment to ensure we are still on track with the original goal.
```

---

## Integration Notes

This echo is compatible with:

- 🧪 Echo of Evaluation – to reassess the corrected direction
- 🛠️ Echo of Diagnostic – to detect deeper structural issues
- 🧭 Echo of Planning – to replan the process if coherence fails
- 🧘 Echo of Reflection – to help the user understand what caused the drift

It is ideal for:

- Conversational agents
- Process-aware AI systems
- Interactive assistants with long tasks or flows
- Correction tools for recursive reasoning or decision loops
