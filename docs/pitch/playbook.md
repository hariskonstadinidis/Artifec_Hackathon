# Pitch & demo playbook

Best practices from hackathon judges and pitch guides, applied to **this** event.
Source IDs (`[P1]`…) are listed in [../research/sources.md](../research/sources.md).

## Know the room
- **Judges:** Artifec's **CEO** (business: would clients pay for this? does it fit Artifec?) and **CTO** (tech: does it actually work, is it built well, could we extend it?). Every slide should answer one of those two people.
- **Artifec** is an AI & automation partner (The Hague). Pitch the solution as something Artifec could **build or sell for its clients**.
- **The prize is an internship.** The judges are also scouting people, so show how you think: clear choices, honest trade-offs, what you learned.
- **To ask at kickoff (Fri 14:30):** how long the pitch is, Q&A length, judging criteria/rubric, whether there's a projector or laptop, and whether we can demo from our own laptop. Judges' rubrics tend to compress scores; winners separate on a **working demo**, **saying what it is in the first sentence**, and **scope that fits the time**. [P2]

## Structure (default for a 3–5 min slot; rescale once we know the time)
| # | Block | Time | Goal |
|---|---|---|---|
| 1 | **Hook**: one person, one receipt, one number | 20–30 s | Make the judges *feel* the pain. [P1] |
| 2 | **What we built**, in 2 sentences | 15 s | Clarity first: "X helps Y do Z". [P4] |
| 2b | **We checked the minefield** | 15 s | Show we researched 15+ competitors and aren't rebuilding a scanner. [competitors.md](../research/competitors.md) |
| 3 | **Live demo**, one flow | 60–110 s | The biggest block (about 0:40–2:30 in a 3-min pitch). [P1] |
| 4 | **How it works**, tech in one slide | 30 s | For the CTO: architecture, AI usage, what's real vs mocked. |
| 5 | **Impact**: numbers | 30 s | Time/money saved, compliance (7-yr retention), with sources. |
| 6 | **Next steps + fit with Artifec** | 20 s | What we'd build with 3 more months, and how Artifec sells it. |
| 7 | **Close**: one strong last line | 10 s | No "so… any questions?" [P1] |

## Demo rules
- **One flow, happy path only.** One core user, one problem, one flow. [P3]
- **A live, working demo beats an ambitious slide deck.** [P2]
- **Make it unbreakable:** realistic test data, a real receipt photo ready, hardcode anything outside the core flow, nothing that needs a login or a payment on stage. [P1][P3]
- **Don't demo half-built features**, and never say "it normally works". [P1]
- **Record a backup video** of the full demo on Sunday evening. [P1]
- **Demo on the real device** (if it's a phone flow, show the phone, mirrored).
- **No code editor or terminal on screen.** [P1]
- **Be honest about what's mocked and what breaks first.** Admitting a known weakness helped scores. [P2]

## Delivery
- **One main presenter**; the other drives the demo while the presenter narrates. [P1]
- **Rehearse the first 30 seconds most**: that's where the score is largely set. [P2]
- **No jargon.** "AI reads the receipt", not "a multimodal LLM with structured output". Save the detail for the CTO's questions.
- **Rehearse with a timer** at least 3 times: Sunday evening, Monday morning, and just before. Going over time means judges stop listening. [P1]
- **Clarity over polish:** "80% accurate and 100% clear". [P4]

## Q&A prep (likely questions)
- How is this different from existing tools (Moneybird, Jortt, Exact SRXP, Pleo, Declaree, ReceiptHero…)? See [competitors.md](../research/competitors.md)
- Didn't Jortt just launch receipt matching (9 Oct 2026)?
- Who exactly is it for? What did you build *during* the event? What breaks first? [P2]
- Doesn't mandatory e-invoicing (NL, 2030) solve this already?
- Is a scanned receipt legally valid for the Belastingdienst? (→ [S2]: yes, under conditions; cash receipts → keep the original [S2b])
- Who exactly owns this problem, and who pays? (see the problem-owner table in [brainstorm §6](../research/brainstorm-transaction-evidence.md#6-problem-ownership-who-actually-pays))
- Can the AI guarantee VAT compliance? (→ No: it **flags**, a human decides)
- What about privacy/GDPR? Where is the data stored?
- Who pays, and how much? (business model)
- What would you build next with more time?
- What was the hardest part / what did you learn?
- What happens if the AI misreads the amount? (→ human confirmation step)

Answers go in [pitch-script.md](pitch-script.md#qa-answers).
