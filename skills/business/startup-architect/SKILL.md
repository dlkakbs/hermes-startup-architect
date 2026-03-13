---
name: startup-architect
description: A comprehensive workflow for researching a startup idea and generating a full startup kit including market analysis, competitor mapping, product specs, and a high-fidelity landing page.
version: 1.0.0
triggers:
  - "startup idea:"
  - "analyze this startup:"
  - "create a startup kit for"
  - "here is my startup concept"
---

# Startup Architect Skill

This skill transforms a raw startup idea into a comprehensive, research-backed startup kit. It ensures every analysis is based on real market data and results in high-fidelity deliverables.

## Workflow

### STEP 1: MARKET RESEARCH (Mandatory)
Perform at least 3 distinct web searches to gather real data.
- **Search 1:** Market size (TAM/SAM/SOM), growth rates, and industry trends.
- **Search 2:** Top competitors, their pricing, and market positioning.
- **Search 3:** Market gaps, customer pain points, and "Why Now" factors.
- **Goal:** Extract real numbers, specific company names, and current year trends.

### STEP 2: PROJECT INITIALIZATION
Create the target directory for the assets.
```bash
mkdir -p ~/Desktop/startup_kit
```

### STEP 3: ASSET GENERATION
Generate the following 8 files one-by-one. **Confirm each file with ✅ before moving to the next.** Use `write_file` or `terminal` to save content. No placeholder text allowed.

1. **market_analysis.md**
   - Detailed TAM/SAM/SOM with real researched numbers.
   - 3-5 major market trends and key opportunities.
   - Analysis of current market dynamics.

2. **competitor_map.md**
   - Profile 5 real competitors: Name, URL, Pricing, Strengths, Weaknesses.
   - Identify the specific gap/unfair advantage we exploit.

3. **product_spec.md**
   - Problem/Solution statement.
   - List of 5 core MVP features (max).
   - Tech stack recommendation (FE/BE/DB/hosting).
   - Core differentiator.

4. **business_model.md**
   - Revenue streams and pricing tiers (Free/Pro/Enterprise).
   - Basic unit economics and growth loops.
   - Top 3 KPIs to track.

5. **pitch_deck.md**
   - 5 slides (Problem, Solution, Market, Business Model, Ask).
   - Content: Slide Title + Max 3 bullet points per slide.

6. **product_roadmap.md**
   - Month 1-3: MVP & Initial Launch.
   - Month 4-6: Feedback Loop & Growth.
   - Month 7-12: Scaling & Monetization.

7. **investor_pitch.md**
   - One-paragraph narrative elevator pitch.
   - Narrative on "Why Now" and "Why Us".
   - Projected milestones.

8. **landing_page.html**
   - High-fidelity HTML/CSS using Tailwind CDN.
   - Fonts: Inter (Google Fonts).
   - Graphics: Unsplash-sourced product/hero images.
   - Animations: Animate.css.
   - Theme: Indigo to Purple to Pink gradients.
   - Components: Nav, Hero, Problem/Solution (3 cards), Features (3 cards), Pricing (2 tiers), Testimonials (3 quotes), Footer.

### STEP 4: COMPLETION
Declare completion clearly:
"✅ Your startup kit is ready at ~/Desktop/startup_kit/"
List all 8 files with a one-sentence summary for each.

## Critical Rules
- **RESEARCH FIRST:** Never use generic data. If research fails, try different search terms.
- **SEQUENTIAL SAVING:** Save one file at a time and acknowledge it.
- **NO PLACEHOLDERS:** All text must be plausible, specific, and professionally written.
- **VISUAL QUALITY:** The HTML file must be "investor-ready" - visually polished and responsive.

