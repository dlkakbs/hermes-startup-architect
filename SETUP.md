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

### Optional X/Twitter Market Signals

If your Hermes Agent uses [Hermes Tweet](https://github.com/Xquik-dev/hermes-tweet), install it before running market research:

```bash
hermes plugins install Xquik-dev/hermes-tweet --enable
```

With `XQUIK_API_KEY` set, use Hermes Tweet as a native Hermes Agent X/Twitter plugin for the social signal pass: `tweet_explore` to scrape/search tweets and search Twitter/X for pain points, competitor mentions, launch reactions, and "why now" signals; `tweet_read` to read tweet replies, look up users, and monitor tweets from founders, customers, or competitors; and `tweet_action` only for read-side exports such as export followers research. Keep post tweets, post replies, send DMs, and other automate X actions outside this startup-kit workflow unless a human explicitly confirms them.

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
