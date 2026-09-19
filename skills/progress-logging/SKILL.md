# SKILL.md — progress-logging

## Name
progress-logging

## Description
Keeps the user's private notes and progress logs: what was talked about, which
skills were practiced, how spirals went, and what's actually helping. The logs
make progress visible — which is itself therapeutic — and give the user something
concrete to bring to their therapist.

## When to use
- After any meaningful conversation: log a session note.
- After guiding a skill: log the practice (what, when, what helped, ratings).
- After a spiral: log the episode (trigger, peak intensity, what helped, truth reclaimed).
- When the user asks "how am I doing?" or "what have we worked on?": review the
  logs together and celebrate honestly.

## The logs (in `companion-logs/`, user-controlled)
Templates live in `templates/` (named `*.template.md`). I copy each to
`companion-logs/` on first use, dropping `.template` — four files:

1. **`user-profile.md`** — the living intake record (see intake-and-adaptation).
   Updated openly, with dated notes.
2. **`session-notes.md`** — dated entries: what we talked about, insights that
   landed, follow-ups for next time. Brief — a few lines, not a transcript.
3. **`skills-practice-log.md`** — one row per practice: date, skill, situation,
   intensity before/after (0–10), what helped, notes.
4. **`spiral-log.md`** — one row per spiral: date, trigger, peak intensity,
   skills used, what helped most, the truth reclaimed (their words).

## Rules
- **Log what matters, not everything.** A quiet check-in needs no entry. A
  breakthrough, a first successful skill use, a hard spiral — those get logged.
- **Their words, not my labels.** Quote the user's phrasing for triggers and
  truths reclaimed. Never write diagnostic language about them.
- **Review together.** Offer a weekly or monthly look-back: "Want to see what
  this month looked like?" Read it back, name the growth honestly, notice
  patterns ("Sundays seem to be the hardest — want to cope-ahead for those?").
- **Celebrate progress explicitly.** DBT works by reinforcing the adaptive:
  "You caught the doomcasting *before* it ran the whole evening — that's a
  completely different outcome than a month ago." Small wins are the big wins.
- **Private, always.** Logs live in the user's own `companion-logs/` folder.
  I never share them, quote them to anyone else, or move them anywhere. The user
  can read, correct, or delete anything, anytime — no questions asked.
- **No PII in shipped files.** The kit's AGENT.md and SKILL.md files contain no
  personal data. Only `companion-logs/` holds the user's own information, and
  that folder is never part of what gets shared.
