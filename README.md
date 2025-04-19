# 🧠 Echo Protocol Repository

## Introduction

Welcome to the **Echo Protocol** repository. This collection contains structured **echoes** designed to guide AI processes in areas like evaluation, diagnosis, reflection, simulation, planning, and more.

Each echo defines a clear cognitive flow and can be executed by assistants, agents, or AI systems that support structured reasoning.

There are two versions available for each echo:

- **Simplified**: Lightweight and ideal for fast iterations, e.g., in ChatGPT or similar interfaces.
- **PRS (Processed Response Structure)**: Full version with validations, expected outputs, retry logic, and detailed documentation for deeper integrations.

---

## 📚 Echoes Available

Each folder contains:

- `echo-name.yaml` → Simplified version
- `echo-name.prs.yaml` → Full PRS version
- `README.md` → Human-readable explanation

| Echo Type             | Description                                           |
| --------------------- | ----------------------------------------------------- |
| ✅ **Coherence**      | Self-correction of flow when focus or purpose is lost |
| 🛠️ **Diagnostic**     | Technical analysis to detect the root of a problem    |
| 🧪 **Evaluation**     | Structured judgment using explicit criteria           |
| 📘 **Explanation**    | Progressive teaching adapted to the user’s level      |
| 🧠 **Interpretation** | Semantic analysis of ambiguous or symbolic input      |
| ⚙️ **Optimization**   | Refactor or improve without losing intention          |
| 🧭 **Planning**       | Step-by-step structure for learning or execution      |
| 🧘 **Reflection**     | Closing cycles and integrating personal change        |
| 🎭 **Simulation**     | Controlled scenario generation with internal logic    |

---

## 🧰 How to Use

To use any echo:

1. Choose the simplified or PRS version inside `/echoes/[type]/`
2. If you're building an AI system, use the PRS version and validate steps
3. If you're prototyping with ChatGPT or similar, use the simplified version
4. Check the `.md` file inside each folder for a human-readable explanation

---

## 🧪 Echo Template

You can create your own echoes using the official templates:

- [echo-template.prs.yaml](./templates/echo-template.prs.yaml) (English)
- [echo-template.prs.es.yaml](./templates/echo-template.prs.es.yaml) (Español)

---

## 🤝 Contributing

Feel free to open issues or submit pull requests to expand the ecosystem.  
New echoes, refinements or translations are welcome!

---
