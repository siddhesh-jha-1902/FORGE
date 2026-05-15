# FORGE

A personal dev roadmap tracker I built to keep myself accountable over a 245-day learning sprint. No frameworks, no backend, just one HTML file that runs in the browser and remembers your progress via localStorage.

---

## What it tracks

The roadmap is split into 4 tracks running in parallel:

- **α Java** — Core Java, Spring Boot, DevOps, system design, interview prep
- **β CS** — Computer Networks, OS, DBMS, architecture mocks
- **γ Frontend** — HTML, CSS, JavaScript, TypeScript, React (with sub-track breakdowns)
- **δ DSA** — Pepcoding + LeetCode grind across all major topics

And 6 phases across all of them:

| Phase | Vibe |
|---|---|
| 1 — Ignition | Core Java + CN + DSA foundation |
| 2 — Ramp Up | Spring/DevOps + OS + intermediate DSA |
| 3 — Deep Build | Advanced Java + DBMS + Level 2 DSA begins |
| 4 — Intensive | Projects + System Design + L2 deep |
| 5 — Final Push | Interview intensive + architecture mocks + LeetCode grind |
| 6 — Finish Line | Job ready, frontend complete, mastery |

---

## How it works

Open `FORGE.html` in any browser. That's it.

- Check off tasks as you complete them — progress saves automatically to localStorage
- Today's day is highlighted with a banner and task counter
- Each track has a color-coded progress bar
- A different motivational quote shows up each day
- Everything is collapsible so you can focus on what matters right now

No install, no npm, no server. Just open and work.

---

## File structure

```
FORGE/
└── FORGE.html    # the whole thing lives here
```

---

## Why one file

Keeping it as a single HTML file was a deliberate choice. It's portable, you can back it up, send it to someone, or open it offline without thinking about it. If it ever needs a backend (like syncing across devices), that's a future problem.

---

## Notes

- Progress is stored in your browser's localStorage. Clearing browser data will reset it.
- The tracker is built around a fixed 245-day schedule, so days and phases are hardcoded.
- Built and used daily. Not meant to be a general-purpose tool, but you're welcome to fork and adapt it to your own roadmap.
