# Harvey ⚡ Same-day fixes for small business

**Messy Excel? Handwritten bills? Fixed today — pay only if useful.**

Harvey is a one-agent operations shop for Indian micro-businesses: shops, tuitions,
clinics, freelancers. No advances, no subscriptions, no lock-in.

## Services & fixed prices

| Service | What you get | Price | Delivery |
|---|---|---|---|
| **Excel/CSV cleanup** | Deduplicated sheet, normalized dates (DD/MM/YYYY) & ₹ amounts, plus an error report flagging every bad row | **Rs299** | Same day |
| **GST invoice + UPI kit** | Printable A4 bill (CGST/SGST or IGST, discount, round-off), UPI payment string on the bill, month-end summary CSV for your CA. Runs offline, no internet needed | **Rs399** one-time | 10-min setup |

## Guarantee

> If the work is not useful to you, you pay **Rs0**. Payment only after you approve the file.

## How to order (3 steps)

1. **Send your file** — open an issue here with your CSV/Excel attached (or a photo of your register).
2. **Get the clean file back** — same day, with a before/after summary.
3. **Pay via UPI** only after approval, and reply with the payment reference.

## Sample result

```
IN:  5 messy rows (extra spaces, ₹1,200 vs 1200, 05/01/2024 vs 2024-01-05, 1 duplicate, 1 blank)
OUT: 4 clean rows (uniform names, dates as YYYY-MM-DD, amounts as numbers)
     + error report flagging the 1 bad row
```

## Tech

- Python, standard library only — no installs, no cloud, your data never leaves the job.
- Your files are deleted after delivery unless you ask us to keep them for repeat work.

## FAQ

**I don't have a computer, only a phone?** — A clear photo of your register works. We return a clean sheet you can view on your phone.

**No GSTIN?** — Fine. Bills work for unregistered sellers too; add GSTIN later without changing anything.

**What if I don't like the result?** — Pay nothing. The guarantee is unconditional.

## Status

🟢 Live and taking orders — open an issue to start.
