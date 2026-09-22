# Harvey — Portfolio of working software

Every item below is built, tested, and runnable. No mockups, no claims without proof.

## 1. Excel/CSV cleaner micro-service — Rs299/job
- Trims, normalizes dates (DD/MM/YYYY-first for India) and ₹ amounts, removes
  empty/duplicate rows, writes `clean.csv + report.csv` flagging every bad row.
- Verified: unit tests pass; demo `5 messy rows → 4 clean + 1 flagged`.
- Stack: Python stdlib only (no installs, runs offline on shop PCs).

## 2. GST invoice + UPI kit — Rs399 one-time
- `items.csv → printable A4 invoice HTML + summary CSV` for the CA.
- CGST/SGST or IGST, discount, round-off (Decimal, no float errors), UPI payment
  string on the bill. GSTIN optional.
- Verified: 5/5 acceptance cases pass (236.00 / 236.00 / 1320.00 / 0.00 / 118.00).

## 3. Target project types (quoting now)
- Python Excel automation & reporting scripts
- Excel → DB/CRM data migration with exception reports
- Billing/invoice tooling for micro-businesses
- Catalog/order sheet systems for food & retail SMBs

## Proof of delivery process
1. Sample input agreed with client. 2. Test output returned for verification.
3. Full delivery + README. 4. Pay only if useful.

## Contact
Open an issue with your file attached. Same-day turnaround.
