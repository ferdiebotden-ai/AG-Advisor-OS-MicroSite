# AgAdvisor OS Pitch Microsite

Single-page HTML microsite showcasing AgAdvisor OS — an AI-native operating system for Canadian agriculture advisors. Built for a pitch to Joe Dales (RHA Ventures).

## Context

- **Handoff:** `CLAUDE_CODE_HANDOFF.md` - full context, requirements, demo specs
- **Session state:** `SESSION_STATUS.md` - current phase, next task, blockers
- **Main file:** `JoeDales-AgAdvisorOS-Microsite-Feb2026.html`

Always check SESSION_STATUS.md before starting. Update it when done.

## Stack

Single HTML file | Inline CSS | Inline JavaScript | Google Fonts (Inter)

No build step. No npm. No package.json. Self-contained.

## Commands

```bash
# View the site
open JoeDales-AgAdvisorOS-Microsite-Feb2026.html

# Or run a local server (for live reload tools)
python3 -m http.server 8000
```

## Design System

- **Theme:** Dark mode
- **Primary BG:** #0a0d14
- **Accent:** #22c55e (green)
- **Secondary:** #3b82f6 (blue), #f59e0b (amber), #8b5cf6 (purple)
- **Font:** Inter (300-800 weights)
- **Responsive:** Breakpoints at 1024px and 768px

## Key Sections

1. Navigation (fixed, blur backdrop)
2. Hero (stats, badge, gradient text)
3. Vision (3 cards)
4. Founder (credentials, highlights)
5. **Modules/Demos** ← Main enhancement area
6. Technology Stack
7. Market Opportunity
8. CTA + Footer

## Current Task

**Improve the workflow demos** (lines ~1326-1551 in HTML):
- Current: Basic div boxes with sequential highlighting
- Goal: Beautiful animated flow diagrams (Linear/Vercel/Stripe quality)
- Options: SVG animations, canvas, Lottie, CSS animations

## Patterns

**Self-contained.** All CSS in `<style>`, all JS in `<script>`.

**Mobile-first.** Test on 375px width.

**No external dependencies** except Google Fonts.

**Demo-first mindset.** The demos are the "wow factor" — they prove technical capability.

## Skills Reference

For this project:
- `frontend-design` - For visual design, animations, CSS
- `playwright-testing` - For cross-browser testing if needed
- `security-compliance` - Minimal (static site, no user input)

NOT relevant for this project:
- nextjs-patterns, supabase-patterns, ai-native-development, typescript-strict

## Project-Specific Notes

- **Target audience:** Joe Dales (mentor, RHA Ventures, 40+ years in ag)
- **Goal:** Demonstrate vision + technical capability
- **NOT a cold pitch** — warm relationship
- **Success:** Joe understands vision, impressed by demos, wants deeper conversation
