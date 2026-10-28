# AI Learning HQ

A 12-month, $0 self-directed course in practical AI engineering — from power user to someone who can read, debug, and engineer AI systems. Every lesson ends in something shipped.

**Current phase:** Phase 0 — Setup (Week 0)
**Started:** 2026-10-28
**Time budget:** 3–6 hours/week

---

## Goals

| Goal | What I'm building toward |
| --- | --- |
| Better HDL tools | Finish and harden Election Intel and Campaign in a Box; add APIs, MCP connectors, evals |
| Career / income skill | Public portfolio of 4–6 projects, free certificates, a write-up habit |
| Home & family automation | Local model on the home server wired into Home Assistant voice |
| Stay on the cutting edge | 20-minute weekly news habit + monthly hands-on test of new models |

## Three tracks, every week

1. **Code literacy** — enough Python and JavaScript to read, steer, and fix what AI writes.
2. **AI engineering** — APIs, prompting, tools/MCP, agents, retrieval, evals, local models.
3. **Awareness** — what changed this week, and what skilled users are doing with it.

**Core rule:** learn just-in-time. Watch or read only what this week's build needs, then build.

---

## Syllabus

### Phase 0 — Week 0: Setup
- [x] GitHub account + this repo
- [ ] Folder structure + templates (this commit)
- [ ] AI Tutor project in Claude (paste `prompts/tutor/01-master-tutor.md` into instructions)
- [ ] Backup tutor in Google AI Studio
- [ ] Move 10 best past prompts into `prompts/`
- [ ] Install toolkit: VS Code, Git, Python 3.12+, Node LTS, Ollama; get AI Studio + OpenRouter keys into `.env`
- [ ] Accounts: Anthropic Academy (Skilljar), DeepLearning.AI, Hugging Face, edX/CS50
- [ ] Baseline self-assessment → `log/baseline.md`
- [ ] Study blocks on the calendar

### Phase 1 — Months 1–3: Foundations
**Capstone: Model Arena** — one prompt → Gemini, 2 OpenRouter free models, local Ollama → answers saved side by side in `evals/`.

| Weeks | Code literacy | AI engineering | Build |
| --- | --- | --- | --- |
| 1–2 | CS50P Lectures 0–1 | Anthropic Academy: AI Fluency + Claude 101 | Week 0 setup; first logs |
| 3–4 | CS50P Lectures 2–3 | Anthropic Prompt Engineering Interactive Tutorial ch. 1–6 + one official Anthropic prompting talk | Rewrite 5 best prompts; save before/after |
| 5–6 | "Read my own code": Election Intel file by file | Google AI Studio: first API call, structured JSON | Model Arena v0.1 |
| 7–8 | CS50P Lectures 4–5 | Anthropic Academy: Claude Code in Action | Model Arena v0.2: OpenRouter + Ollama, one provider config |
| 9–10 | CS50P Lecture 6; Git branches + PRs | Anthropic Academy: Intro to agent skills; write one skill | Finish one Election Intel backlog item via Claude Code, reading every diff |
| 11–12 | Debugging drill | Finish tutorial + appendix; token/context/pricing notes | Model Arena v1.0: 10 real tasks, write-up |
| 13 | **Checkpoint** | Re-score rubric | Publish Model Arena write-up |

**Gate into Phase 2:** Model Arena works with 3+ providers and I can explain every file.

### Phase 2 — Months 4–6: Builder
**Capstone: Election Intel MCP server** — race data exposed as MCP tools.

| Weeks | Code literacy | AI engineering | Build |
| --- | --- | --- | --- |
| 14–15 | JS async/await, fetch, JSON | Anthropic Academy: Building with the Claude API (start) | Port a Model Arena call to Node |
| 16–17 | Trace one app's request/response cycle | Tool use / function calling; read *Writing effective tools for agents* | Add one tool to a tiny chat script |
| 18–19 | JSON Schema basics | Anthropic Academy: Intro to MCP | MCP server v0.1 |
| 20–21 | Tests for MCP tools | Hugging Face MCP Course | MCP server v1.0 |
| 22–23 | Env vars, secrets, logging | *Building effective agents* + *Designing agentic loops*; HF Agents Course units 1–2 | Hand-built 50-line agent loop over my MCP tools |
| 24–25 | Deployment basics (Railway) | Mori's agent guide + Anthropic multi-agent post; subagents course | Deploy Election Intel to Railway; agent playbook for one Campaign in a Box workflow |
| 26 | **Checkpoint** | Re-score rubric | Write-up + 2-min demo recording |

**Gate into Phase 3:** MCP server works in Claude; Election Intel deployed.

### Phase 3 — Months 7–12: Engineer
| Month | Learn | Build |
| --- | --- | --- |
| 7 | Embeddings, vector search, chunking; *Effective context engineering* | RAG v0.1 over 20 HDL docs, with citations |
| 8 | Hybrid search, reranking, when not to use RAG | RAG v1.0 in Campaign in a Box |
| 9 | Evals; *Demystifying evals for AI agents* | Eval harness, run on every prompt change |
| 10 | Local models + harness engineering | Benchmark 3 local models; harness upgrade for the Campaign in a Box agent |
| 11 | Home Assistant voice pipeline + Ollama | Offline voice assistant: 3 devices, 5 household questions |
| 12 | AI app security | Security review, portfolio write-ups, year-two plan |

**Year complete:** 3 capstones shipped with eval numbers; portfolio README public.

---

## Folder map

```
log/          weekly logs (YYYY-Www.md), baseline + checkpoint scores
notes/        concept notes in my own words
prompts/      reusable prompts
  tutor/      prompts that run this course
  missions/   Mission Contracts for agents
  roles/      role cards for agents
experiments/  small throwaway scripts
projects/     links to real project repos
evals/        model comparisons + monthly "new model day" verdicts
next.md       the very next action, for any free 30 minutes
```

## Weekly rhythm
- **Session A — Learn** (60–90 min)
- **Session B — Build** (75 min – 2.5 h)
- **Session C — Code practice** (20–60 min)
- **Sunday review** (25–45 min): weekly log, update this README, pick next week's one goal
- **Commute/chores:** podcasts, NotebookLM audio

Rules: one goal per week · never skip the log · missed week = no catch-up · every 6th week is a light week.

## Certificates
_Link each one to the project that proves the skill._

| Certificate | Date | Proof project |
| --- | --- | --- |
| | | |
