# Pitch script (spoken)

Draft. Read it aloud with a timer and rewrite anything that sounds unnatural.
Target total: **TBD** (assume 4 min until the format is confirmed at kickoff).

| Time | Slide | Speaker | Text |
|---|---|---|---|
| 0:00 | 1 Hook | A | "Last week, someone took a client to lunch. They paid with their phone, like 83% of payments in the Netherlands today. And they still got this. By law, this slip has to stay checkable for **seven years**. And the VAT on it? Not deductible." |
| 0:25 | 2 Problem | A | "And it's not one receipt. We pay by phone, yet just 600 Dutch restaurants printed over **17 million** paper receipts last year. Two out of three Dutch companies say receipts regularly go missing from expense claims. And a quarter still process claims by hand, at **41 hours a month**, a full working week." |
| 0:50 | 2c Minefield | A | "Before we wrote any code, we mapped over 15 products. Scanning receipts? Moneybird does it for three euros a month. Matching receipts to payments? Jortt launched that last week. We're not building another scanner." |
| 1:05 | 3 Persona | A | TBD |
| 1:10 | 4 Solution | A | TBD: two sentences. |
| 1:25 | 5 Demo | B drives, A narrates | TBD: narrate what the *user* gains at each step, not what the code does. |
| 2:55 | 6 How it works | B | TBD |
| 3:25 | 7 Impact | A | TBD |
| 3:45 | 8 Next / Artifec | A | TBD |
| 3:55 | Close | A | TBD: one strong line, then stop talking. |

## Q&A answers
- **"How is this different from Expensify / Pleo / Moneybird scanning?"** Scanning is solved. Those tools start *after* you have a receipt and remembered to scan it. We focus on TBD (e.g. capturing context at the moment of payment / fiscal validity check / zzp-sized). Pleo needs 3+ users for OCR [C6] and Declaree targets 20+ users [C5], while about 81% of Dutch SMEs are one-person businesses [S8]. We see Moneybird and Jortt as the *destination*, not the competition.
- **"Is a scanned receipt legally valid?"** Yes, if the scan is a complete and correct copy, the authenticity features are kept, and it stays checkable for 7 years [S2]. For cash receipts, the Belastingdienst says to keep the original unless you've agreed otherwise [S2b].
- **"What if the AI reads the amount wrong?"** TBD (e.g. user confirms, confidence threshold)
- **"Privacy / GDPR?"** TBD
- **"Business model?"** TBD
- **"What would you do with more time?"** TBD
- **"Doesn't e-invoicing in 2030 solve this?"** E-invoicing targets B2B invoices. The government's letter of 11 Sep 2026 is about B2B invoices from 2030 and doesn't mention till receipts [S9]. The bill isn't even submitted yet (planned before summer 2027). Germany is already moving on digital till receipts from 2028 [S18]; the Netherlands isn't.
- **"Can you deduct the VAT on that lunch?"** No. Horeca food/drink VAT isn't deductible in NL, and the lunch cost itself only partly (80%, or above a €5,700 threshold) [S15]. That's exactly why the context and correct booking matter.
- **"Didn't Jortt just launch this?"** Jortt matches a receipt to a bank payment [C3]. That's useful, but it doesn't tell you whether the receipt is fiscally valid or what the business purpose was. We'd work well alongside it.
- **"Isn't a bank statement enough? The Consumentenbond says so."** For a warranty claim, yes [S24]. For the tax authority, no: a valid (simplified) invoice must show the supplier and the VAT [S16], and a bank line shows neither. That's why the receipt matters more for businesses than for consumers.
- **"Does your AI guarantee the booking is tax-compliant?"** No, and we deliberately don't promise that. It flags missing or inconsistent evidence (no context, cash receipt, over €100, non-deductible VAT) and the entrepreneur or bookkeeper decides.
