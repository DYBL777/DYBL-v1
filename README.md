# DYBL - Decentralised Yield Bearing Legacy

**"The Eternal Seed"** — A Self-Sustaining Compounding Primitive for Recurring Payments

---

## The Problem

Every lottery resets to zero after a jackpot. Prize pools drain completely. Start over.

Every subscription payment disappears. No compounding. No shared upside.

## The Solution

**The Eternal Seed** — a configurable percentage of every payment is retained forever.

Under normal operating conditions, the pot floor only rises. A new primitive for yield generation.

---

## How It Works For Lettery

| Source | Effect |
|--------|--------|
| **Eternal Seed** | Set % never paid out, accumulates forever |
| **Ticket Sales** | 65% of every ticket adds to pot |
| **Jackpot Rollovers** | No winner = stays in pot |
| **Aave Yield** | Seed compounds via DeFi |
| **Forfeit Yield** | Broken streaks → 50% to pot |

*Note: Not immune to smart contract risk, protocol exploits, or stablecoin depegs. See Risks section.*

---

## Tech Stack

- **Solidity** ^0.8.24
- **Chainlink VRF** — Provably fair draws
- **Aave V3** — Yield generation
- **Architected for V2:** Truflation / Chainlink Automation — Dynamic treasury management

---

## Key Features

✅ **Eternal Seed** — Pot floor only rises (under normal conditions)

✅ **Yield-bearing savings** — Users earn while they play

✅ **Pavlov Toggle (V2)** — Savers: 100% yield + 100% cashback. Gamblers: yield as tickets + reduced cashback. Game favours savers.

✅ **Legacy Mode** — Set an heir, pass on your balance

✅ **Meme Alphabet** — 42 characters, viral potential

✅ **1-Year Lock** — Prevents gaming as free yield account

✅ **Mulligan** — One free missed week per year

---

## Contract

📄 **Lettery_AuditReady_v1.3.sol** — Current version (audit-ready)

📄 **archive/** — Previous versions (v1.0, v1.2)

The 7-part mechanism explanation is in the contract header — designed for auditor readability.

---

## Documentation

📄 [DYBL Whitepaper](./DYBL%20WHITEPAPER.md)

📄 [Changelog](./docs/CHANGELOG_BugFixes.md)

---

## Risks

⚠️ **This is experimental DeFi.** Risks include:

- Smart contract vulnerabilities (not yet professionally audited)
- Aave protocol dependency (liquidity, exploits)
- USDC stablecoin risk (depeg)
- Chainlink VRF dependency

**Status:** Seeking audit from Cyfrin / Chainlink ecosystem partners.

---

## V1.3 Changelog

- ✅ Removed `depositSavings()` — All users must buy tickets to participate
- ✅ Clarified saver/gambler toggle (V2 feature)
- ✅ Honest risk assessment in documentation

See full changelog in contract header.

---

## License

**BUSL 1.1** — Business Source License

**Change Date:** 10 May 2029

**After Change Date:** MIT

---

## Contact

**DYBL Foundation** 🇬🇧 UK

📧 dybl7@proton.me

🔗 [GitHub](https://github.com/DYBL777/DYBL-v1)

---

**Not a fork. A new DeFi primitive.**

*Today's seed becomes tomorrow's fortune.*
