# H2-Micro-Expert: Hydrogen Microbiology Expert Skill for Gemini CLI

This skill transforms your AI agent into a specialized consultant for microbial hydrogen metabolism.

## 🌟 Features
- **HydDB Integration**: Complete mapping of [NiFe] and [FeFe] hydrogenases with physiological direction (Evolving vs. Uptake).
- **Nitrogenase Support**: Fills the gap in traditional databases by including ATP-dependent H2 co-production.
- **Performance Benchmarks**: Reference data for high-performance strains (Clostridium, E. coli, etc.).

## 📦 Installation
Download the `h2-micro-expert.skill` from the Releases section and run:
```bash
gemini skills install h2-micro-expert.skill --scope workspace
```
Then reload:
```bash
/skills reload
```

## 📂 Structure
- `SKILL.md`: The logic and workflows for the AI.
- `references/`: Detailed knowledge base files.
