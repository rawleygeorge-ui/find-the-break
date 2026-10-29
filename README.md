# Find the Break

**A three-round reconciliation puzzle. Can you spot every mismatch between the books and the bank before the clock runs out?**

▶ **Play it:** https://rawleygeorge-ui.github.io/find-the-break/

You get the company ledger on one side and the bank statement on the other. Most lines match, but some don't. Flag every line that's part of a break, then hit **Reconcile**.

## The breaks you'll meet

| Break | What it looks like | Why it matters |
|---|---|---|
| Transposed amount | 4,580.00 in the books, 4,850.00 at the bank | A keying error. The difference is always divisible by 9. |
| Missing from bank | In the ledger, not on the statement | A deposit in transit, or money that was never banked |
| Missing from books | On the statement, not in the ledger | Bank charges or receipts nobody posted |
| Duplicate posting | The same entry twice in the ledger | The balance is overstated |
| Wrong side | A payment booked as a receipt | Swings the balance by twice the amount |
| Short receipt | The bank shows less than the invoice | The customer short-paid or a fee was deducted |

After each round, the game explains every break you found or missed.

## Scoring

- +100 for each break found
- −50 for each clean line flagged
- Speed bonus when you find all the breaks in a round

## About

Built by **[Rawley George](https://www.linkedin.com/in/rawley-george-884547272)**, a finance operations and automation professional.

The game is one HTML file with no dependencies and no tracking. All names and amounts are randomly generated.

© 2026 Rawley George · Designed by rawsploit@gmail.com
