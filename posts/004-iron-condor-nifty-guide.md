---
id: "004"
title: "Iron Condor on NIFTY — a beginner's complete step-by-step guide"
category: "options"
categoryLabel: "Options"
date: "2026-05-08"
readtime: 10
excerpt: "One of the most popular options strategies for sideways markets. Setup, strike selection, max profit, max loss, and when to exit — all covered."
---

The Iron Condor is one of the most popular options strategies among Indian traders — particularly on NIFTY weekly expiries. If you've seen experienced traders talk about "selling range" or "collecting premium in a sideways market," they're often talking about Iron Condors. Here's the complete guide.

## What is an Iron Condor?

An Iron Condor is a four-leg options strategy that profits when the underlying asset (in our case, NIFTY) stays within a defined range until expiry.

You simultaneously:
- **Sell** a higher strike Call
- **Buy** an even higher strike Call (protection)
- **Sell** a lower strike Put
- **Buy** an even lower strike Put (protection)

The result is a position that earns maximum profit if NIFTY expires between your two short strikes — and has defined, limited loss if it moves beyond either side.

## Why do traders love it on NIFTY?

NIFTY spends a significant portion of its time in sideways consolidation — especially in the weeks after large moves. The Iron Condor is designed exactly for this environment. You get paid to wait.

Additionally, NIFTY options are highly liquid, spreads are tight, and weekly expiries give you frequent opportunities to set up fresh positions.

## Setting up an Iron Condor — step by step

Let's use a real example. Assume NIFTY is at **24,000**.

**Step 1 — Define your expected range**
You believe NIFTY will stay between 23,500 and 24,500 for the next week. That's your "safe zone."

**Step 2 — Set up the Call side (upper wing)**
- Sell 24,500 CE (Call) — collect premium, say ₹80
- Buy 24,800 CE (Call) — pay premium, say ₹30
- Net credit on call side: ₹50

**Step 3 — Set up the Put side (lower wing)**
- Sell 23,500 PE (Put) — collect premium, say ₹75
- Buy 23,200 PE (Put) — pay premium, say ₹28
- Net credit on put side: ₹47

**Step 4 — Calculate your numbers**

| Metric | Calculation | Value |
|---|---|---|
| Total premium collected | ₹50 + ₹47 | ₹97 per lot |
| Max profit | Premium collected × lot size | ₹97 × 75 = ₹7,275 |
| Max loss per side | Strike width − premium | (300 − 97) × 75 = ₹15,225 |
| Breakeven upper | Short call + premium | 24,500 + 97 = 24,597 |
| Breakeven lower | Short put − premium | 23,500 − 97 = 23,403 |

## When do you make maximum profit?

If NIFTY expires anywhere between **23,500 and 24,500** — all four options expire worthless and you keep the entire ₹97 premium per lot. With one lot of NIFTY (75 units), that's ₹7,275 profit.

## When do you lose?

**If NIFTY rises above 24,597** — your short call is losing money faster than your long call protects. Maximum loss is hit at 24,800 (your long call strike).

**If NIFTY falls below 23,403** — your short put is losing money. Maximum loss is hit at 23,200 (your long put strike).

The maximum loss is always **limited** — that's the beauty of the Iron Condor vs. naked option selling.

## Strike selection — the most important decision

There's no single "correct" answer, but here are the principles:

**Use implied volatility (IV) as your guide**
- When IV is high (above 15 on NIFTY), sell wider strikes — you collect more premium and have more buffer
- When IV is low (below 12), the premium is thin — Iron Condors are less attractive

**Delta as a guide**
Most professional traders sell strikes at around 15-20 delta on each side. This gives approximately an 80-85% probability that NIFTY stays within your range.

**Respect key levels**
Never place your short strike right at a major support or resistance level. Place it beyond the level so you have a natural buffer.

## When to enter and exit

**Best time to enter:** 7-10 days before expiry, when time decay accelerates. Monday or Tuesday of expiry week is popular among NIFTY traders.

**Exit for profit:** Close the position when you've captured 50-70% of the maximum premium. Don't be greedy waiting for the last few rupees — the risk isn't worth it near expiry.

**Exit for loss (stop loss):** If one side is tested and the premium of that spread doubles, consider closing that side or the entire position.

## Common mistakes to avoid

**Mistake 1 — Setting strikes too close**
Narrow Iron Condors collect more premium but get tested far more often. Give yourself enough room.

**Mistake 2 — Ignoring upcoming events**
Never hold an Iron Condor through a major event — RBI policy, Union Budget, quarterly results season, or global shocks. These events can cause large moves that blow through your strikes.

**Mistake 3 — Not adjusting when tested**
If one side gets tested, you have options — roll the tested side further out, close the losing side, or hedge with a futures position. Don't just hope it comes back.

**Mistake 4 — Overleveraging**
One lot is fine to learn. Many beginners put on 5-10 lots on their first trade and face psychological pressure when the position moves against them.

## Iron Condor vs. Short Strangle

You might wonder: why buy the protective wings? Why not just sell the call and put outright (a strangle)?

| | Iron Condor | Short Strangle |
|---|---|---|
| Max loss | Limited ✅ | Unlimited ❌ |
| Margin required | Lower ✅ | Very high ❌ |
| Premium collected | Lower | Higher |
| Suitable for | Retail traders | Experienced only |

For most retail traders, the Iron Condor is the right choice.

## Summary

The Iron Condor is one of the most elegant strategies in options trading — defined risk, defined reward, and it profits from time passing when markets are calm. Master it on paper first, then deploy it with one lot on NIFTY, and gradually build experience before scaling up.

---

*Disclaimer: Options trading involves significant risk and is not suitable for all investors. This article is for educational purposes only. Please consult a SEBI-registered advisor before trading options.*
