# CODE-GATE Project

**An Autonomous Development Framework powered by Gemini CLI.**

## 🚀 Overview
CODE-GATE is a meta-framework designed to enhance AI coding agents with:
1.  **Long-term Memory:** Project Wiki (`knowledge.md`) persistence.
2.  **Strategic Planning:** The `Conductor` extension with dynamic re-planning.
3.  **Self-Correction:** A "Critic" loop to audit plans before execution.
4.  **Reference Intelligence:** A curated library of System Prompts from top AI engineering tools (Devin, Cline, AutoGPT).

## 📂 Structure
- `conductor-enhanced/`: The custom Gemini CLI extension implementing the logic.
- `references/`: Cloned source code of AutoGPT, MetaGPT, BabyAGI for architectural study.
- `system_prompts_raw/`: The massive collection of system prompts from `x1xhlol/system-prompts-and-models-of-ai-tools`.
- `prompts/reference/`: Curated "Gold Standard" prompts (Devin Wiki, Traycer Planning).

## 🛠️ Key Features (Conductor v2)
- `/conductor:critic` - Audits your `plan.md` for risks.
- `/conductor:replan` - Handles major strategy shifts (e.g., "Switch to React").
- `/conductor:remember` - Saves constraints to `knowledge.md`.
- `/conductor:prioritize` - Re-orders tasks based on urgency.

## 🤝 Acknowledgements
- **System Prompts Collection:** [x1xhlol](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **Architectural References:** AutoGPT, MetaGPT, BabyAGI.
