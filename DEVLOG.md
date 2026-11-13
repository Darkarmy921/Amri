# Dev Log

Daily log of security research and agent work.

## 2026-11-09

- Immunefi account created (username `amri`): email verified, 2FA on, Discord connected, payout wallet verified. Identity verification in progress (Human Passport score 22.1/25).
- XE testnet bug bounty: 37 reports filed, all still NEW; status watch checks every 2h.
- Chainlink bug bounty recon round 1: 4 findings drafted (CCIP, Core Node, External Adapters, DataFeedsCache). Submission waits on identity verification.
- Started daily commits for GitHub Passport stamps: day 2/30 toward Regular Contributor.

## 2026-11-10

- XE testnet bug bounty: 12 reports awarded (1,920 XE total); 13 more closed as duplicates; 20 still queued. Status watch continues every 2h.
- CodeRabbit bug bounty round 2: several leads refuted with evidence (stored XSS, session hygiene, API org scoping); org B test workspace re-onboarded and free trial activated; zero verified findings so far.
- Relay bug bounty: second finding report submitted with follow-up; awaiting triage.
- Daily commits for GitHub Passport stamps: day 3/30 toward Regular Contributor.

## 2026-11-11

- RAAC Guardian Defender bounty contest: hunt authorized; recon rounds 1-2 complete — one candidate Critical (H1: StabilityPool liquidation shortfall not socialized, 23.27% per liquidation, 93.11% after 4; PoC-confirmed) and one High refuted end-to-end (H2 phantom liquidity). Dedup vs Guardian's 30-finding security review cleared (H1 not covered); report draft reframed and submission-ready; submission waits on account setup.
- HackerOne Airbnb: APK static analysis complete (zero verified findings); deeper AI-assistant probes as host refuted 5/5.
- Pearl PoW mining: gate open with 74.17 PEARL reward available, but blocked on low agent-wallet BNB (0.00029, below the 0.0006 minimum).
- Daily commits for GitHub Passport stamps: day 4/30 toward Regular Contributor.

## 2026-11-12

- RAAC Guardian Defender bounty contest: H1 Critical submission sent (StabilityPool liquidation shortfall, 23.27% per liquidation); status Pending, KYC approved; status watch checks every 2h.
- BAgent free mining: 07:00 reset attempt blocked — quote endpoint now requires 5 paid shares to unlock block mining (paywall verified in the site's own code); free-only retry scheduled for 2026-11-13 with the fastmint driver fixed (quote-error logging, late-start bug).
- Agent Cards #4203: daily quests complete, earned level 14, synced on-chain 12 → 14.
- Daily commits for GitHub Passport stamps: day 5/30 toward Regular Contributor.

## 2026-11-13

- make.fun tiny-chess-01: engine v1 submitted (4,087-byte Python chess engine, PVS + PeSTO eval, 90k nodes/move); server practice grade 1,173 Elo, entry is in the final (floor 1,154). Optimization continues in a fresh session: v4 (endgame king table) built, v5 (TT mate-score ply normalization) regression-tested; v3/v4 regression isolation and node-budget A/B tests running; no v2 submission yet.
- BAgent free mining: 2026-11-13 free retry still blocked by the same 5-paid-shares paywall (3rd morning running); user stopped the daily mining schedule — no more attempts unless restarted.
- Agent Cards #4203: daily quests complete (+843 XP), earned level 14 → 16, synced on-chain 14 → 16.
- RAAC Guardian Defender bounty contest: H1 Critical still Pending; status watch continues every 2h.
- Daily commits for GitHub Passport stamps: day 6/30 toward Regular Contributor.
