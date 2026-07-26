# Product Requirements Document (PRD)
## PromptArena — AI Model Comparison & Evaluation Platform

**Version:** 1.0
**Date:** Day 51, 60-Day Claude AI Mastery Challenge
**Owner:** Komal
**Status:** Approved — Source of Truth for Capstone Build

---

## 1. Problem Statement

Developers, students, and researchers regularly need to pick the "right" LLM for a task — but there's no fast, visual way to run the same prompt across multiple models and compare quality, tone, and accuracy side by side. People either:
- Manually copy-paste prompts into 3–4 different chat tabs (slow, no history), or
- Trust marketing benchmarks that don't reflect their actual use case.

**PromptArena solves this** by letting a user submit one prompt, run it simultaneously across multiple LLM APIs, view responses side-by-side, vote on the best one, and keep a searchable history of past comparisons.

## 2. Target Users

| User Type | Need |
|---|---|
| CS/AI students | Learn practical differences between LLMs for coursework/projects |
| Developers | Decide which model API to integrate into their own app |
| Content creators | Pick the best-written response for blogs, captions, emails |
| Researchers/hobbyists | Casual, structured LLM benchmarking |

## 3. Goals (v1.0)

1. Let a signed-in user submit a prompt and get responses from at least 2–3 LLM providers in parallel.
2. Show responses side-by-side with response time and (where available) token usage.
3. Allow the user to vote for the "winner" response per comparison.
4. Save every comparison to the user's history, viewable and searchable later.
5. Allow a comparison to be shared via a public read-only link.
6. Deploy a working, publicly accessible v1.0 within the 10-day capstone window.

## 4. Non-Goals (Out of Scope for v1.0)

- Fine-tuning or training any model.
- Supporting more than 3 LLM providers at launch.
- Team/organization accounts or billing.
- Mobile native app (web-responsive only).
- Streaming token-by-token output (full response only, for v1.0 simplicity).

## 5. User Stories

- **As a visitor**, I can see a demo comparison without logging in, so I understand the value before signing up.
- **As a user**, I can sign up / log in so my comparison history is saved to my account.
- **As a user**, I can type a prompt once and see it run across multiple models at the same time.
- **As a user**, I can see each model's response, response time, and rough cost/token estimate.
- **As a user**, I can vote for the response I think is best, per comparison.
- **As a user**, I can view my past comparisons in a history/dashboard page.
- **As a user**, I can generate a shareable public link for any comparison.
- **As a user**, I get a clear error message if a model API fails or times out, without the whole page breaking.

## 6. Functional Requirements

| ID | Requirement |
|---|---|
| FR1 | User authentication (sign up, log in, log out) |
| FR2 | Prompt submission form with model-selection checkboxes |
| FR3 | Parallel API calls to selected LLM providers |
| FR4 | Side-by-side response display with metadata (time, tokens) |
| FR5 | Voting mechanism per comparison |
| FR6 | Persistent history per user, stored in database |
| FR7 | Public shareable link per saved comparison |
| FR8 | Graceful error handling per model (partial failure ≠ full failure) |

## 7. Non-Functional Requirements

- **Performance:** Comparison should return all model responses within a reasonable timeout (~30s), with partial results shown as they arrive if possible.
- **Cost:** Must run on free-tier infrastructure (student budget) — free DB, free hosting.
- **Security:** API keys for LLM providers must live server-side only, never exposed to the browser.
- **Usability:** Clean, distraction-free UI; must work well on both desktop and mobile browser.
- **Reliability:** One model failing must not crash the whole comparison.

## 8. Success Metrics (for capstone demo/portfolio purposes)

- Working end-to-end demo: prompt in → 2–3 model responses out → vote → saved to history.
- At least 5 sample comparisons pre-loaded or generated for demo purposes.
- Deployed live URL + GitHub repo with clean README.
- Positive reception on LinkedIn post / portfolio review.

## 9. Assumptions & Constraints

- Free-tier API access/limits for the LLM providers used will be sufficient for demo-scale usage.
- Hosting will use free tiers (e.g., Vercel/Render + a free-tier database).
- 10-day timeline (Days 51–60) must be respected — scope is intentionally kept lean for v1.0.

## 10. v1.0 Feature Checklist (MVP)

- [x] Auth (sign up/login)
- [x] Prompt submission + model selection
- [x] Parallel multi-model API calls
- [x] Side-by-side comparison view
- [x] Voting
- [x] History dashboard
- [x] Public share link
- [ ] (Future / v2) Streaming responses
- [ ] (Future / v2) Team accounts
- [ ] (Future / v2) Analytics dashboard on model performance over time
