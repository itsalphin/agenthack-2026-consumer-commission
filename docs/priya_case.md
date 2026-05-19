# Priya's Case — North-Star Demo Scenario

Every design decision in this project should pass the test:
**does this make Priya's case work better?**

## The user

| Field | Value |
|---|---|
| Name | Priya Krishnan |
| Age | 28 |
| Occupation | Software engineer |
| Location | Chennai, Tamil Nadu |

## The dispute

| Field | Value |
|---|---|
| Product purchased | OnePlus Nord CE 4 (256GB, Celadon Marble) |
| Purchase price | ₹14,499 (incl. taxes) |
| Purchased from | Flipkart (sold by RetailNet via Flipkart Marketplace) |
| Purchase date | March 12, 2026 |
| Payment method | UPI via PhonePe — txn ID T2503124... |
| Delivery date | March 14, 2026 |

## What went wrong

- **Problem:** On unboxing, screen showed cluster of dead pixels in upper-right quadrant
- **First action:** Filed return request via Flipkart app same day (March 14)
- **Flipkart response:** March 15 — return rejected. Reason: "Quality check found no defect."
- **Follow-up:** Called Flipkart customer service 4 times over 5 days. Promised callbacks never came.
- **Final escalation:** Sent email to grievance@flipkart.com on March 19. No response after 14 days.

## Evidence Priya has

1. Order confirmation PDF
2. UPI payment screenshot
3. Two photos of the defective screen (well-lit, clear)
4. Screenshot of rejected return request
5. Email thread with grievance@flipkart.com
6. Call log screenshots showing 4 calls

## Relief sought

| Item | Amount |
|---|---|
| Full refund of phone | ₹14,499 |
| Compensation for harassment + time lost | ₹10,000 |
| Litigation cost | ₹2,500 |
| **Total** | **₹26,999** |

## Legal framework

- **Forum:** District Consumer Disputes Redressal Commission, Chennai (jurisdiction up to ₹50 lakh)
- **Limitation period:** 2 years from cause of action — well within
- **Legal grounds:**
  - Deficiency in service under Consumer Protection Act 2019, Section 2(11)
  - Unfair trade practice under Section 2(47)

## Expected outputs from each agent

### Agent 1 (Intake & Drafting) should produce:
- Properly formatted complaint citing CPA 2019 Section 2(11)
- Correct jurisdiction (DCDRC Chennai)
- All three relief items listed
- Limitation period confirmed as within 2 years
- Parties correctly named (Priya as Complainant, Flipkart + RetailNet as Opposite Parties)

### Agent 2 (Evidence Packager) should produce:
- 6 numbered exhibits (Exhibit P-1 through P-6)
- Each exhibit classified correctly (Invoice, Payment, Photo, etc.)
- Extracted data: amount, transaction ID, dates
- Confidence > 0.7 on at least 4 of 6 files
- Flag any low-confidence files for human review

### Agent 3 (Filing) should produce:
- Validated inputs check passes
- e-Daakhil RPA invoked
- Captcha handed off to user via Action Center
- Real case number returned from portal
- Filing receipt saved to storage
