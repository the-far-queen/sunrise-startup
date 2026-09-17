# Content Axes — Stocks

> **Bobby Wolfson + Hermes, 2026-09-17.** Content-axis schema for
> structured content generation in this domain. Mirrors the
> `far-art` 56-axis style schema — axes are the contract, vibe is not.
>
> **Use case:** when generating content (articles, posts, scripts,
> briefings) in this domain, use these axes as the gate. Each asset
> declares its axis coverage. Naked assets (no axis coverage) are
> refused.
>
> **Converted to markdown from the original HTML table.**
> **Total axes:** 32.

## Why this schema exists

To stop one-shot content generation. "Write about crypto" is not an
axis. The 32 axes below are the load-bearing structure. Use
them.

## Schema (the contract)

| # | Axis | What It Covers |
|---|---|---|
| 1 | **Valuation** | P/E, P/S, PEG ratio — cheap or expensive relative to history/peers |
| 2 | **Earnings/Revenue Growth** | Trend direction, not a single quarter's number |
| 3 | **Chart/Technical** | Trend structure, volume-confirmed breakouts, key moving averages |
| 4 | **Balance Sheet Health** | Debt load, cash reserves, free cash flow |
| 5 | **Dividends & Buybacks** | Yield trend, payout ratio, repurchase pace |
| 6 | **Competitive Moat** | Pricing power, switching costs, network effects |
| 7 | **Management Quality** | Capital allocation track record, insider buying/selling |
| 8 | **Sector Positioning** | Where it sits in its industry's growth/decline cycle |
| 9 | **Macro Sensitivity** | Interest-rate exposure, inflation exposure, cyclicality |
| 10 | **Institutional Ownership** | 13F trends, hedge fund positioning |
| 11 | **Options/Volatility** | Implied volatility trends, historical beta |
| 12 | **Regulatory/Legal Risk** | Antitrust, litigation exposure |
| 13 | **Broker/Custody Security** | Account protection, SIPC insurance, 2FA |
| 14 | **Tax Treatment** | Long vs. short-term capital gains, dividend tax categories |


## How to use this schema

1. **At intake** — when the user asks for content in this domain, list
   which axes will be covered.
2. **At draft** — the content must actually address the claimed axes.
   Don't claim "Earnings/Revenue Growth" if the draft has no earnings
   data.
3. **At review** — run the Atlas-style 5-item check:
   - **Coverage**: do all claimed axes have content?
   - **Fidelity**: are claims sourced (primary > secondary)?
   - **No-house-style**: is the content in the user's voice, not the
     generic assistant voice?
   - **No-slop**: no generic phrasing, no padding, no TM woes.
   - **Audience-fit**: is the content for the named audience?

## Anti-patterns

- One-shot generation without axis coverage.
- Generic assistant voice.
- TM / copyrighted material without source.
- Padding to hit word count.
- "Make it punchy" / "Make it epic" without axis.

## Sister repos

- [the-far-queen/far-art](https://github.com/the-far-queen/far-art) —
  the original 56-axis style schema (Medium, Mark, Space, Light,
  Language, Citation, Pipeline).
- [the-far-queen/sunrise-startup](https://github.com/the-far-queen/sunrise-startup) —
  this repo (public face).

## License

MIT. Free for all agents, human and non-human.
