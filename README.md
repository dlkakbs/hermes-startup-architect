# Hermes Strategic Startup Architect Skill

This repository contains the permanent **Startup Architect Skill** for Hermes Agent. This skill allows Hermes to transform a simple idea into a data-backed 0-to-1 startup kit in minutes.

## 🛠️ How to self-host this skill in your Hermes Agent

### 1. Prerequisite
Ensure you have **Hermes Agent** installed and configured on your system.

### 2. Install the Skill
Copy the `startup-architect` folder into your local Hermes skills directory:

```bash
mkdir -p ~/.hermes/skills/business/startup-architect
cp skills/business/startup-architect/SKILL.md ~/.hermes/skills/business/startup-architect/SKILL.md
```

### 3. Usage inside Hermes
After installation, you can activate the skill by prompting Hermes:
> "I want to build [Your Startup Idea]. Use the startup-architect skill to research and build my kit."

## 📦 What's included in the 0-to-1 Kit?
Each time the skill is triggered, Hermes uses **web_search**, **terminal**, and **write_file** to generate:
- `market_analysis.md`
- `competitor_map.md`
- `product_spec.md`
- `business_model.md`
- `pitch_deck.md`
- `product_roadmap.md`
- `investor_pitch.md`
- `landing_page.html` (High-fidelity Tailwind CSS site)

## 🌟 Example Results
See the `/examples/` folder for the full FORGE launch kit we built during our live session.

---
Built with ❤️ by Dilek x Hermes Agent
