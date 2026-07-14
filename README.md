# Decision Journal

**Log decisions before you know the outcome — then learn from how your judgment actually performs.**

A small app for logging decisions before you make them — your reasoning, your confidence level, and what you expect to happen — so you can look back later and see how your judgment actually performs over time.

## Why

Most decisions get made and forgotten. This app makes you write down your reasoning *before* you know the outcome, then lets you revisit and grade yourself later. It is a lightweight tool for building better judgment through reflection.

## Status

Early development — project scaffold complete; core features in progress.

## Current State

Scaffold only — Vite + React setup is in place; decision-logging features are not implemented yet.

## How It Works

1. **Log** — Record a decision with reasoning, confidence (%), and expected outcome.
2. **Wait** — Revisit after the real outcome is known.
3. **Reflect** — Compare expectation vs. reality and track judgment over time.

## Stack

- React 19 + Vite 8
- Plain CSS (styling approach TBD)
- Client-side only — localStorage for persistence (no backend yet)
- ESLint for linting

## Prerequisites

- Node.js 18+ (20+ recommended)
- npm

## Getting Started

```bash
git clone <your-repo-url>
cd my-capstone
npm install
npm run dev
```

The app runs at `http://localhost:5173` by default.

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Production build |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## Roadmap

### MVP

- [ ] Log a new decision (title, reasoning, confidence %, expected outcome)
- [ ] View list of past decisions
- [ ] Revisit a decision and record actual outcome

### Later

- [ ] Filter/sort by confidence, date, or outcome accuracy
- [ ] Export or backup decisions

## License

MIT — see [LICENSE](LICENSE).
