# PIP Proposal for Settlement (PFS) Strategy Matrix

An internal decision-support tool for setting **§768.79 Proposal for Settlement** amounts in
**new-law Florida PIP cases** (HB 837 — policies issued/renewed on or after 3/24/2023) where the
one-way attorney-fee statute no longer applies and the PFS is the primary path to fees.

## What it does

- Computes the **Max Safe Offer** — 80% of the expected judgment, the ceiling that still lets a
  judgment beat your offer by the required 25% to trigger fees under §768.79.
- Applies a **safety buffer** to recommend an offer below that ceiling.
- Flags each offer **SAFE / TIGHT / FAIL** against the 25% threshold.
- Weighs **expected value of litigating vs. settling** using your win probability and fee/cost estimates.
- Includes a **statutory interest calculator** (Fla. Stat. §627.736(4)(d) / §55.03) with support for
  the annual January-1 rate re-adjustment via multiple rate periods.

## How to use

Open `index.html` in any web browser. Fill in the blue cells; the black cells calculate automatically.
Nothing is sent anywhere — all math runs in the browser, and the file stores no data.

## Disclaimer

Internal decision-support only — **not legal advice.** Verify the current statute, Rule 1.442,
good-faith/specificity case law in your venue, and that the policy is genuinely post-3/24/2023
before serving any proposal. Fee entitlement can be lost on good-faith or specificity grounds even
when the 25% math is satisfied.
