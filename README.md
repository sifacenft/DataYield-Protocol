
# 💎 DataYield Protocol

Own your data.
Yield from it.
Platforms took the value.
Now take it back.

## 🛡️ Privacy Architecture

Privacy is structural, not optional.

### Core Guarantees

- Only the data owner decides what is shared
- Buyers receive only the minimum required information
- Data cannot be linked across sales without explicit consent

### How it works

1. User creates a **Private Commercial Identity** (PCI)
2. Merchants issue signed attestations of purchases
3. User claims attestations into their PCI (encrypted)
4. When fulfilling a data request, the user generates a **Zero-Knowledge Proof**
5. Only the requested attributes are revealed

**Example proofs:**
- “I made at least 3 purchases in Electronics in the last 90 days”
- “My total Fashion spend in Q2 was between $200–$500”
- “I am a repeat customer of Merchant X above a certain lifetime value”

Raw data never leaves the user’s device.

---

## 🛍️ Merchant Integration (Web2 Stores)

Designed for simplicity.

### Level 1 – Low Code (Recommended)
Add a lightweight JavaScript snippet or use the official SDK.

### Level 2 – Server-side
Send a signed webhook / API call (Shopify, WooCommerce, custom).

### Level 3 – Native
Direct interaction with Solana programs.

```javascript
import { DataYield } from "@datayield/sdk";

await DataYield.attestOrder({
  orderId: "ORD-12345",
  amount: 149.99,
  currency: "USD",
  items: [...],
  timestamp: Date.now(),
  merchantSignature: signedPayload
});
```

---

## 🪙 Token: $OWNY

| Parameter | Value |
|---------|-------|
| **Name** | DataOWNYield |
| **Ticker** | $OWNY |
| **Max Supply** | 1,000,000,000 (Fixed) |

### Utilities
- Fee discounts for data buyers
- Reward boosts for data providers
- Governance
- Staking for reputation weight

### Value Accrual
A large majority of protocol fees are used for **automated buyback & burn** of $OWNY.

More real data volume → Higher protocol revenue → Stronger buybacks → Reduced supply.

---

## 🎯 Points System & Genesis Airdrop

A multi-season Points system will run before TGE to reward real contribution:

- Verified data contribution
- Successful request fulfillment
- Demand-side activity
- Consistent participation
- Privacy-preserving behavior

Early seasons receive significant multipliers.  
A substantial portion of total supply is reserved for the **Genesis Airdrop**.

---

## 🚀 Early Private Contribution Phase (30 Days)

Before the full public launch, a limited private contribution window is open.

- **Duration:** 30 days
- **Target:** Minimum $100,000 USDC (or SOL equivalent)

**Solana Address:**

```text
5PwmQw3kyLKa2WF5G3Nd4eymSN2AkkjRBctGZwg1bEM6
```

Early contributors receive elevated Points multipliers (up to **3.5×** in the first 7 days) and priority in the Genesis Airdrop.

> This phase exists solely to fund initial development, audits, and liquidity bootstrap.  
> No guarantee of return is provided. All contributions are publicly visible on-chain.

---

## 🌊 Why Solana?

- Sub-second finality
- Extremely low fees
- High throughput
- Strong consumer & DeFi ecosystem
- Perfect for micro-settlements and high-frequency data interactions

---

## 🗺️ Roadmap

| Phase | Timeline | Focus |
|------|----------|-------|
| Phase 0 | Days 1–30 | Private contribution + Core development |
| Phase 1 | Month 2 | Public GitHub + Testnet + Season 1 Points |
| Phase 2 | Months 3–5 | Mainnet Beta + Seasons 2 & 3 |
| Phase 3 | Month 6–7 | TGE + Full Marketplace Launch |

---

## 🤝 Contributing

We welcome contributors.

Please read `CONTRIBUTING.md` before submitting pull requests.

---

## 📄 License

This project is licensed under the **MIT License**.

---

