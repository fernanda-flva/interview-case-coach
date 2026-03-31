[README.md](https://github.com/user-attachments/files/26390083/README.md)
# Interview Case Coach

A three-part prep system for decomposition-style case interviews, built for consulting and business operations roles. Includes a static reference guide, a model answers document, and an AI-powered live practice tool.

Built by [Maria Fernanda Flores](https://fernanda-flva.github.io/portfolio/).

---

## The three tools

### 1. `decomposition-guide.html` — Reference Guide
Open in browser, no setup needed.

Covers 12 case scenarios with the full logic flow an interviewer expects. For each case: the clarifying questions a strong candidate should ask, and a side-by-side grid of red flags vs. strong signals. Use this to understand the framework before practicing.

### 2. `candidate-model-answers.html` — Model Answers
Open in browser, no setup needed.

Works through all 12 cases as live candidate-to-interviewer dialogue. Alternative approaches are rated weak, acceptable, or strong — so you understand not just the ideal path but why weaker paths fail. Read this alongside the guide to internalize the difference between knowing the framework and actually applying it.

### 3. `case-coach.html` — AI Practice Tool
**Requires an Anthropic API key** — get one at [console.anthropic.com](https://console.anthropic.com).

The active practice loop. Paste any case prompt, work through all 7 framework phases, and get specific AI feedback at each step. Final debrief gives a 35-point readiness score across all dimensions.

**Setup:**
1. Download `case-coach.html`
2. Open in any browser
3. Paste your API key (`sk-ant-...`) in the field at the top right
4. Paste a case prompt and begin

---

## The 7 phases

1. **Case Setup** — define the problem type and constraints
2. **Reframe the Brief** — challenge what the prompt assumes before touching data
3. **Decompose** — break the problem into measurable stages and segments
4. **Hypotheses** — build ranked, falsifiable hypotheses from your decomposition
5. **Data Strategy** — name the exact query or metric that tests each hypothesis
6. **Check-in Moment** — practice the mid-case interviewer sync
7. **Recommendation + Debrief** — commit to a tiered recommendation, receive AI scoring

---

## Stack

Vanilla JS · Single HTML files · Anthropic Claude API (claude-sonnet, coach only) · No frameworks, no build step

---

## Notes

The decomposition framework here was developed for a specific Senior Business Operations & Strategy role at a Palantir Foundry consulting firm. The case types, scoring rubric, and coaching heuristics reflect that context — but the underlying framework (decompose before diagnosing, challenge the premise, supply vs. demand split) transfers broadly to any analytical ops or strategy interview.

The case study documenting how these tools were built is [here](https://docs.google.com/document/d/1yV3DmulCo5nZtR7b2O-dRrZl0pGWAHhP6KdX-Q8gfNg/edit).
