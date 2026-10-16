# Presentation: slide outline

Living outline. `TBD` = waiting for an MVP decision. Numbers cite [sources](../research/sources.md); every number on a slide must be ✅ verified there.
Target: ~6–8 slides, one idea per slide, big numbers, little text.

---

### Slide 1: Hook
- Visual: a real crumpled lunch receipt next to a phone showing the card payment.
- Line: *"We paid with a phone. We still got this paper. By law, this slip has to stay checkable for 7 years, and we can't even deduct the VAT on it."*
- Data: 83% of till payments are digital [S11]; 7-year retention [S2]; horeca VAT not deductible [S15]
- ❌ Don't claim how fast thermal paper fades (no reliable source)

### Slide 2: The problem (in numbers)
- **17M+** paper receipts printed in 2025 by just 600+ Dutch horeca venues [S1], while 83% of payments are already digital [S11]
- **2 out of 3** Dutch companies say receipts are **regularly missing** from expense claims [S12]
- **25%+** still process claims manually, at **41 h/month** [S12] (small print: "research by PanelWizard for ICS")
- For a business, every receipt is a **tax document it must keep for 7 years** [S2]

### Slide 2b (optional): Where it breaks: the receipt journey
- Visual: PAY → RECEIPT → KEEP → CONTEXT → SCAN → BOOK → ARCHIVE 7 YRS, with a red mark where we intervene
- Key insight: scanning (OCR) is solved. The pain is **losing it**, **missing context** (who/why; horeca VAT isn't deductible, lunch cost only 80% deductible [S15]) and **proving it for 7 years** [S2]
- See [dutch-market.md](../research/dutch-market.md) §2

### Slide 2c: We checked the minefield first 💣
- Visual: a minesweeper grid. Red mines = OCR scanning (Moneybird from €3/month [C1]), bank matching (Jortt, 9 Oct 2026 [C3]), team expense tools (Pleo, Declaree [C5][C6]), POS digital receipts (ReceiptHero + Visa/MC [C10]). Green square = **our spot**.
- Line: *"Before writing a line of code, we mapped 15+ products. We're not building another scanner."*
- Source: [competitors.md](../research/competitors.md)

### Slide 3: Who we built for
- Persona: TBD (name, role, one sentence about their pain)

### Slide 4: Our solution, in 2 sentences
- TBD: "[Product] helps [who] [do what] so that [benefit]."

### Slide 5: Live demo
- (switch to demo; backup video ready)
- Flow: TBD (see [mvp.md](mvp.md))

### Slide 6: How it works (for the CTO)
- Architecture diagram: TBD
- What's real / what's mocked (be honest)
- Compliance: meets the scan requirements (complete, correct, authenticity, checkable for 7 years) [S2]; flags cash receipts (keep the original) [S2b]

### Slide 7: Impact & why now
- Time/cost saved per receipt: TBD (our estimate vs the 41 h/month baseline [S12])
- **1.8M zzp'ers** + 1.6M SMEs, most without a finance department [S7][S8]
- **72%** of consumers are already positive about digital receipts [S1]
- NL: **mandatory B2B e-invoicing from 1 July 2030**, but till receipts aren't in scope [S9]; Germany's cabinet approved digital receipts from 2028 [S18]

### Slide 8: Next steps & fit with Artifec
- What we'd build next: TBD
- How Artifec could offer this to its clients: plugs into their existing bookkeeping (Moneybird/Exact/Jortt…) instead of replacing it ([competitors.md](../research/competitors.md) positioning)
- Closing line: TBD
