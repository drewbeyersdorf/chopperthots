# WORKBOOK — Daily chopperthots pack

This is the operational playbook. The machine stages. The human punches. Nothing posts itself until an X OAuth credential exists in n8n and is deliberately wired.

## Cadence

| Time (PT) | What |
| --- | --- |
| 07:15 | Grok Automation `chopperthots daily pack` runs. Stages the full pack (heart, tip, reasoning, 3+ X posts, Short, optional LinkedIn, blog draft, compose URLs, visual assignment). Notification arrives. |
| Morning | Human reviews the pack. Punches the compose links (or later n8n tweet:create). |
| +24 h | Score: smart reply? Anyone call it AI? Did you mean it? Log it. |

## What the automation produces

1. **Heart of the creativity** — why this tip matters today.
2. **Tip / Headline** — the atom.
3. **Reasoning** — only the strongest lenses (history · biomimicry · ontology · business · advice · lived). Motorcycle / biomimicry / religious analogy may earn a seat when it teaches AI + the world today.
4. **3 X posts** (under 220, Drew table talk). Optional more if strong.
5. **One Short (16s)** — strongest image, pure B&W preferred, VO, hold/cut.
6. **LinkedIn** — only if business earned the seat.
7. **Blog angle** — new notes/ draft on the same skill, different day.
8. **Compose URLs** — ready for the human.

Lived is fail-closed. Visual banks are locked (Daytona / Old Santa Monica / ENIAC-CS). No generation. No secrets in the repo.

## Human punch checklist

- [ ] Open the morning notification / pack.
- [ ] Read the heart. Does it still feel true?
- [ ] Check the three posts for voice (deadpan, sport, fog). Delete any that sound like LinkedIn or a brand partnership.
- [ ] Confirm visual plate is from an allowed bank and credited.
- [ ] Click the three compose URLs (or paste into X).
- [ ] Film or schedule the Short when ready.
- [ ] Optional: paste the blog draft into `notes/` later.
- [ ] After 24 h: score and log.

## Scoring (after 24 h)

- Smart reply received?
- Did anyone call it AI?
- Did you mean it when you posted?

Keep the score somewhere durable (sheet, issue note, or personal log). Do not invent metrics.

## Later: true auto-post

When an X OAuth credential is added to n8n and named clearly:

1. Wire a small n8n flow that receives the staged pack (email parse or webhook or sheet row).
2. Use tweet:create (or equivalent) only on the posts the human has already approved, or add an explicit “approve” step.
3. Keep the Automation as the stager. Keep the human (or an explicit approve gate) as the final punch until the magazine is ready for lights-out.

Until that credential exists, compose links are the send path. Do not paste keys into this repo.

## Voice law (from MAINTAIN.md)

Deadpan. Sport. Fog. AI is a spotter.
If it sounds like LinkedIn, delete it.
If it sounds like a brand partnership with a skate mag, delete it.

## Art law (from ART.md)

Only these banks:
1. Daytona Beach, Florida — real biker / Bike Week / beach-race photographs.
2. Old Santa Monica beach — real archival beach and surf photographs. Not Santa Cruz. Not Pacifica.
3. Coveted computer-science archive — ENIAC, automata, labs. Public domain or clearly licensed.

Edit only: crop, grade, dust. Prefer black and white. Credit or no picture.

## File law

- Tip files stay short.
- Shorts stay under 80 words of VO.
- Issues track what actually shipped.
- This workbook is the runbook, not a course platform.

## You

Drew films. Drew composes (until the gate is intentionally opened).
The repo holds the script and the tip.
The Automation stages every morning at 07:15 PT.
The human still punches.
