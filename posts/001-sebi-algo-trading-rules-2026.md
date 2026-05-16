---
id: "001"
title: "SEBI's algo trading rules in 2026 — what every retail trader must know"
category: "algo"
categoryLabel: "Algo Trading"
date: "2026-05-14"
readtime: 12
excerpt: "SEBI has fundamentally changed how retail investors can use automated systems. This comprehensive guide breaks down the new framework in plain English."
---

If you've been following Indian markets, you've probably heard about SEBI's crackdown on retail algorithmic trading. But most of the coverage has been either too technical or too vague. This article cuts through the noise and tells you exactly what changed, what it means for you, and what you can still do legally.

## What triggered the new rules?

SEBI's concern was straightforward: retail traders were accessing powerful algorithmic tools through brokers and third-party platforms — tools that were never formally approved or tested. This created an uneven playing field and, in some cases, market manipulation risks.

The result was a circular that fundamentally changed how algos must be registered, tested, and deployed.

## What changed — the key points

### 1. All algos must be approved by SEBI

Any automated strategy that places orders without manual intervention must now be:
- Submitted to the exchange (NSE/BSE) for approval
- Tested in a sandbox environment first
- Tagged with a unique algo ID on every order

This applies to both proprietary algos and third-party tools offered by brokers.

### 2. Brokers are now accountable

Previously, if a third-party tool caused problems, accountability was murky. Now brokers are directly responsible for every algo their clients run. This means brokers are much more careful about which platforms they allow.

### 3. The "API trading" grey area is gone

Many retail traders were using broker APIs to effectively run algos without formal approval. SEBI has explicitly addressed this — API-based order placement is now treated as algorithmic trading and must follow the same approval process.

## What you CAN still do legally

Here's the good news — there's plenty you can do:

> **Rule-based trading on approved platforms** like Streak (on Zerodha), SmallCase, and similar SEBI-compliant tools is completely legal. These platforms have already gone through the approval process on your behalf.

**Approved activities include:**
- Building and running strategies on Streak
- Using scanner alerts (ChartInk, TradingView alerts) to get notified — then placing orders manually
- Paper trading any strategy using any tool
- Backtesting using historical data tools like Amibroker or Python

## What you CANNOT do without approval

- Running a Python/Pine Script bot that places live orders automatically
- Using any unapproved third-party tool that auto-executes trades
- Sharing or selling algos to other traders without exchange approval

## How to get your algo approved (the process)

If you do want to run a custom algo, the path is:

1. **Develop and document** your strategy with full logic
2. **Backtest** it and prepare performance reports
3. **Submit to your broker** — they apply to the exchange on your behalf
4. **Sandbox testing** — the exchange tests it in a controlled environment
5. **Get the Algo ID** — once approved, every order carries this ID
6. **Go live** — only after all of the above

The process typically takes 4-8 weeks and requires technical documentation most retail traders find challenging. This is why approved platforms like Streak are the practical path for most people.

## The AlgoJinn take

SEBI's intent here is actually good — protecting retail traders from unregulated, potentially manipulative tools. The casualty is the "code your own bot" dream that many retail traders had.

But here's our perspective: **most retail traders who were running unsophisticated algos were losing money anyway**. The discipline of rule-based thinking — defining your entry, exit, and position sizing clearly — is more valuable than the automation itself.

That's exactly what we focus on at TheAlgoJinn. Think like an algo. You don't have to be one.

## Summary

| What | Status |
|---|---|
| Approved platform algos (Streak etc.) | ✅ Fully legal |
| Manual trading with scanner alerts | ✅ Fully legal |
| Backtesting & paper trading | ✅ Fully legal |
| Custom API bots without approval | ❌ Not allowed |
| Unapproved third-party auto-execution | ❌ Not allowed |

---

*Disclaimer: This article is for educational purposes only and does not constitute legal or financial advice. Always verify regulatory requirements with SEBI's official circulars or a qualified professional.*
