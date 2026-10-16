# Competitive landscape: the "minesweeper" map 💣

**Why this file exists:** before building anything, we mapped what already exists, so we don't step on a mine. A "mine" is building something that already exists, that a big player dominates, or that we can't win in 3 days. In the pitch this shows the judges that **research was done first** and that our solution sits in a gap, not on top of an existing product.

Researched: 2026-10-16. Only facts from the vendor's **own website** or **reputable news** are used. Vendor claims are labelled as claims. Problem sources (`[S#]`) are in [sources.md](sources.md).

---

## 1. Bookkeeping software with receipt scanning (NL, zzp/SME)

| Product | What it does with receipts | Price (official) | Source |
|---|---|---|---|
| **Moneybird** | "Scan en herken" included in **all** plans (Compact plan: 3 smart documents) | Compact €3 · Start €15 · Groei €29 · Compleet €41 /month | [C1] ✅ |
| **e-Boekhouden.nl** | "Scan & Mail & Herken": put receipts and invoices into the books; scanning uses credits (from €0.09 each) | ZZP €9.95 · Standaard €14.50 · +Factureren €24 /month; free for 15 months for starters | [C2] ✅ |
| **Jortt** | **Since 9 Oct 2026:** AI reads the receipt and **automatically links it to the bank payment** (amount + invoice number/date must match); "Liever geen bon dan een verkeerde bon" | AI Scan en Herken in Jortt Plus, €39.95/month ex VAT | [C3] ✅ |
| **Exact Online + Exact SRXP** | Expense app: photo → OCR (location, currency, amount) → manager approves with a swipe → one-click export; matches credit-card and **bunq** debit-card transactions to receipts | Per-user pricing (check exact.com) | [C4] ✅ |
| Others in the same category | SnelStart, Yuki, Twinfield, Tellow, Rompslomp, Informer: all offer some form of receipt/document scanning | – | (found in comparison sites; not individually verified) |

**💣 Mine:** a standalone "photo → OCR → booking" receipt scanner. Every Dutch bookkeeping package already does this, and the cheapest costs €3/month.
**💣 Mine:** "match receipt to bank transaction". Jortt launched exactly this **one week ago** (9 Oct 2026), and Exact SRXP does it for cards.

## 2. Expense management for teams (employees → approval → reimbursement)

| Product | Focus | Facts | Source |
|---|---|---|---|
| **Declaree** (by Mobilexpense) | Expense app; founded **Rotterdam 2012**; "AI receipt scanner"; approvals, mileage, cards, ERP links | "Designed for small and mid-size companies with a **minimum of 20 users**"; claims 3,000+ companies; from €8/month | [C5] ✅ |
| **Pleo** | Company cards + expenses | Start €8 · Build €14 · Optimise €18 per user/month; receipt **OCR only from Build** (min. 3 users); receipt capture by email and receipt reminders in all plans | [C6] ✅ |
| **SAP Concur, Expensify, Spendesk, Payhawk, Moss, Rydoo, Qonto** | International expense/spend platforms, mostly for mid-size to enterprise teams, often card-based | Positioning described in vendor comparisons (e.g. Spendesk's own list), so not neutral | [C7] ⚠️ |

**💣 Mine:** approval workflows, company cards, reimbursements. These are crowded, well-funded markets, and they target **teams of 20+**. Meanwhile ~81% of Dutch SMEs are one-person businesses [S8].

## 3. Receipt capture for accountants / bookkeepers

| Product | Facts | Source |
|---|---|---|
| **Dext** (formerly Receipt Bank, part of IRIS) | Receipt and invoice capture for accounting firms; claims 700k+ businesses and 12k+ accounting firms worldwide | [C8] ⚠️ vendor claim |
| **Hubdoc** (Xero) | Xero's document capture tool, bought by Xero in 2018 | [C8] ⚠️ |

**💣 Mine:** document capture for accounting firms. Global players already serve it, bundled with accounting software.

## 4. Banks

| Product | Facts | Source |
|---|---|---|
| **ING "Bonnen & Facturen"** | In the ING business app: photograph a receipt and **attach it to the transaction**. Launched for 80,000 business customers (2018). | [C9] ⚠️ 2018 news; current availability not verified |
| **bunq** | Debit-card transactions sync in real time into Exact SRXP and are matched with receipts | [C4] ✅ |

## 5. Digital receipts at the point of sale (merchant side)

| Product | Facts | Source |
|---|---|---|
| **ReceiptHero** (Finland) | **Card-linked** digital receipts in the customer's banking app or browser, itemised with a VAT breakdown; partners include Visa, Mastercard, Adyen, Worldline, Verifone; segments include expense/TEM | [C10] ✅ |
| **fiskaly** | One digital-receipt API for many countries (QR, Apple/Google Wallet, Mastercard delivery) | [C11] ✅ |
| **anybill, efsta, fiskaltrust, Recepta** | POS-integrated digital receipt providers, mostly in DACH | [C12] ⚠️ trade-fair overview |
| **Lightspeed** | POS/payments for horeca; publishes the receipt-waste research [S1] | [S1] ✅ |
| **Bonnie** (Leiden, NL) | Startup device that sends the receipt to the customer's phone from the existing POS | [C13] ⚠️ current status unknown |
| **Retailer e-receipts** (e.g. Hornbach) | Receipt in the customer account, but "**geen fiscaal erkend document**" | [S19] ✅ |

**💣 Mine:** building a digital-receipt network at the POS. It needs merchant and POS integrations (a chicken-and-egg problem), and well-funded players with Visa and Mastercard partnerships already exist.
**Note:** the regulation is moving here (France 2023, Italy 2027–29, Austria Oct 2026, Germany cabinet draft for 2028) [S18][S22]. **The Netherlands has no digital till-receipt rule yet**, and the 2030 e-invoicing law covers **B2B invoices only** [S9].

## 5b. Adjacent workflows (from the brainstorm, not yet verified)
| Product | Area | Status |
|---|---|---|
| **Klippa** | Document processing, incl. three-way matching (PO ↔ delivery note ↔ invoice) | ⚠️ named in the brainstorm; check https://www.klippa.com/ |
| **Artlogic** | Gallery inventory/management | ⚠️ https://artlogic.net/ not verified |
| **Verisart** | Digital certificates for artworks | ⚠️ https://verisart.com/ not verified |

**💣 Likely mines:** three-way matching (ERP/AP tools) and art certification (Verisart). The brainstorm itself notes that "general receipt storage is not an uncontested opportunity".

## 6. Building blocks (tools we can *use*, not competitors)
- **OCR / document AI APIs:** Veryfi, Mindee, Google Document AI, AWS Textract, Azure Document Intelligence, Klippa. Also **multimodal LLMs** (e.g. Claude) that can read a receipt photo and return structured JSON.
- So OCR is a **commodity**: we shouldn't compete on "we read receipts", but use it as an ingredient.

---

## 🗺️ Minesweeper summary

| Square | Status | Why |
|---|---|---|
| Receipt photo → OCR → booking | 💣 **Mine** | Every NL bookkeeping package has it (from €3/month) [C1–C4] |
| Receipt ↔ bank transaction matching | 💣 **Mine** | Jortt launched it on 9 Oct 2026 [C3]; Exact SRXP + bunq [C4]; ING [C9] |
| Team expense approval + company cards | 💣 **Mine** | Pleo, Declaree, Concur, Expensify, Spendesk… [C5–C7] |
| Digital receipts at the POS / card-linked | 💣 **Mine** (for a 3-day hackathon) | ReceiptHero + Visa/MC, fiskaly, anybill [C10–C12] |
| **Dutch fiscal-rules intelligence at the moment of capture**: VAT not deductible in horeca [S15], ≤ €100 simplified invoice [S16], cash receipts need the original [S2b], business-lunch deduction rule (€5,700 threshold or 80%) [S15] | 🟩 **Open (in our research)** | None of the tools we looked at advertise checking a receipt against these NL rules. They read and book it; they don't tell you whether it will hold up in an audit. |
| **Context capture (who / why) at the moment of payment**, needed to prove the business purpose of a lunch [S15] | 🟩 **Open (in our research)** | The tools capture the *receipt*, not the *story* behind it |
| **Sized for the 1-person business** (81% of SMEs [S8]) with no finance team | 🟨 **Partly open** | Bookkeeping apps serve zzp'ers; expense tools target 20+ users [C5][C6] |
| A bridge for receipts that **won't** be covered by 2030 e-invoicing (till receipts, B2C-style) | 🟨 **Partly open** | [S9] covers B2B only; the NL has no digital-receipt rule (unlike DE, FR, IT, AT) [S18][S22] |

> ⚠️ "Open" means **we didn't find it** in our research, not that it doesn't exist anywhere. Say it that way in the pitch: *"In the 15+ products we looked at, none…"*

**Positioning for the pitch:** *"We don't compete with Moneybird or Jortt. They're the destination. We make sure what arrives there is complete, valid under Dutch tax rules, and still defensible in 7 years."* That also fits Artifec's role as an **AI and automation partner** that plugs into a client's existing tools.

---

## Competitor sources

- **[C1]** Moneybird pricing: https://www.moneybird.nl/prijzen/ ✅ (2026-10-16)
- **[C2]** e-Boekhouden.nl pricing: https://www.e-boekhouden.nl/prijzen ✅ (2026-10-16)
- **[C3]** Jortt press release "Jortt koppelt bonnetjes nu zelf" (Emerce, 9 Oct 2026): https://www.emerce.nl/?p=7126127 ✅
- **[C4]** Exact SRXP: https://www.exact.com/nl/producten/exact-srxp ✅ (via exact.com pages: OCR flow, credit-card matching, bunq integration)
- **[C5]** Declaree by Mobilexpense: https://www.mobilexpense.com/product-declaree ✅ (2026-10-16)
- **[C6]** Pleo NL pricing: https://www.pleo.io/nl/pricing ✅ (2026-10-16)
- **[C7]** Spendesk's own comparison (biased): https://www.spendesk.com/blog/best-expense-management-software/ ⚠️
- **[C8]** Dext (Receipt Bank): https://dext.com/us/receipt-bank ⚠️ vendor claims; Hubdoc: Xero acquisition in 2018 (several trade sources)
- **[C9]** ING Bonnen & Facturen: https://www.banken.nl/nieuws/amp/20606/ing-lanceert-bonnen-facturen-app-functionaliteit-voor-ondernemers · https://finextra.com/newsarticle/31595/ing-introduces-receipts--invoices-app-for-smes ⚠️ 2018
- **[C10]** ReceiptHero: https://getreceipthero.com/en ✅ (2026-10-16); 2021 Visa/Mastercard partnership: https://thefintechtimes.com/the-future-of-receipts-to-be-digital-with-new-partnership-between-receipthero-visa-and-mastercard/
- **[C11]** fiskaly digital receipt: https://www.fiskaly.com/digital-receipt ✅
- **[C12]** EuroShop "Providers of digital receipts compared": https://www.euroshop-tradefair.com/en/media-news/euroshopmag/retail-technology/providers-of-digital-receipts-compared ⚠️ not opened in full
- **[C13]** Bonnie: https://www.f6s.com/company/bonniedigitalreceipts ⚠️ the Rabobank article was blocked; status unknown
