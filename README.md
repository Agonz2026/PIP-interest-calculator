# PIP Statutory Interest Calculator

Internal presuit tool for **The Law Offices of Gonzalez & Associates** to calculate statutory
interest on overdue Florida PIP benefits under **Fla. Stat. §627.736(4)(d)** and **§55.03**.

## What it does

- Computes **simple** statutory interest on overdue PIP benefits.
- Auto-splits the timeline at each **January 1** (the PIP rate re-adjusts annually until paid) and
  fills in the correct **§55.03 rate** for each period from the official Florida CFO table.
- Shows days overdue, interest, and total demand (principal + interest).
- **Print / Save as PDF** produces a clean breakdown to attach to a demand letter.
- Every rate cell is editable for edge cases; a §55.03 rate reference is built in.

## How to use

Open `index.html` in any web browser. Enter the overdue benefit amount, the date interest begins
(written notice of the covered loss), and a through date, then click **Auto-build periods**.

## Files

- `index.html` — the calculator (open this).
- `logo.png` — firm logo shown in the header. **Add your logo file here named `logo.png`**; until
  then the header shows a placeholder.

## Rates

§55.03 rates are simple interest as published by the Florida CFO (table current through Q3 2026).
Verify any quarter after the last table entry against the official CFO page before relying on it,
and use the contract rate if it is higher than the statutory rate.

## Disclaimer

Internal decision-support only — **not legal advice.** Confirm the applicable rate, the date
interest begins, and current statutory authority before using output in a demand or filing.
