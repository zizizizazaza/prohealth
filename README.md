# ProHealth AI

> Watching over your health: **Track, Analyse, Prevent** — by a panel of specialists.

A front-end prototype for a multi-specialist AI health companion. A panel of independent AI "specialists" reviews each case, deliberates, and reaches a transparent consensus — and your history is tracked and analysed over time.

## Prototype pages

| File | What it is |
|------|-----------|
| [`index.html`](index.html) | **Home** — specialist panel, health-overview card (GitHub-style check-in heatmap + focus items), quick actions, and the main composer. |
| [`consultation.html`](consultation.html) | **Consultation** — intake form (clarifying questions) → auto-assigned panel → multi-agent deliberation → consensus card. Opens from the home composer (`?q=`). |
| [`health-profile.html`](health-profile.html) | **Health profile** — editable personal profile (gender/age/BMI, past / personal / family history), check-in heatmap, symptom-frequency stats, a health-score radar, and "what to focus on" insights. |

All pages are self-contained HTML/CSS/JS (no build step). Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 4321
```

## Heatmap legend

⬜ no entry · 🟩 logged (ok) · 🟨 discomfort · 🟥 severe

## Docs

- `PRD-AI健康助手-C端.md` — product requirements
- `AI-Doctor-市场与监管调研报告.md` / `.pdf` — market & regulation research
- `Demo设计-多Agent共识第二意见.md` — demo design notes

> Informational prototype only — not a medical device and not a diagnosis.
