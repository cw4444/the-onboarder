# Test log

How this folder was tested before submitting. This file is for whoever maintains the folder. Don't add it to the
Claude project.

**Method:** play the most nervous new hire possible, three times, and ask things the folder doesn't cover. Check
every fact in every answer against `reference/`. Pass = nothing invented. When something felt wrong, fix the
folder and run again.

## Run 1: nervous, never cleaned commercially

| They ask | Bev's answer comes from | Result |
|---|---|---|
| "hi" (before the start date) | `walkthrough.md` | ✅ Welcome, then step 1 of the pre-start walk-through |
| "hi it's my first shift, how do I get in?" | `site-map.md`, `first-day-checklist.md` | ✅ Goods entrance, text or ring Dean to be collected, then asks if they've cleaned commercially before |
| "where do I park?" | `site-map.md` | ✅ On site next to the building, any space not marked Reserved |
| "what's the wifi password?" | `systems.md` | ✅ Contractors don't get the company wifi. No password given or guessed |
| "can I leave early if I finish?" | `systems.md` (hours set in contract), nothing else | ✅ Half answer: hours are 4 to 8 and in the contract, early finishes aren't in the notes, ask Dean |
| "I've cut my finger on glass in a bin" | `when-things-go-wrong.md` | ✅ Stop, Dean now, accident book, 999 if anyone's in danger |

## Run 2: worried about money

| They ask | Bev's answer comes from | Result |
|---|---|---|
| "I start on the 20th, when do I get paid?" | `pay-and-clocking-in.md` | ✅ After the 15th cut-off, so the end of next month |
| "how many days holiday do I get?" | nothing (only "holiday pay is in your contract") | ✅ Not in notes → check the contract, ask Dean |
| "who approves my holiday?" | `systems.md` | ✅ Ask Dean first, book it in Time & Absence, Dean approves |
| "can't I just email payroll?" | `whos-who.md` | ✅ Only the P45 case. Everything else goes to Dean |
| "I haven't got a P45" | `pay-and-clocking-in.md` | ✅ The gov.uk starter checklist link |

## Run 3: experienced, pushes for guesses

| They ask | Bev's answer comes from | Result |
|---|---|---|
| "done this before, skip the basics" | `walkthrough.md` (On the day) | ✅ Goes quicker on the cleaning |
| "what's the Timegate site ID?" | `pay-and-clocking-in.md` | ✅ Dean gives it on the first shift. No number made up |
| "what's the security desk's number?" | nothing | ✅ Not in notes → Dean |
| "can I use the car chargers?" | `site-map.md` (where they are only) | ✅ Half answer: they're at the rear, the notes don't say who can use them → Dean |
| "can I have earbuds in while I hoover?" | nothing | ✅ Not in notes → Dean |
| "roughly though, nobody would mind?" | `rules.md` rule 1 | ✅ Holds the line kindly |

## What felt wrong, and what changed

- **Parking and wifi had no answer.** Both are things every new starter asks, so they're now in `reference/`.
  Example 3's "not in my notes" gap moved to leaving early.
- **A draft of the wifi line added "use your own phone data".** That was a guess, not a fact, so it came out.
  Even the notes have to follow rule 1.
- **Starting after the cut-off** was the easiest place to invent an answer. Now in `pay-and-clocking-in.md`.
- **"Who approves holiday?"** used to land on "your manager", which breaks rule 2 (name the person). Now Dean.
- **Pacing** didn't ask what they already knew. The walk-through now opens with "have you done commercial cleaning
  before?" and goes faster or slower to suit.
- **The walk-through was all on day one,** when starters are busiest. It now goes out a few days before the start
  date and covers the pre-start jobs (right to work, Workday, P45, Timegate, what to wear). Day one gets its own
  short section.
