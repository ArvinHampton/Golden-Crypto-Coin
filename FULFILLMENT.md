# Founders Pack fulfillment (manual)

Zero-budget ops runbook. Digital goods only. Not a token sale.

**Product:** Golden Crypto Founders Pack — `$29`  
**Buy link:** https://buy.stripe.com/dRmaEWcJeaXt38N0BjbEA02  
**Stripe (livemode):** product `prod_VFEtjI700dsgw5` · price `price_1UEkPPCQLkwPXwCzABV6I6E2` · payment link `plink_1UEkPUCQLkwPXwCzlZPpXqsw` · account `acct_1TlM9DCQLkwPXwCz`  
**Pack zip (box):** `/workspace/goldc-founders-pack/Golden-Crypto-Founders-Pack.zip`

## What the buyer gets

Zip contains:

- `Golden-Crypto-Founders-Brief.pdf` — launch brief + roadmap
- `brand/` — logo / banner / `BRAND.md` (heritage assets)

They also join the founders update list (manual: keep their email).

## When a payment comes in

1. **Detect paid checkout**
   - Stripe Dashboard → Payments (or Checkout Sessions), livemode.
   - Filter for Founders Pack / amount `$29.00` / metadata `project=goldc` + `offer=founders_pack` when present.
   - Or payment link `plink_1UEkPUCQLkwPXwCzlZPpXqsw`.
   - Confirm status **Succeeded** / **Paid** (ignore unpaid/expired sessions).
2. **Copy buyer email + name** from the Stripe payment / customer details.
3. **Email the zip** from Arvin’s usual mailbox (Gmail/Telegram follow-up OK if they wrote you there first).
   - **To:** buyer email from Stripe
   - **Subject:** `Your Golden Crypto Founders Pack`
   - **Attach:** `Golden-Crypto-Founders-Pack.zip`
   - **Body template (copy/paste):**

```
Hi {name},

Thanks for grabbing the Golden Crypto Founders Pack.

Attached is your zip:
- Launch brief + roadmap PDF
- Brand asset pack (logo / banner)

You're on the founders update list — occasional product notes only.

This purchase is digital goods only. It is not a token sale, not investment advice, and does not include GOLDC tokens or DEX liquidity. Current heritage liquidity is near-zero.

Site: https://arvinhampton.github.io/Golden-Crypto-Coin/
GitHub: https://github.com/ArvinHampton/Golden-Crypto-Coin

Questions → Telegram @ArvinHampton

— Arvin
```

4. **Log it** (simple sheet or note):
   - date · Stripe payment id · email · emailed? Y/N · notes
5. **Reply once** if they ask for a re-send; do not over-promise liquidity or returns.

## Guardrails

- Do **not** send tokens, seed phrases, or “allocation” language.
- Do **not** mix this with 539 Labs HQH / investor-researcher outreach.
- Do **not** claim tradability while liquidity is near-dead.
- Stay zero-budget: no paid email automation required; Stripe receipt is automatic, pack delivery is manual.

## Quick morning check

1. Stripe livemode → any new **Paid** Founders Pack charges?
2. If yes → email zip within a few hours.
3. If no → push free announce copy from `ANNOUNCE.md` (personal / GOLDC channels only).
