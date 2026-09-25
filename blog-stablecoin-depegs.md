# Stablecoin Depegs: What Actually Happens When a Dollar Isn't a Dollar

*~750 words · writing sample*

---

A stablecoin is a promise: one token, one dollar, always. When that promise breaks — even by a few cents — billions of dollars can move in minutes. These events are called depegs, and understanding them is understanding the plumbing of modern crypto.

## The promise and the peg

Most dollar stablecoins (USDC, USDT) are backed by real reserves: cash, Treasury bills, other safe assets. In theory, you can always redeem one token for one dollar, so the market price stays at $1.00.

Algorithmic stablecoins tried to do it without reserves — pure code, pure confidence. That ended the way you'd expect.

But even reserve-backed stables depeg. USDC traded at $0.87 in March 2023. Not because the reserves vanished — because $3.3 billion of them sat at Silicon Valley Bank, and the market panicked before the facts arrived.

## Anatomy of a depeg

Depegs follow a script:

**1. The trigger.** A bank fails. A custodian freezes. A rumor spreads. Something makes people doubt redemption.

**2. The rush.** Holders sell at any price to exit. On-chain liquidity is thin relative to the panic — a $10 million market sell can move a multi-billion-dollar token if the pools are shallow.

**3. The spiral (sometimes).** If the stablecoin is collateral elsewhere — lent out, locked in vaults, paired in LPs — the depeg cascades. Loans get liquidated. LPs take losses. Each liquidation adds sell pressure.

**4. The recovery (usually).** Arbitrageurs buy the discount and redeem at $1, pocketing the spread. This is the market's self-healing mechanism — and it works when reserves are real. USDC was back at $1 within days.

## Why depegs are a trader's telescope

Watching a depeg in real time teaches you more than a year of bull-market trading:

- **Liquidity is a fair-weather friend.** Depth that looks solid at $1.00 evaporates at $0.95. Always check the book, not the headline number.
- **Redemption > reserves.** What matters isn't what's *in* the vault — it's how fast you can get it *out*. Redemption speed is the real peg.
- **Discounts are information.** A stablecoin at $0.97 isn't "cheap dollars." It's the market pricing a probability. If you can't quantify the risk, you're not arbitraging — you're gambling.

## The checklist before you trust a peg

1. **Attestations, not vibes.** Monthly reserve reports from real auditors. "Trust us" is not a backing mechanism.
2. **Redemption path.** Can *you*, personally, redeem? Or only "authorized partners"? The wider the redemption access, the stronger the peg.
3. **On-chain liquidity depth.** Check the biggest pools. If a $5M sell moves the price 2%, the peg is thinner than it looks.
4. **Where it's reused.** A stablecoin deeply embedded as DeFi collateral depegs harder — liquidations amplify everything.

## The bottom line

Every depeg is the same lesson in different clothes: in crypto, a dollar is only a dollar if someone will hand you one on demand. The peg isn't a property of the token. It's a property of the *exit*.

The next time a stablecoin wobbles, don't ask "will it recover?" Ask "how fast can I redeem, and who's already in line ahead of me?" That question is worth more than any price chart.

---

*Spec work · written from real market mechanics, no client affiliation.*
