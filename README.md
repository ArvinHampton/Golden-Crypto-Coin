# Golden Crypto Coin (GOLDC)

**Public launch home** for Golden Crypto Coin — a deflationary BEP-20 token on BNB Smart Chain with built-in burn and charity routing.

| | |
|---|---|
| **Ticker** | `GOLDC` |
| **Network** | BNB Smart Chain (BEP-20) |
| **Contract** | [`0x7ed52b30ae68463a21994371c3a77d18dd144fc8`](https://bscscan.com/token/0x7ed52b30ae68463a21994371c3a77d18dd144fc8) |
| **Initial supply** | 2,000,000,000 GOLDC |
| **Burned at launch** | 1,000,000,000 GOLDC (sent to `0x0`) |
| **Mechanics** | 1% burn + 1% charity on every transfer |
| **Charity** | [Free the Food](https://giveth.io/project/free-the-food) |
| **Heritage source** | [`GHampton23/Crypto`](https://github.com/GHampton23/Crypto) |

---

## Why Golden Crypto

Golden Crypto Coin is built for transparent, eco-aligned value transfer:

- **Deflationary by design** — 1% of every transfer is burned forever
- **Charity on-chain** — 1% of every transfer goes to Free the Food
- **Open source** — verified contract source in this repo
- **539 Labs stewardship** — public relaunch under [Arvin Hampton / 539 Labs](https://539labs.org)

This is **not** financial advice. Cryptocurrency is volatile and risky. Do your own research. Nothing here is an offer to sell securities.

---

## How to buy (DEX)

1. Open [Trust Wallet](https://trustwallet.com/) or any BSC wallet
2. Go to [PancakeSwap](https://pancakeswap.finance/swap?outputCurrency=0x7ed52b30ae68463a21994371c3a77d18dd144fc8)
3. Connect wallet
4. Swap into GOLDC using contract:
   ```
   0x7ed52b30ae68463a21994371c3a77d18dd144fc8
   ```
5. If the swap fails, raise slippage (historically ~6% minimum)

Add liquidity on PancakeSwap if you want to support depth (and earn LP fees when volume exists).

---

## Contract

- Source: [`contract.sol`](./contract.sol)
- Verified on BscScan (submitted 2021-07-29)
- Charity wallet hard-coded: `0x21e0Ca21F517a26db49Ec8FCf05FCeAbBABe98FA`

---

## Brand assets

Assets live in the heritage repo until mirrored here:

- [GoldenCoin_Circle.png](https://github.com/GHampton23/Crypto/blob/main/GoldenCoin_Circle.png)
- [banner.jpg](https://github.com/GHampton23/Crypto/blob/main/banner.jpg)
- [GoldenCoin.jpg](https://github.com/GHampton23/Crypto/blob/main/GoldenCoin.jpg)

---

## Roadmap (public relaunch)

- [x] Publish canonical GitHub home under ArvinHampton
- [ ] Mirror brand assets into this repo
- [ ] Launch page + clear risk disclosures
- [ ] Stripe rails for **allowed** revenue (merch / membership / 539 Labs tools — **not** token sales)
- [ ] X / community announcement
- [ ] Liquidity health check + listing hygiene

---

## Legal / compliance notes

- Token purchases happen on-chain via DEX, not via Stripe
- Stripe is used only for permitted products (software, merch, memberships) under 539 Labs, LLC
- No guaranteed returns. DYOR.

---

**539 Labs, LLC** · [539labs.org](https://539labs.org) · GitHub: [ArvinHampton](https://github.com/ArvinHampton)
