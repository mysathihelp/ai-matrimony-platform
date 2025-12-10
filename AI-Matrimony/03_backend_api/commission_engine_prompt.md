# Commission Engine & Payout Automation

Rules:
- Meeting Fee: ₹2000 (₹2500 for free user)
- Tier %: 50/60/70 (T1/T2/T3)
- Marriage Fee: ₹10,000 split same way

APIs:
- /commission/calc
- /commission/finalize
- /payouts/export

Logic:
- Hold in escrow 7 days
- Monthly payout job 1st–5th
- Admin manual adjustments allowed
