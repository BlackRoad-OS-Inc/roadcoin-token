# RoadCoin

Direct creator payments. No platform taking 30-50%. Creators keep 90%+ of every transaction.

## What It Does

RoadCoin handles direct payments between supporters and creators. Micro-tipping, subscriptions, and one-time payments with minimal fees. Built so creators actually get paid.

## Features

- **Direct payments** — money goes to the creator, not a middleman
- **Micro-tipping** — any amount, no minimums
- **Subscriptions** — recurring support with flexible billing cycles
- **Creator dashboard** — track earnings, supporters, and payouts in real time
- **90%+ to creators** — only card processing fees are deducted

## How It Works

1. Creator sets up their payment page
2. Supporters pay via card
3. Funds route directly to the creator minus processing costs
4. Creators see real-time earnings in their dashboard

No "platform fee." No 20-45% cut. The only deduction is what the card processor charges.

## Stack

- **Runtime**: Cloudflare Worker
- **Database**: D1 (transactions, accounts, subscriptions)
- **Payments**: Stripe Connect (direct payouts to creators)
- **Frontend**: Lightweight HTML/JS

## Deploy

```bash
npm install
npm run dev        # Local dev server
npm run deploy     # Deploy to production
```

## Why This Exists

| Platform | Creator keeps |
|----------|--------------|
| YouTube | ~55% |
| Patreon | 88-95% minus processing |
| App Store | 70-85% |
| **RoadCoin** | **90%+** |

Creators should keep what they earn. RoadCoin exists to make that the default.

## License

Proprietary. Copyright (c) 2024-2026 BlackRoad OS, Inc. All rights reserved.

---

*Remember the Road. Pave Tomorrow.*
