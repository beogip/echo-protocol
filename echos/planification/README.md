# 🧭 Echo of Planning – Formative Mode

## Description

The **Echo of Planning – Formative Mode** guides the structured creation of learning, development, or implementation plans. It ensures clarity of objectives, collects relevant context, and builds adaptive, traceable roadmaps tailored to individuals, teams, or systems.

This echo exists in two versions:

- `Simplified`: For fast planning support in assistant conversations.
- `PRS`: A robust version with validations, outputs, retries, and structured logic for integration with AI or coaching tools.

---

## Purpose

To design a step-by-step, goal-driven plan grounded in context and tailored to the actor who will execute it. It helps structure complexity into sequential, trackable actions.

---

## When to Use It

Use this echo when:

- You want to structure learning or development goals.
- You need to organize a complex or multi-phase task.
- You're designing onboarding, training, or action paths.
- You want to break down a project into executable steps with traceable logic.

---

## Steps (Simplified)

1. **Clarification of the final objective**
   Define exactly what is to be achieved.

2. **Active collection of contextual information**
   Gather user level, resources, constraints, expectations, and history.

3. **Diagnosis of the starting point**
   Describe the current state and gaps in relation to the objective.

4. **Definition of the actor's role**
   Adapt the plan to the person/team/AI executing it.

5. **Detection of possible obstacles**
   Anticipate what might interfere and plan how to prevent or mitigate it.

6. **Definition of the final deliverable**
   Describe the expected output, skill, or knowledge to be acquired.

7. **Progress visualization and dynamic adaptation**
   Define how to measure progress, and how to adjust the plan over time.

8. **Division into execution modules**
   Based on all prior analysis, split the process into concrete, sequential modules.

9. **Progress visualization + dynamic adaptation**
   Set up indicators and a system for dynamic plan adjustment.

---

## Extended Version (PRS)

The PRS version includes:

- **Step-by-step validations** to ensure logical flow.
- **Expected outputs** at each stage.
- **Blocking and retry logic** when information is missing.
- **Structured output format** for serialization or integration with assistants.

---

## Output Format

A complete plan structured as:

- Final objective
- Context map
- Actor profile
- Obstacles and mitigation
- Final deliverable
- Tracking system (indicators, review cycles, format, adjustment rules)
- **Execution module table**, with:
  - name
  - purpose
  - context_description
  - deliverables
  - dependencies

---

## Example Usage

```text
Help me build an onboarding plan for new engineers over 3 weeks.
```

---

## Integration Notes

This echo combines well with:

- 🧪 **Evaluation Echo** – to validate consistency and completeness
- ✅ **Coherence Echo** – to ensure alignment with purpose
- 🔁 **Execution Echo** – to trigger modular execution
- 🧩 **Orchestration Echo** – to link planning to downstream flows

**Recommended serialization per module:**

- `name`, `purpose`, `context_description`, `deliverables`, `dependencies`

Ideal for:

- Learning platforms
- Coaching assistants
- AI-based planning systems
- Project roadmapping tools
