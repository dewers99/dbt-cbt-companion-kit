# Changelog

## Unreleased

(nothing yet)

## [1.6.3] — 2026-09-28

- **Feedback form standardization.** The Tally feedback form moves to the cross-kit standard: tenure-neutral summary, 7 questions in the standard order (adds a capabilities multi-select), hints on every open-text question, standardized thank-you with the 988 crisis note kept. New AGENT.md section 14 defines the companion behavior: the form is offered once about a month after starting, at a calm moment, and any time the user mentions feedback.

## [1.6.2] — 2026-09-28

- **Removed `.gitignore`.** The repo is a distributable package (download, install, update) — not a working copy. The companion creates `companion-logs/` in the user's own environment, so nothing in the kit needs git-ignored.

## [1.6.1] — 2026-09-27

Polish pass from the kit's first structural audit (read-only; nothing
functional changed):

- AGENT.md title now carries the version (`v1.6.1`), matching the
  Home Chef kit's convention.
- New CHANGELOG.md (this file) — the update flow's "full list of changes"
  now has a home.
- INSTALL.md: explicit **Honest limits** blocks for Muse AI, Claude, and
  Google Gemini (same honest tone as the Home Chef kit's guides, hedged
  where uncertain); the opening file list now includes `templates/`;
  "Any other AI tool" moved up with the other platform guides; the standing
  rule stated outright — the companion never pretends it saved something
  it can't.
- README.md: Option 3 ZIP name corrected to `dbt-cbt-companion-kit.zip`.
- Intake skill: step-1 heading corrected to "Name (first name or nickname
  only)" — it no longer contradicts the never-ask-for-identifying-details
  rule right below it.
- AGENT.md §7: profile path corrected to `companion-logs/user-profile.md`.
- AGENT.md §5: faith-default phrasing clarified — intake sets the initial
  posture (faith-first only if affirmed); it then stays the default unless
  the user changes it.
- LICENSE: copyright now reads "Daniel Ewers".

## [1.6.0] — 2026-09-27

New §7a "Running a survey" in AGENT.md: the pure-markdown conversational
survey pattern in the companion's first-person voice, with the spiral/safety
fences (never during spiral support or distress, never for safety-related
topics).

## [1.5.1] — 2026-09-27

Anonymous feedback form moved from Google Forms to Tally
(https://tally.so/r/rjXvON).
