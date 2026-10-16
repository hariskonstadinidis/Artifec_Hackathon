# The receipt problem in the Dutch market

Where it hurts, who it hurts, and why now. Source IDs → [sources.md](sources.md) (all verified 2026-10-16). Competitors → [competitors.md](competitors.md).

## 0. Framing: it's not about paper, it's about *evidence*
From our brainstorm ([brainstorm-transaction-evidence.md](brainstorm-transaction-evidence.md)), transaction-evidence problems fall into three families:
1. **Missing proof:** the transaction happened but can't be shown (lost receipt, missing photo, warranty, subsidy).
2. **Untrusted proof:** a document exists but doesn't prove what people think (forged return receipts, a fraudulent expense, a receipt that doesn't prove the business purpose).
3. **Disconnected proof:** parties hold records that should agree but don't (purchase order vs delivery note vs invoice, receipt vs bank line).

A receipt proves a **transaction happened**, not that the **claim built on it** is valid (business purpose, warranty entitlement, ownership).

## 1. Market size: who has this problem?

| | Number | Source |
|---|---|---|
| Businesses registered at KVK (1 Jan 2026) | **2,599,668** (+0.8% in 2025) | [S7] |
| Zzp'ers registered at KVK (30 Jun 2026) | **1,805,194** | [S7] |
| SMEs (mkb) in the business economy (start of 2025) | **1.6M+** | [S8] |
| …of which zzp (one-person businesses) | **~81%** (was 70% in 2014) | [S8] |
| Pin payments at supermarkets / horeca (2025) | ≈ **2.1bn** / ≈ **0.82bn** (35.8% / 14.1% of 5.8bn) | [S26] |
| Online purchases / returned parcels (2025) | **347M** / **70.11M** (11.4% of 615M parcels) | [S29] [S28] |
| Fiscal administrative burden for SMEs (2024) | **≈ €5.5 billion/yr** (VAT part: €0.7bn) | [S10] |
| Dutch entrepreneurs spending ≥ 50% of their week on admin | **41.4%** (self-reported, n = 209 NL) | [S21] ⚠️ |

→ Most Dutch businesses are **one-person companies with no finance department**. The person who gets the receipt is also the person who has to book it and keep it.

## 2. The receipt journey and where it breaks

```
 PAY ──► GET RECEIPT ──► KEEP IT ──► ADD CONTEXT ──► SCAN ──► BOOK / CLAIM ──► ARCHIVE 7 YRS
(digital)  (paper)       (pocket)    (who? why?)    (legal)   (VAT/cost type)  (auditable)
```

### Bottleneck 1: The payment is digital, the receipt is paper
- **83%** of payments at the till are already by card or phone (cash 17%), across 7.1 billion transactions in 2025. [S11]
- Yet just 600+ Dutch horeca venues printed **17M+** paper receipts in 2025. [S1]
- Retailers' digital receipts aren't a fix: Hornbach's e-bon "is **geen fiscaal erkend document**". [S19]
- The Netherlands has **no** digital till-receipt rule. France (2023), Italy (2027–29), Austria (Oct 2026) and Germany (cabinet draft, 2028) are moving. [S18][S22]

### Bottleneck 2: Receipts go missing before they're processed
- **Two-thirds** of Dutch companies say receipts are **regularly missing** when expense claims come in. [S12]
- **23%** of consumers often lose receipts before they can use them. [S1]
- This is an old problem: in 2013, 25% of employees didn't claim because of a **lost receipt**, and 44% because they forgot. [S14] *(2013)*

### Bottleneck 3: The receipt alone isn't enough; it needs context and the right tax treatment
The client lunch is the clearest example:
- **VAT is not deductible** on food and drink consumed in a restaurant, even for business. [S15] ✅ official
- For income tax, business lunches and dinners (including tips) fall under "voedsel": the **first €5,700 isn't deductible**, or you choose to deduct **80%**. For corporate tax, the figure is **73.5%**. [S15] ✅ official
- To claim it as business at all, you must be able to show the business purpose, which only the person who paid knows (who, why).
- A till receipt is only a valid **simplified invoice up to €100 incl. VAT**. [S16] ✅ official
- So one lunch receipt needs: the right VAT code (non-deductible), the right cost category (with its limit), the business context, and a valid document.

### Bottleneck 4: Scanning is allowed, but with conditions
- Scanning is allowed if the copy is complete and correct and the **authenticity features** are kept. Then you can throw away the paper. [S2] ✅
- **But** scanned **cash** receipts are hard to verify, so keep the original unless agreed otherwise with the Belastingdienst. [S2b] ✅
- The digital archive must stay **checkable within a reasonable time for 7 years**. [S2] ✅

### Bottleneck 5: Processing is still manual
- **25%+** of Dutch companies process expense claims **manually**, mostly those with 1–50 employees, at **41 hours/month** on average. [S12] ⚠️ ICS-commissioned
- **28%** still have employees pay upfront and hand in paper receipts. [S12]
- International reference: 19% of expense reports contain errors; each fix costs $52 + 18 min. [S4] ⚠️ 2015, US

### Bottleneck 6: Archiving for 7 years
- Paper or digital, the record must be kept for 7 years (10 for real estate) and be auditable. [S2]

### Side note: the warranty / proof-of-purchase angle
- **59%** of consumers with a defective product didn't claim warranty; **64%** of them thought it had expired. **90%** want warranty info on the receipt or purchase confirmation. [S34] ⚠️ panel
- For a **warranty claim**, a bank statement can replace the lost receipt, as long as you can prove you bought it at that shop. [S24]
- But stores get warranty wrong anyway: in a Consumentenbond mystery-shopping test, **3 out of 4** retailers gave incorrect or incomplete warranty information. [S23] ⚠️ small sample, consumer side
- **Our inference (not a source claim):** for the **Belastingdienst**, the bank statement isn't enough. A simplified invoice must show the supplier and the VAT [S16], and a bank line shows neither. So the receipt matters *more* for tax than for warranty, and that's the business-side problem.
- Relevance for us: warranty is a **secondary use case** (e.g. a business buys a laptop or machine and needs the receipt years later). Keep it for "next steps", not as the core pitch.

### Adjacent problem areas (from the brainstorm, verified numbers only)
| Area | Verified signal | Problem owner | Caveat |
|---|---|---|---|
| **Receipt errors at the till** | 13% of checked promo items mispriced at 6 regional supermarkets [S27] | Retailer, consumer | Promo items only |
| **Return / receipt fraud** | 70.11M return parcels [S28]; a 2025 police case with several hundred thousand euros [S31]; US benchmark 9% fraudulent [S32] | Webshop, loss prevention | No Dutch fraud rate; receipts not proven as the cause |
| **Subsidy evidence (ISDE)** | 215,454 applications, €469.1M claimed in 2025 [S35] | Installer, subsidy adviser | No data on how many are rejected for missing proof |
| **PO ↔ delivery note ↔ invoice** | (no verified NL figure yet) | Purchasing / AP | Existing three-way-matching tools |
| **Art consignment / provenance** | (art figures not verified) | Gallery | Niche size unknown |

### Not an argument for NL
- "Toxic receipts": Dutch shop receipts are BPA-free and go in the paper bin. [S30]

## 3. Why now?
- **NL e-invoicing:** mandatory for domestic and intra-EU **B2B** from **1 July 2030**, with digital reporting from 1 July 2031. Consultation is in autumn 2026 and the bill is due before summer 2027. [S9]
- **But:** that letter covers **B2B invoices only** and says nothing about till receipts or simplified invoices. [S9] So the client-lunch receipt is **not** solved by the 2030 law, as far as we can tell.
- **EU ViDA:** intra-EU B2B e-invoicing from July 2030. Member states may already extend it to domestic B2B and B2C. [S5]
- **Neighbours go digital:** Germany's cabinet approved digital till receipts from 2028 (23 Sep 2026). [S18] France, Italy and Austria are ahead too. [S22]
- **Consumers are ready:** 72% are positive about digital receipts. [S1]
- **The government wants less burden:** €5.5bn of fiscal admin burden on SMEs. [S10]

## 4. Existing solutions
See **[competitors.md](competitors.md)** for the full minesweeper map. In short:
- Receipt OCR and booking is a **commodity**: Moneybird includes it from €3/month. [C1]
- Receipt ↔ bank matching was **just launched** by Jortt (9 Oct 2026). [C3]
- Team expense tools (Pleo, Declaree, etc.) target **teams of 3–20+**. [C5][C6]
- In the products we looked at, we **didn't find** any that check a receipt against Dutch fiscal rules (horeca VAT, €100, cash, business-lunch deduction) or capture the business context at the moment of payment.

## 5. Still open
- [ ] Does the NL e-invoicing bill (consultation in autumn 2026) say anything about simplified invoices or till receipts?
- [ ] Ask Artifec at kickoff: which part of this hurts their clients most?
