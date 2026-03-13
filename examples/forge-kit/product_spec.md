
# Product Spec: FORGE MVP (Feb 2026)

## Problem Statement
The "vibe coding" explosion has created thousands of builders who create valuable assets (apps, workflows, prompts) but have no centralized, specialized marketplace to sell them with technical validation.

## The Solution
FORGE: The first verified marketplace for AI-generated code, workflows, and logic.

## Core MVP Features (Max 5)
1. **The Sandbox:** Automatic AI verification that checks if the code/workflow actually runs.
2. **Instant Marketplace:** One-click deployment of sales pages for uploaded AI assets.
3. **Multi-Asset Support:** Native support for n8n, LangGraph, Replit, and simple Prompt Packs.
4. **Trust Badges:** "Hermes Verified" badge for assets tested by our internal agents.
5. **Unified Checkout:** Single checkout experience for bundles (e.g., Landing Page + Workflow).

## Tech Stack Recommendation
* **Frontend:** Next.js 15 (App Router) + Tailwind CSS (UI) + Lucide (Icons).
* **Backend:** Vercel AI SDK for internal verification agents.
* **Database:** Supabase (Auth + PostgreSQL) for its fast scaling.
* **Payments:** Stripe Connect (Sub-accounts for sellers).
* **Hosting:** Vercel for instant deployments.

## Unique Differentiator
"Execution Guarantee." If a FORGE-verified asset doesn't run in your environment, instant refund. No risk for the buyer.
