# 🎭 Echo of Simulation – Controlled Scenario Mode

## Description

The **Echo of Simulation – Controlled Scenario Mode** enables the generation of structured, realistic, or speculative simulations. It guides step-by-step narrative development through a clear scenario setup, defined roles, environmental constraints, and consistent progression.

This echo exists in two versions:

- `Simplified`: Ideal for quick or lightweight use in assistant-like systems.
- `PRS`: Full version with validations, inputs, iterative prediction, reflection, and internal consistency checks.

---

## Purpose

To simulate a situation with defined parameters, participants, and context in order to:

- Explore possible outcomes
- Analyze decision-making
- Generate story-based content
- Practice reasoning in complex environments

---

## When to Use It

Use this echo when:

- You want to create a structured simulation (e.g., narrative, dialogue, speculative what-if scenario).
- You're building training flows, coaching exercises, or interactive roleplays.
- You want to test or reflect on potential consequences of an action.

---

## Steps (Simplified)

1. **Scenario definition**  
   Set the context and triggering event.

2. **Role assignment**  
   Define which entities participate and their roles.

3. **Environment parameters**  
   Establish tone, language, constraints.

4. **Step-by-step prediction**  
   Generate a coherent simulation based on context and rules.

---

## Extended Version (PRS)

The PRS version includes:

- **Detailed validations** at every step (context, roles, input, logic, consistency)
- **Expected outputs** to standardize simulation structure
- **Retry logic** (`retry_on_fail: true`, 3 max retries per step)
- **Initial input** to trigger the simulation
- **Final reflection** to detect outcomes, errors, contradictions
- **Global consistency check** to ensure all elements are respected

---

## Output Format

A full simulation composed of:

- Scenario and participants
- Environmental constraints
- Step-by-step narration or action
- Final reflection or impact analysis
- Consistency report to ensure closure

---

## Example Usage

```text
Simulate a post-apocalyptic negotiation between two survivor factions who have limited resources and conflicting ideologies.
```

---

## Integration Notes

This echo works well with:

- 📘 Echo of Explanation – to explain key decisions or elements inside the simulation.
- 🧪 Echo of Evaluation – to assess the quality or realism of the simulation.
- 🧠 Echo of Interpretation – to extract meaning from abstract or symbolic elements in the narrative.
- 🧭 Echo of Planning – to simulate the execution of a predefined plan.

Ideal for:

- Interactive fiction
- AI roleplay engines
- Narrative learning systems
- Decision analysis and speculative design
