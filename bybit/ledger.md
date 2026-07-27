# Bybit Ledger

## Wallet Summary

| Currency | Balance | Last Updated |
|----------|---------|--------------|
| IDR (Unified Trading) | 400,087 | 2026-07-25 |
| ETH (Unified Trading) | 0.00289 | 2026-07-25 |

---

## Transaction Ledger

| Date | Type | Amount (IDR) | Fee | Notes |
|------|------|--------------|-----|-------|
| 2026-07-22 | Transfer In | +500,000 | 3,000 | Main account → Subaccount (Funding). Fee deducted from main account side. |
| 2026-07-22 | Internal Transfer | — | — | Funding → Unified Trading Account |
| 2026-07-23 | Buy ETHIDR | 99,913 | 100 | 0.00289 ETH @ 34,572,010, Entry Price: 34,572,010 |

---

## IDR Cash Flow

| Date | Description | In | Out | Balance |
|------|-------------|----|-----|---------|
| 2026-07-22 | Transfer from Main Account | 500,000 | — | 500,000 |
| 2026-07-22 | Move to Unified Trading | — | 500,000 | 0 |
| 2026-07-22 | Received in Unified Trading | 500,000 | — | 500,000 |
| 2026-07-23 | Buy 0.00289 ETH @ 34,572,010 | — | 100,013 | 399,987 |

---

## Notes

- **Account type:** Standard Subaccount on bybit.id
- **API endpoint:** `api.bybit.id`
- **Trading:** Spot only (no leverage/derivatives on bybit.id)
- **Fees:** 0.10% maker / 0.20% taker on IDR pairs
- **IP whitelisted:** 43.128.118.178
