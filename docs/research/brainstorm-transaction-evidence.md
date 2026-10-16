# The Receipt Problem in the Netherlands
## Research & Opportunity Discovery Brief

**Project:** Artifec × Codam Hackathon  
**Date:** 16 October 2026  
**Scope:** Dutch consumer and business markets; physical receipts, digital purchase records, invoices, delivery notes, ownership documentation, and missing transaction evidence  
**Stage:** Problem discovery and validation — **not** a committed product specification

> ✅ **Verification pass (2026-10-16):** the numbers below were checked against the original publications. Verified sources were added to [sources.md](sources.md) as [S25]–[S35]. Corrections and unverifiable items are marked inline with ✅ / ❌ / ⚠️. **Only ✅ numbers go into the pitch.**

> **Central research question:** Where does the absence, unreliability, or fragmentation of transaction evidence create a recurring, costly problem — and who has both the incentive and ability to pay to solve it?

---

## Executive summary

The Netherlands is already highly digital in payments, yet paper receipts and fragmented transaction records still persist. Our research suggests that **printing too many receipts is only one symptom**. The larger opportunity may lie in what happens when transaction evidence is **missing, inaccurate, unverified, duplicated, or disconnected from the next business process**.

Three distinct problem families emerged:

1. **Missing proof:** A real transaction or completed task cannot be demonstrated easily because documents or photos were never captured, were lost, or are incomplete. Examples: warranty claims, subsidy applications, insurance claims.
2. **Untrusted proof:** Documents exist but do not establish what users think they establish. Examples: forged return receipts, questionable art provenance, fraudulent expense claims, fake invoices.
3. **Disconnected proof:** Different parties hold records that must agree, but do not. Examples: supplier invoice vs. goods delivered, gallery consignment vs. sale and artist payout, product ownership histories when reselling goods.

**The most promising near-term investigation areas** are (a) missing evidence in subsidy/installation workflows, (b) purchase order–delivery note–invoice mismatches, and (c) art-gallery consignment and custody documentation. Warranty proof and consumer rights also present compelling demand evidence, but identifying a willing payer is harder.

**Important limitation:** No verified, recent national count of *paper receipts printed* in the Netherlands was established in our research. Payment counts, parcel counts, deposit containers, and invoice volumes must **not** be represented as printed-receipt counts.

---

## 1. Market size and measured signals

| Area | Research signal | What it actually means | Qualification |
|---|---:|---|---|
| Dutch physical checkout payments | **~7.1 billion / year (2025)** ✅ [S11] | All checkout payments across payment methods | **Not** 7.1 billion paper receipts |
| Supermarket transactions | **Over 1.9 billion debit payments (2025)** ✅ ≈2.1bn: 35.8% of 5.8bn pin payments [S26] | Debit-card activity in supermarkets | Excludes other payment methods; not printing volume |
| Hospitality | **~830 million debit payments (2025)** ✅ ≈0.82bn: 14.1% of 5.8bn [S26] | Debit-card activity in horeca | Not printing volume |
| Hospitality printing | **~17.4 million paper receipts (2025)** ✅ [S1] | Receipts printed in the systems of **600+ Dutch Lightspeed locations** | Vendor-specific sample, not national total |
| Consumer attitude to digital receipts | **72% positive** ✅ [S1] | Respondents favorably disposed to digital alternatives in Lightspeed/Factsnapp survey | Survey, not observed adoption |
| Business expenses | **41 hours/month** ✅ [S12] | Reported average monthly manual expense-processing time in relevant organizations | ICS-commissioned survey; not all companies |
| Missing business receipts | ~~62%~~ ❌ → **two-thirds ("twee derde")** ✅ [S12] | Share of companies that say receipts are regularly missing from expense claims | Survey figure, not transaction incidence |
| Supermarket checkout pricing | **13%** ✅ [S27] | Mispriced *selected promotional products* in a 2025 Consumentenbond investigation | **Not** 13% of all items in Dutch supermarkets |
| Dutch online purchases | **347 million (2025)** ✅ [S29] (615M B2C parcels shipped [S28]) | E-commerce purchase count | Not returned parcels or receipts |
| Dutch B2C returned parcels | **70.11 million (2025)** ✅ 11.4% of parcels [S28] | Volume of return parcels | Not necessarily fraudulent or receipt-dependent |
| Deposit-return ecosystem | **Over 4.5 billion beverage containers annually** ⚠️ no source given, not verified | Bottles/cans handled within the system | Not vouchers: one voucher can cover multiple containers |

**Interpretation:** Grocery and hospitality have enormous transaction exposure; employee expenses and returns can generate higher processing or fraud costs per incident. **High volume alone does not identify the highest-value problem.**

### Approximate paper economics

Illustrative 80 mm thermal-paper supplier prices previously reviewed imply a **paper-only cost of roughly €0.003–€0.0065 for a 25 cm receipt**, or **€3,000–€6,500 per million receipts**, before labor, printers, maintenance, disposal, and different bulk procurement prices. These are **scenario calculations**, not measured Dutch industry averages. ⚠️ No source for the supplier prices, so don't put this in the pitch.

**Implication:** Paper elimination may have environmental benefits, but paper savings alone might be insufficient to support a strong business case. Time saved, claims prevented, or incorrect payments caught could be more economically valuable.

---

## 2. Where receipts create problems

| Sector / workflow | Underlying problem | Most affected | Potential cost / consequence |
|---|---|---|---|
| **Supermarkets** | Unwanted printing; pricing discrepancies; use of checkout barcode for exit control | Retail operators, consumers | Waste, wrong charges, customer friction, security dependencies |
| **Hospitality** | Paper tickets and customer receipts persist despite digital POS | Restaurant owners, staff | Printing, handling, operational complexity |
| **SME expense claims** | Lost, duplicated, altered, or manually categorized receipts | Employers, finance teams | Administrative hours, errors, fraud exposure |
| **Retail refunds** | False claims can be supported by counterfeit or genuine-but-misused receipts | Retailers, loss-prevention teams | Invalid refunds and investigation effort |
| **E-commerce returns** | Goods received do not match refund claim; incomplete return history | Webshops, platforms, fulfillment teams | Losses, refunds, disputes |
| **Warranties / repair** | Consumers cannot find purchase proof or misunderstand their legal entitlements | Consumers, service teams | Abandoned claims, avoidable replacement, disputes |
| **Secondhand resale** | Purchase, service, ownership and warranty history does not travel with item | Buyers, refurbishers, resellers | Uncertainty, support costs, reduced trust |
| **Art market** | Incomplete provenance, questionable ownership documentation, custody ambiguity | Galleries, auction houses, artists, collectors | Due diligence cost, disputed title, litigation, reputation |
| **Subsidy applications** | Required invoice, payment proof, photos or product codes are missing | Homeowners, installers, subsidy advisers | Rework, delay, rejected applications |
| **Procurement / delivery** | Purchase order, delivery note and invoice disagree | Procurement, warehouse, accounting | Overpayments, disputes, manual reconciliation |
| **Insurance** | Owner cannot reconstruct evidence of belongings after loss | Policyholders, claims assessors | Delay, reduced or contested claims |
| **Gift cards and deposit vouchers** | Money-equivalent paper or digital records are lost or expire | Consumers; sometimes retailers | Unredeemed value and friction |

### The important distinction

An authentic receipt may prove that a **transaction occurred**, but not necessarily that:

- The seller legally owned an artwork.
- A returned product is the same product that was originally purchased.
- An employee expense had a legitimate business purpose.
- A service or construction job was correctly completed.
- An owner can transfer a manufacturer's warranty.

**Document authenticity and validity of the underlying business claim are different problems.**

---

## 3. Receipt fraud: what is documented?

### Categories to keep separate

- **Retail receipt / refund fraud:** Fake, altered, or misused proof of purchase used to request a refund. A genuine receipt can also be misused; verifying a barcode alone may be insufficient.
- **Return fraud:** Dishonest refund requests when goods are not legitimately returned. May involve no paper receipt at all.
- **Employee expense fraud:** Personal, altered, or duplicated expenses presented for reimbursement.
- **Invoice and VAT fraud:** Fictitious transactions or manipulated invoices used to extract money or tax benefits; generally *not* the same market as consumer receipts.
- **Self-checkout theft:** Important for supermarkets but must not be counted automatically as receipt fraud.

### Strength of the evidence

| Evidence | What it supports | What it **does not** support |
|---|---|---|
| Historic Dutch trade estimate of **€5–10 million/year** for kassabonfraude (2009) ❌ not found on the linked INretail page (which only describes receipt/return fraud) [S33] | Fraud involving checkout receipts has long been recognized | A reliable estimate of **2026** receipt fraud |
| Dutch police investigation, **2025**, alleging **hundreds of thousands of euros** in online return fraud ✅ [S31] (fake "returned" claims; receipts not mentioned) | Individual return-fraud cases can be material | Proof that the fraud depended on forged receipts |
| **70.11 million** Dutch B2C return parcels (2025) | A high-volume workflow potentially exposed to fraud | A Dutch fraud rate |
| **9%** fraudulent retail returns in a US NRF/Happy Returns 2025 benchmark ✅ [S32] | International indication that return fraud is a known category | The Dutch fraudulent-return percentage |
| Benelux Allianz Trade research on internal fraud and document falsification | Document fraud exists inside businesses | A receipt-specific Dutch financial-loss rate |
| Dutch FIOD/FIU cases involving **multi-million-euro false invoices** | Serious financial damage from fraudulent transaction documents | A market-size estimate for ordinary receipt forgery |

**Conclusion on fraud:** There is a real problem, but we lack a credible, recent, receipt-specific Dutch loss total. Before proposing a fraud product, find who loses money, how often, what existing controls catch, and what fraction is specifically attributable to receipt/record weaknesses.

---

## 4. Deep dive: artwork, provenance and ownership

### Four separate questions

1. **Purchase:** Was money paid and by whom?
2. **Title:** Did the seller have the right to transfer ownership?
3. **Authenticity:** Is the artwork genuinely attributed to the claimed creator?
4. **Copyright:** Who holds reproduction/commercial-use rights?

A receipt does **not** conclusively answer all four. Ownership also differs from physical **custody**: an artwork can be held by a gallery on consignment while remaining owned by an artist or collector.

### Evidence that the problem exists

- Dutch legal and public-enforcement cases show disputes involving art provenance, authenticity of records, or title.
- ⚠️ *Art figures below were not re-verified.* Paid professional research exists. Previously reviewed RKD prices included **€680 excluding VAT for five research hours**; Art Loss Register listed a **standard single search around €100**. These services perform different tasks.
- The Netherlands has a sizeable art ecosystem; the researched figure of **810 galleries/exhibition spaces** in 2025 is **not** the number of active commercial galleries alone.
- The Dutch Gallery Association's fair-practice rules emphasize written gallery–artist agreements, payment conditions and sales documentation.
- Pictoright administers statutory art resale royalties, creating document/reporting duties for relevant sales.

### More promising niche than “certify every artwork”

**Art consignment and custody workflow**:

Artist/collector entrusts piece → gallery acknowledges custody → piece moves to exhibition/fair → sale is agreed → invoice and payment are recorded → artist receives share → buyer receives evidence.

Potential pain points:

- Who owns the piece vs. who currently holds it?
- Are signed consignment agreements and movement records accessible?
- Did the sale trigger the correct invoice, artist payment or resale-royalty check?
- Can the gallery reconstruct the history during a dispute or insurer inquiry?

**Likely problem owner:** Gallery operator or consignment administrator; sometimes artist or dealer.

**Competition and limitation:** Artlogic and Verisart already provide inventory/certification features. Blockchain or an AI-generated certificate cannot establish legal ownership merely by recording a claim. The unmet workflow, frequency, and willingness to pay must be demonstrated.

---

## 5. Noteworthy adjacent problems discovered

### A. Warranty evidence and consumer rights

Consumentenbond research published **8 October 2026** among approximately **3,100 panel members** reported (✅ [S34]; percentages refer to the ~1,000+ members who had a defective product):

- **59%** of surveyed consumers in the relevant question group did not make a claim after a product problem.
- Among non-claimants, **64%** thought the warranty had expired.
- **90%** wanted warranty information on a purchase confirmation or receipt.

**Implication:** The customer may lack not just a receipt but a clear, product-specific understanding of legal warranty rights. The Netherlands does not have one universal fixed two-year legal-warranty expiry for every product.

**Open business question:** Who pays to make consumers better at asserting their rights—retailers, repair providers, insurers, or consumers themselves?

### B. Subsidy evidence lost before an application

RVO figures reviewed for the ISDE scheme reported **215,454 applications in 2025**, covering approximately **€469.1 million** of *claimed* budget ✅ [S35] (partly estimated, reference date 5 Jan 2026; €431.8M private, €37.3M business; rejected applications not counted). Requirements can include invoices, proof of payment, technical codes and installation photos.

**Root issue:** Necessary proof is sometimes never collected *at the moment the work occurs*. Retrieving it later may require calls, return visits or impossible reconstruction.

**Owner:** Installation business or subsidy adviser with repeated cases. **Product hypothesis:** Detect missing application evidence *before* job handover.

Caution: Application volumes are not rejection volumes; specific rates of denial because of missing receipts were **not established**.

### C. Supplier receiving and invoice matching

A purchase order, delivery note (*pakbon*) and invoice may not agree. For example, **150 units ordered, 138 confirmed delivered, 150 billed**. An accounts-payable team must reconcile the difference.

**Owner:** Purchasing manager, finance manager, warehouse/operations head. **Potential measurable value:** Incorrect payments avoided and investigation time saved.

**Competition:** Established three-way-matching/document tools, including Klippa. Differentiation must be tested, especially among smaller firms and specialist workflows.

### D. Secondhand goods and insurance

Product history can fail to transfer to a second owner: original proof of purchase, repair records, serial numbers, warranty and ownership evidence. Insured households may similarly struggle to reconstruct records after loss.

**Owner:** Potentially professional refurbisher, resale platform, insurer or claims processor. **Evidence gap:** We did not establish Dutch-wide financial losses caused specifically by missing purchase evidence.

---

## 6. Problem ownership: who actually pays?

A legitimate **problem owner** is not simply someone annoyed by a receipt. They should (1) experience the problem repeatedly, (2) incur measurable cost or risk, and (3) have responsibility and budget to change the workflow.

| Problem | Operational problem owner | Possible budget holder | Main commercial uncertainty |
|---|---|---|---|
| Refund/receipt fraud | Retail returns & loss prevention | Retail operations director | Existing POS controls may already catch most cases |
| Missing expense receipts | Finance/AP team | CFO or business owner | Crowded automation market |
| Art custody/consignment | Gallery operator | Gallery owner | Frequency/severity among small galleries |
| Art provenance research | Dealer/auction specialist | Dealer or auction house | Specialist work may not be safely automated |
| Missing subsidy evidence | Installation administrator/subsidy adviser | Installer owner, intermediary | Actual preventable cost per application |
| Delivery/invoice mismatch | Purchasing, warehouse, AP | CFO, procurement lead | Existing ERP/AP coverage |
| Warranty records | Consumer, after-sales staff | Retailer, repair provider, possibly insurer | Consumer and retailer incentives may conflict |
| Voucher expiry | Consumer | Unclear | Issuer may lack incentive to increase redemption |

A critical lesson: **The beneficiary and the payer are not always the same.** That is particularly true for warranties, gift cards and consumer-held digital receipts.

---

## 7. Opportunity shortlist for a four-day hackathon

These are **research hypotheses**, not validated market rankings.

| Candidate | Clear problem owner | Measurable value | Demonstrable in 4 days | Biggest obstacle |
|---|---|---|---|---|
| **Subsidy evidence completeness** | Installer / subsidy adviser | Fewer missing docs, less rework | **Yes**: document checklist, OCR, evidence alerts | Competitors and rules complexity |
| **Delivery/invoice discrepancy detection** | Purchasing / AP | Review time and overpayments | **Yes**: compare purchase order, pakbon, invoice | Existing software integration |
| **Art consignment evidence trail** | Gallery / artist | Less confusion, faster reconciliation | **Yes**: custody events and agreements | Niche size and incumbents |
| **Warranty record + rights clarity** | Repair / retail service | Faster cases, fewer abandoned repairs | **Yes**: product record and claim checklist | Finding a willing payer |
| **Expense-document anomaly detection** | Finance / employer | Reduced manual checks and duplicate claims | **Yes**: flag duplicates/inconsistencies | Strong competition; false positives |
| **Art historical provenance assistant** | Dealer / auction specialist | Less time assembling evidence | **Partial**: research dossier with gaps | Can't independently verify legal title/authenticity |
| **Secondhand item history handover** | Professional refurbisher | Better trust and lower dispute handling | **Yes**: transferable product record | Source records and verification |

### Three highest-priority interviews

**1. Installer / subsidy adviser**  
“Show us the last five applications that required corrections. Which documents were missing, when could that have been caught, and how much extra work did it cause?”

**2. Purchasing/AP team**  
“Show us one recent supplier invoice that did not match the delivery. How did you discover it, how long did the investigation take, and what amount was at stake?”

**3. Independent art gallery**  
“Walk us through your most recent consignment and sale. Where are the agreements, movement records, sale invoice, artist payout and provenance evidence stored? Which step requires manual reconstruction?”

### Fast validation checklist

- [ ] Identify one specific organization and a named role that owns the problem.
- [ ] Obtain at least 2–3 descriptions of *actual recent incidents*, not hypothetical opinions.
- [ ] Estimate frequency (per week/month) and financial or time cost per incident.
- [ ] Ask what software/process the organization already uses and why it falls short.
- [ ] Distinguish genuine failures from deliberate fraud and from regulatory obligations.
- [ ] Verify that the proposed workflow is legally and technically feasible.
- [ ] Establish who has budget and what success metric they would pay for.
- [ ] Build the smallest prototype that demonstrates one **measurable improvement**.

**Disqualifying signal:** “Nice idea” feedback without a recent incident, existing expenditure, or clear decision-maker.

---

## 8. What we should *not* claim

- **7.1 billion transactions ≠ 7.1 billion printed receipts.**
- **70 million returns ≠ 70 million fraudulent returns.**
- **Retail theft ≠ receipt fraud**, unless the causal connection is demonstrated.
- The **historical €5–10 million kassabonfraude estimate (2009)** is not a current Dutch fraud-market figure.
- The US **9% return-fraud benchmark** is not the Dutch rate.
- A real receipt does **not** prove legitimate ownership of artwork or products.
- A cryptographically signed record proves the record's integrity/issuer, **not automatically the truth of its contents**.
- The Netherlands already has digital-receipt and document-automation providers. General receipt storage is **not an uncontested opportunity**.
- A four-day AI demo can flag missing or inconsistent evidence, but should **not** promise definitive legal title, VAT compliance, warranty entitlement, or fraud adjudication.

---

## 9. Sources and reading list

Research discussed during our brainstorming drew on the following Dutch official, industry, provider, and consumer sources. Numbers should be **rechecked in the original publications before use in a judged pitch**, particularly if the methodology or survey base matters.

### Payments, retail and receipts

- [De Nederlandsche Bank — *Betalen aan de kassa 2025* (PDF)](https://www.dnb.nl/media/mjsfjw0h/betalen-aan-de-kassa-2025-def.pdf)
- [Betaalvereniging Nederland — Facts & figures](https://www.betaalvereniging.nl/feiten-en-cijfers/)
- [Lightspeed — Research into Dutch hospitality receipts](https://www.lightspeedhq.nl/nieuws/horecabonnetjes/)
- [Consumentenbond — Checkout pricing errors at regional supermarkets (2025)](https://www.consumentenbond.nl/nieuws/2025/te-veel-fouten-op-kassabonnen-regionale-supermarkten)
- [Milieu Centraal — Thermal paper and recycling](https://www.afvalscheidingswijzer.nl/alle-afvalproducten/papier-en-karton/thermisch-papier)
- [Thuiswinkel.org — Returned parcels in the Netherlands](https://www.thuiswinkel.org/vragen/hoeveel-pakketten-worden-er-naar-webwinkels-teruggestuurd-in-nederland/)

### Fraud and expenses

- [INretail — Retail fraud guidance](https://www.inretail.nl/kennisbank/winkelpand/veiligheid/winkelfraude/)
- [Dutch Police — Major return fraud investigation (Dec 2025)](https://www.politie.nl/nieuws/2025/december/3/03-twee-mannen-aangehouden-voor-grootschalige-retourfraude.html)
- [ICS — Manual expense administration in Dutch organizations (2024)](https://www.icscards.nl/zakelijk/nieuws/2024-10-nederlandse-bedrijven-verwerken-declaraties-handmatig)
- [Allianz Trade — Fraud trend report](https://www.allianz-trade.com/nl_NL/nieuws-tips/fraude/fraude-trendrapport.html)
- [FIU-Nederland — Large-scale fraud with false invoices](https://www.fiu-nederland.nl/knowledge_base/grootschalige-belastingfraude-via-valse-facturen/)
- [National Retail Federation — 2025 retail returns landscape (US)](https://cdn.nrf.com/research/2025-retail-returns-landscape)

### Art, evidence and adjacent workflows

- [RKD — Netherlands Institute for Art History](https://rkd.nl/)
- [Art Loss Register](https://www.artloss.com/)
- [Nederlandse Galerie Associatie](https://www.nederlandsegalerieassociatie.nl/)
- [Pictoright — Dutch visual artists' rights](https://pictoright.nl/)
- [Artlogic — Gallery management](https://artlogic.net/)
- [Verisart — Digital certification](https://verisart.com/)
- [RVO — ISDE subsidy](https://www.rvo.nl/subsidies-financiering/isde)
- [Klippa — Document processing](https://www.klippa.com/)
- [Consumentenbond — Consumer rights and warranty information](https://www.consumentenbond.nl/juridisch-advies/garantie-reparatie/garantie-buiten-garantietermijn)

---

## Working conclusion

**Do not begin with “How do we digitize receipts?”** That already has multiple technical solutions. Begin with the operational failure and the owner:

> **What important decision cannot be made quickly, accurately, or fairly because evidence of a transaction, entitlement, ownership or delivery is missing, unreliable or disconnected?**

**Next move:** Validate the three strongest problem-owner candidates (installers/subsidy advisers, purchasing/AP teams, and small art galleries). Choose the first problem for which we obtain **specific recent examples, measurable losses or labor hours, an unsolved workflow, and a plausible buyer**. Only then define a product.

*Prepared as a concise synthesis of our research and brainstorming, not as an independently audited market report.*
