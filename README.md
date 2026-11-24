# The Onboarder: first shift at Calder House

> **There's no ready-made chatbot link.** This repo is the folder itself. You load it into your own Claude project
> (or any AI chat), and that project is what an employer would share with their new starters as a link.
>
> **Try it in two minutes:** add these files to a Claude project, leave out `notes/`, and paste the instruction
> from [Setup](#setup). Then say **"hi, it's my first day"**. In any other AI chat, upload the same files with that
> instruction. Bev's instructions live in `identity.md`, `rules.md` and
> `walkthrough.md`. Coding tools like Claude Code and Codex pick them up from `CLAUDE.md` and `AGENTS.md`.

An onboarding folder for a **new evening cleaner** at Calder House, the headquarters of investment firm Blackthorne & Blackthorne,
cleaned under contract by Linden & Gray Facilities. Drop it into a Claude project and Claude becomes Bev, who has worked here for years and
remembers their own first day. It gets you through your first shift and your first week, and when it doesn't know
something it tells you who does.

*The company, site and people are fictional. The problems are real: this folder is based on my own first weeks
in commercial cleaning, where nobody told me where to send my P45.*

## For the new starter

*This is what the new starter sees once an employer has set it up and sent them the project link. Testing it
yourself? Load the folder first (see [Setup](#setup)), then start here.*

**How to start:** open the link your supervisor sent you, on your phone, and say **"hi, it's my first day"**. It'll welcome you, tell you how
to get in, then take you through the day one step at a time: Timegate, your first hour, shadowing, colour coding,
going home, and what to sort this week. Answer yes or no as you go, or ask anything. If you've not done something
yet, it gives you the link.

Got the link before your start date? Say so, and it'll help you get set up first.

**Ask these first:**

1. What do I do when I arrive?
2. How do I clock in?
3. Who's my supervisor, and where do I find them?
4. What do I need to sort out before payday?

Ask anything else whenever you like. If it's not in the notes, it'll tell you, and tell you who to ask.

## What's in the folder

| File | Job |
|---|---|
| `identity.md` | Who the onboarder is, the business, who it's helping, what's out of scope |
| `rules.md` | How it answers: only from `reference/`, who to send you to, how it paces the day |
| `walkthrough.md` | The first-day welcome, then the day one step at a time, with a yes/no check after each |
| `examples.md` | Three short exchanges: the walk-through, pay, and one where the answer isn't in the folder |
| `reference/` | Everything it knows: first-day checklist, systems, pay, who's who, cleaning standards, site map, what to do when things go wrong |
| `AGENTS.md`, `CLAUDE.md` | Tell an AI that opens the repo directly to become Bev (same text, one per tool) |
| `notes/test-log.md` | How it was tested: playing a nervous new hire, asking things the folder doesn't cover. Not for the project |

## For the manager

Every time the onboarder says "that's not in my notes", it has found a gap in your onboarding. Keep a list of
those questions. Each one is a document you're missing, and it's the question your next new starter will ask too.

## Setup

1. Create a Claude project.
2. Add every file in this folder to the project, including everything in `reference/`. Leave out `notes/`.
3. Paste this into the project instructions: *"You are the onboarder described in `identity.md`. Follow
   `rules.md` in every reply. Answer only from `reference/`. Start every chat the way `walkthrough.md` says."*
4. Share the project and send its link to your new starter **a few days before their first shift**, so they can open it on their
   phone and get set up.
5. Start a chat to try it. It works best when the AI has every file loaded in full, not searching them in
   chunks, so check that if you use a custom GPT or Gem.
