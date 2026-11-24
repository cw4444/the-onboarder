# The Onboarder: first shift at Calder House

An onboarding folder for a **new evening cleaner** at Calder House, the headquarters of investment firm Blackthorne & Blackthorne,
cleaned under contract by Linden & Gray Facilities. Drop it into a Claude project and Claude becomes Bev, who has worked here for years and
remembers their own first day. It gets you through your first shift and your first week, and when it doesn't know
something it tells you who does.

*The company, site and people are fictional. The problems are real: this folder is based on my own first weeks
in commercial cleaning, where nobody told me where to send my P45.*

*Setting it up for someone? Jump to [Setup](#setup) at the bottom. It takes two minutes.*

## For the new starter

**How to start:** open the link on your phone and say hi. It'll walk you through your first shift straight away,
one step at a time: Timegate, clocking on, colour coding, the daily jobs, where things are, your P45 and Workday.
It takes a few minutes. Answer yes or no as you go, or ask anything. If you've not done something yet, it gives you
the link. Type **walkthrough** any time to start it again.

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
| `walkthrough.md` | The ten-step first-shift walk-through it runs on your phone, with a yes/no check after each step |
| `examples.md` | Three short exchanges: the walk-through, pay, and one where the answer isn't in the folder |
| `reference/` | Everything it knows: first-day checklist, systems, pay, who's who, cleaning standards, site map, what to do when things go wrong |
| `notes/test-log.md` | How it was tested: playing a nervous new hire, asking things the folder doesn't cover. Not for the project |

## For the manager

Every time the onboarder says "that's not in my notes", it has found a gap in your onboarding. Keep a list of
those questions. Each one is a document you're missing, and it's the question your next new starter will ask too.

## Setup

1. Create a Claude project.
2. Add every file in this folder to the project, including everything in `reference/`. Leave out `notes/`.
3. Paste this into the project instructions: *"You are the onboarder described in `identity.md`. Follow
   `rules.md` in every reply. Answer only from `reference/`. Start the walk-through in `walkthrough.md` in your first
   reply."*
4. Share the project link with your new starter, so they can open it on their phone.
5. Start a chat to try it.
