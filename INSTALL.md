# Installation Guide

How to set up the **DBT/CBT Skills Companion Kit** in the AI tool of your
choice. The kit is just text files — `AGENT.md` (the companion's persona and
rules) plus the `skills/` folder (the DBT/CBT coaching library). Any AI tool
that can follow a long set of instructions can run it.

> **Safety note:** This kit is educational and supportive — not therapy, not a
> diagnosis, not a crisis service. If you feel unsafe or have thoughts of
> harming yourself, call or text **988** (US, 24/7), text **741741**, or call
> **911** for imminent danger.

## Quick orientation

1. Pick an AI tool below and install it if you haven't already.
2. Follow that section's steps to give the tool the kit's files.
3. The companion starts with a gentle **intake** (your name, faith posture,
   therapist/program status, skills you're learning, how direct it may be),
   then adapts from there.
4. Your private profile and logs stay in *your own* `companion-logs/` — never
   shared, never part of the public kit.

---

## Muse AI (recommended)

Muse is Meta's personal AI agent. Because it has a full computer of its own,
it can fetch the kit straight from the public repository — nothing to
download, nothing to upload.

**Get Muse:** use it on the web at [muse.ai](https://muse.ai), or download the
iOS app from the App Store or the Android app from Google Play. Learn more at
[muse.ai](https://muse.ai).

**Set up the companion:**

1. In the Muse app, tap **+** and choose **New side chat**. A side chat keeps
   your companion in its own private conversation, separate from everything
   else.
2. Send this message in the side chat:

   > Install this companion kit and start intake with me:
   > https://github.com/dewers99/dbt-cbt-companion-kit

3. Muse reads the kit from that link and begins intake. Just answer its
   questions one at a time.

If you'd rather share the files directly, download the ZIP from the repo's
**Code → Download ZIP** button and attach `AGENT.md` plus the `skills/` folder
to the side chat instead.

---

## ChatGPT

**Get ChatGPT:** download the desktop app from
[chatgpt.com/download](https://chatgpt.com/download/) (Mac and Windows), or
get the mobile app from the App Store or Google Play — search for the app
**published by OpenAI** so you get the official one. The web version works at
chatgpt.com. Learn more: [OpenAI's help center](https://help.openai.com).

**Set up the companion:**

1. Create a new **Project** (in the sidebar) and name it something like
   "DBT Companion".
2. In the project's settings, add the contents of `AGENT.md` as the project
   instructions.
3. Upload each `skills/*/SKILL.md` file (and the `templates/` folder) to the
   project's files.
4. Open a new chat in that project and say: *"Start intake with me."*

If your plan doesn't support Projects, start a regular chat, attach
`AGENT.md` and the skill files, and ask it to start intake — but know the
companion won't remember your profile between chats without a Project.

---

## Claude

**Get Claude:** download the desktop app from
[claude.com/download](https://claude.com/download) (Mac, Windows, and Linux),
or get the mobile app from the App Store or Google Play (publisher: Anthropic).
The web version works at claude.ai. Learn more:
[Anthropic's support center](https://support.anthropic.com).

**Set up the companion:**

1. Create a new **Project** and name it "DBT Companion".
2. Paste the contents of `AGENT.md` as the project's custom instructions.
3. Upload the five `skills/*/SKILL.md` files to the project's knowledge.
4. Start a new chat in the project and say: *"Start intake with me."*

---

## Microsoft Copilot

**Get Copilot:** download it from
[Microsoft's Copilot download page](https://www.microsoft.com/en-us/microsoft-365-copilot/download-copilot-app)
(Windows, Mac, iOS, Android), or use it in your browser. Learn more:
[Microsoft Copilot help](https://support.microsoft.com/en-us/microsoft-copilot).

**Set up the companion:**

1. Start a new conversation.
2. Attach `AGENT.md` and the `skills/` files to the chat.
3. Send: *"Install this companion kit and start intake with me."*

Copilot chats don't keep a standing persona the way Projects do, so repeat
the attachment step at the start of each new companion conversation.

---

## Google Gemini

**Get Gemini:** use the app on iOS or Android, the desktop apps
([gemini.google/mac](https://gemini.google/mac) for Mac,
[gemini.google/desktop](https://gemini.google/desktop) for Windows), or the
web at gemini.google. Learn more:
[Google's Gemini announcement and help](https://blog.google/innovation-and-ai/products/gemini-app/gemini-app-now-on-mac-os/).

**Set up the companion:**

1. Create a new **Gem** and name it "DBT Companion".
2. Paste the contents of `AGENT.md` as the Gem's instructions.
3. Upload the five `skills/*/SKILL.md` files as the Gem's knowledge.
4. Open the Gem and say: *"Start intake with me."*

---

## Cursor and other coding agents

Cursor is an AI code editor, so the kit lives alongside your project rather
than in a chat app — useful if you're a developer customizing the companion.

**Get Cursor:** download it from
[cursor.com/downloads](https://cursor.com/en/downloads) (Mac, Windows,
Linux). Learn more: [Cursor's docs](https://cursor.com/docs).

**Set up the companion:**

1. Copy `AGENT.md` and the `skills/` folder into your project.
2. Add them to your project's rules (e.g. `.muse/rules/`) so the agent loads
   the persona and coaching library.
3. Ask it to start intake.

---

## Staying up to date

The kit is versioned — a `VERSION` file at the repo root holds the current
version. During intake, your companion records which version was installed.
It doesn't ask about updates at intake — the first check happens on its own
one week after install, and only if something is actually new does it mention
it and ask your preferences.

- **Muse:** the companion can check in the background — first check one week
  after install, then weekly or monthly, your choice. If an update is found,
  it mentions it at the start of a calm conversation (never during a hard
  moment), gives a one-line plain-language summary of what changed, and offers
  the full details if you want them.
- **Other AI tools:** the companion checks opportunistically when a calm
  conversation starts, at most weekly — same gentle wording, same one-decision-
  at-a-time approach.
- **Your call, always:** the first time an update is found, it asks whether to
  apply future updates automatically and whether to keep checking (weekly,
  monthly, or off). Saying no ends the subject until you bring it up again.
- **URL-installed kits** that re-fetch the repo each session are already
  current — there's nothing to update.

You can change your update preferences any time by just telling your
companion ("check monthly instead," "stop checking for updates").

## Share feedback

About a month after you start, your companion may share a short, anonymous
feedback form — a few questions that help improve the kit for everyone. No
name or email is collected, and you're always free to skip it. You can also
open it any time here: https://forms.gle/Ufgd5wXM8oFuJrP88

(The form isn't monitored, so it isn't a place to ask for help — if you need
support right now, contact your therapist or call/text 988.)

---

## Any other AI tool

If your tool can read files or long instructions, the kit will work:

1. Give the tool the full text of `AGENT.md` as its persona or system
   instructions.
2. Add each `skills/*/SKILL.md` as an additional instruction file or skill.
3. Ask it to start intake.

If you hit a snag, the tool's own help docs are the best next stop — these
instructions were written for the general features of each platform, which
change over time.
