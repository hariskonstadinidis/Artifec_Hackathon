# MVP: scope & decisions

## What a hackathon MVP is
"Minimum viable **proof**", not a product: evidence that the idea works. [P3]

Principles (from [P2][P3]):
1. **One sentence, one core feature.** Everything else is nice-to-have.
2. **Design the demo flow first**, then build only what that flow touches.
3. **Divide your plan by 4.** Teams typically finish about a quarter of what they plan.
4. **Happy path only.** Skip edge cases unless the demo hits them.
5. **Fake the rest, openly.** Hardcode accounts, stub integrations, use seeded data.
6. **Avoid expensive dependencies:** "Anything needing accounts, a second device, a payment, or an API you have never called spends hours you do not have." [P3]
7. **Halfway point (Sat evening): cut the remaining feature list in half.** [P3]
8. **One end-to-end path working by the halfway point**, then improve it. [P2]

## Our MVP (fill in at kickoff)
- **Who we build for:** _TBD_ (e.g. SME employee doing client lunches / the bookkeeper / the business owner)
- **Which part of the problem:** _TBD_ (collect · scan · book · keep 7 years)
- **One-sentence pitch:** _TBD_, "[Product] helps [who] [do what] so that [benefit]."
- **The single demo flow:** _TBD_
  1. …
  2. …
  3. …
- **Real vs mocked:**
  | Part | Real | Mocked | Why |
  |---|---|---|---|
  | … | | | |

## Candidate directions (from the market research, to decide at kickoff)
Based on the bottlenecks in [dutch-market.md](../research/dutch-market.md) §2 and the minesweeper map in [competitors.md](../research/competitors.md). Scanning/OCR alone is **not** a differentiator.
| # | Direction | Bottleneck it targets | Demo moment | Minesweeper |
|---|---|---|---|---|
| A | **Capture context at the moment of payment** (photo + "who/why" via voice/chat, AI fills in category and VAT treatment) | 2, 3 | Snap the lunch receipt, say "lunch with client X about project Y", and it's booked correctly with the VAT marked non-deductible | 🟩 not found in competitors |
| B | **Fiscal validity checker**: AI checks a receipt against NL rules (≤ €100 simplified invoice, VAT deductibility, authenticity, context present) | 3, 4 | Upload a receipt and see a red/green checklist with what's missing | 🟩 not found in competitors |
| C | **Match bank/card transactions to receipts**: the payment is digital (83%), so chase the missing receipt | 1, 2 | The bank feed shows "taxi €34, no receipt", with a one-tap reminder or a fetch from email | 💣 **Mine**: Jortt (9 Oct 2026), Exact SRXP + bunq, ING [C3][C4][C9] |
| D | **7-year compliant archive** (hash/timestamp as an authenticity feature, searchable) | 4, 6 | Show an "audit export" for one year in one click | 🟨 partly covered by bookkeeping packages |

### Additional candidates from the brainstorm ([brainstorm-transaction-evidence.md](../research/brainstorm-transaction-evidence.md) §7)
| # | Direction | Problem owner (who pays) | Verified signal | Minesweeper |
|---|---|---|---|---|
| E | **Subsidy evidence completeness**: flag missing invoice, payment proof, photos or codes *before* job handover | Installer / subsidy adviser | 215,454 ISDE applications in 2025 [S35] | 🟨 not mapped yet |
| F | **PO ↔ delivery note ↔ invoice discrepancy check** | Purchasing / AP | (none yet) | 💣 likely (Klippa, ERP/AP tools) |
| G | **Art consignment evidence trail** | Gallery | (none verified) | 🟨 Artlogic/Verisart nearby |
| H | **Warranty record + rights clarity** | Retailer / repair (payer unclear) | 59% don't claim, 90% want info on the receipt [S34] | 🟨 |

**Rule from the brainstorm:** a direction only wins if we get **recent real incidents, a measurable cost or hours, an unsolved workflow and a plausible buyer** (see its validation checklist). And never promise definitive VAT compliance, legal title or fraud verdicts: the AI **flags**, a human decides. → Directions A and B above should be framed as "flags missing or inconsistent evidence", **not** "guarantees tax compliance".

### Decision needed at kickoff
The **expense/fiscal angle (A/B)** has the strongest verified evidence and fits the brief ("client lunch, taxi, parking"). **E (subsidy)** has a clearer payer but is further from the brief. Pick one, then run the validation checklist.

## Out of scope (parking lot)
Ideas we explicitly will *not* build this weekend; mention them as "next steps" in the pitch.
- …

## Timeline
| When | Goal |
|---|---|
| Fri 16 Oct | Kickoff, ask about the rubric/format, pick user + problem, write the demo flow, set up the skeleton |
| Sat 17 Oct | Core flow working end-to-end (ugly is fine) |
| Sun 18 Oct | Polish the demo path, deck, record the backup video, rehearse |
| Mon 19 Oct | Final rehearsals, **15:00 presentation** |

## Decision log
| Date | Decision | Why |
|---|---|---|
| 2026-10-16 | Use Lightspeed horeca survey [S1] as primary problem evidence | Recent, Dutch, quantifies receipt waste and loss |
| 2026-10-16 | Focus pitch on the Dutch market, positioning OCR as a commodity | Research shows the pain is losing receipts, missing context and compliance, not the scanning itself |
| 2026-10-16 | Drop direction C (bank matching) as the main idea | Minesweeper: Jortt launched it on 9 Oct 2026 [C3]; Exact SRXP and ING already do it |
| 2026-10-16 | Added the brainstorm (evidence framing + directions E–H); fixed "62%" → two-thirds | Verification pass on the brainstorm numbers |
| 2026-10-16 | Only verified sources in the deck; removed fade-time, Unit4 and BPA claims | Reliability: see the Removed table in sources.md |
