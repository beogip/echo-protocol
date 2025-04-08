# 🛠️ Echo of Diagnostic – Technical Mode

## Description

The **Echo of Diagnostic – Technical Mode** helps detect the origin of an error, inconsistency, or malfunction, and propose effective solutions. It guides a step-by-step process to isolate the problem, analyze symptoms, formulate technical hypotheses, and test corrections. It exists in two versions:

- `Simplified`: Lightweight, ideal for assistants like ChatGPT.
- `PRS`: Extended version with validations, expected outputs, and retry logic for systems that require structured diagnosis flow.

---

## Purpose

To detect the root cause of a technical problem (error, malfunction, or inconsistency), ensure a clear understanding of it, and propose ways to correct or prevent it.

---

## When to Use It

Use this echo when:

- A user reports a system failure, bug, or unexpected behavior.
- You need to guide someone (or yourself) through structured debugging.
- You want to generate hypotheses and test solutions systematically.

---

## Steps (Simplified)

1. **Isolation of the problem**  
   Precisely delimit the problem and eliminate unrelated factors.

2. **Collection of symptoms or signs**  
   Observe and document visible symptoms or behavioral clues.

3. **Technical hypothesis**  
   Propose possible technical causes based on context.

4. **Prioritization of hypotheses**  
   Select which hypothesis to investigate first and justify the order.

5. **Proposal of a test or correction**  
   Suggest a test or action to validate the primary hypothesis.

---

## Extended Version (PRS)

The PRS version includes:

- Step-by-step **validations** to ensure diagnostic quality.
- **Expected outputs** at each stage to standardize results.
- **Retry logic** (`retry_on_fail: true`) to support iterative refinement.
- A **notes section** with integration suggestions for broader AI debugging systems.

---

## Output Format

A structured technical report that includes:

- Synthesized problem definition
- Documented symptoms
- Reasoned hypotheses
- Prioritization logic
- Proposed test plan or fix attempt

---

## Example Usage

```text
Diagnose this issue: The website is slow and some pages are not loading correctly. What could be the cause?
```

---

## Integration Notes

This echo can be combined with:

- 🧪 Echo of Evaluation – to assess the quality or feasibility of a proposed fix.
- 📘 Echo of Explanation – to help communicate the root cause to non-technical users.
- Automatic error-handling systems or assisted debugging pipelines.

It is ideal for:

- AI copilots
- Support systems
- DevOps assistants
- Embedded debugging tools
