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

## 2026-11-14

- make.fun NVIDIA CEO forecast: v3 submitted 00:59 WIB (asymmetric 75% quantile), dev score 0.267404, place 791 (v2 was 0.275636, place 1151); entries closed 04:00 WIB, v3 is the final entry; final result due 2026-11-30.
- make.fun BTC trading bot race (24h) started as @lucky-condor-19: $250 pot, simulation only, deadline 12:14 WIB; bot build in progress in a fresh session.
- Agent Cards #4203: daily quests complete (+744 XP), earned level 16 → 17; on-chain still 16, sync pending user approval.
- SpectroCoin: user confirmed no assets there; Round 2 closed as moot. Round 1 F1 unaffected.
- XE testnet bug bounty: XE-1793 reopened from closed-duplicate to triaging; 12 awarded (1,920 XE total), 19 triaging, 3 queued.
- Pearl PoW mining: mine #7 ready (74.04 PEARL) but blocked on low agent-wallet BNB (0.00059307, below the 0.0006 minimum).
- Daily commits for GitHub Passport stamps: day 7/30 toward Regular Contributor.

## 2026-11-15

- XE testnet bug bounty: XE-1730 and XE-1788 moved from new-queued to triaging; XE-1790 closed invalid; 12 awarded (1,920 XE total), 21 triaging, 0 queued.
- Agent Cards #4203: daily quests complete (+828 XP), earned level 17 (831/841, 10 XP short of 18); synced on-chain 16 → 17.
- make.fun BTC trading bot race: race window ends 12:29 WIB today; v1 is the final entry (dev grade +$6.03 net PnL, gate passed); official result due 2026-12-07.
- Pearl PoW mining: mine #7 ready (73.99 PEARL) but still blocked on low agent-wallet BNB (0.00059, below the 0.0006 minimum).
- Daily commits for GitHub Passport stamps: day 8/30 toward Regular Contributor.

## 2026-11-16

- make.fun best-game-01: NOVA SWARM submitted and accepted as @lucky-condor-19 (05:47 WIB); all server checks pass; final starts 2026-11-18, result due 2026-12-03.
- Agent Cards #4203: daily quests complete (+664 XP), earned level 17 → 18; synced on-chain 17 → 18 (gas only).
- make.fun free-model-aggregator-01: v2 evaluation closed on 1,000-seed evidence (P(exactly 20 calls) v2 3.4% vs v1 3.6%, statistically identical) — v1 kept as the final entry, no replacement.
- make.fun tiny-chess-01: from-scratch rebuild complete (4,094 bytes, self-play vs v3 4-0); isolation matches finished — move-order golf wins clearly, endgame king table loses; compressed opening book is the next priority.
- Daily commits for GitHub Passport stamps: day 9/30 toward Regular Contributor.

## 2026-11-17

- make.fun markdown-render-speed-02: entries closed 03:30 WIB with no user submit approval, so the entry did not enter the competition despite the verified push (720/720 byte-for-byte match vs marked 18.1.3, ~10-12% faster); repo and code remain as-is.
- Pearl PoW mining: mine #7 ready (~73.92 PEARL, gate open all day) but still blocked on low agent-wallet BNB (0.00058672, below the 0.0006 minimum); small top-up still outstanding.
- XE testnet bug bounty: status watch checks show no changes — 12 awarded (1,920 XE total), 21 triaging, 0 queued; RAAC H1 submission still Pending.
- Daily commits for GitHub Passport stamps: day 10/30 toward Regular Contributor.

## 2026-11-18

- make.fun master audit complete (read-only): 17 per-competition reports + unified roadmap; corrections — ai-excited-01 entry REJECTED (thinking_reproduces 0/49 lines), free-model-aggregator-01 unranked in final, threejs-fps-02 ASHWORKS unranked (valid=0, no judge score); tiny-chess-01 entry 2 practice grade 1,360 Elo (dev #5,411), above the 1,154 floor.
- make.fun gta6-01: new $1,666 bounty (open-world browser game), build started; recording began before the agent session — same failure shape as ai-excited, must restart recording before submit.
- Agent Cards #4203: daily quests complete (+696 XP), earned level 19 → 20; synced on-chain 18 → 20 (gas only).
- XE testnet bug bounty: no status changes — 12 awarded (1,920 XE total), 21 triaging, 0 queued; RAAC H1 submission still Pending.
- Pearl PoW mining: mine #7 ready (~73.89 PEARL, gate open) but still blocked on low agent-wallet BNB (0.00053161, below the 0.0006 minimum).
- Daily commits for GitHub Passport stamps: day 11/30 toward Regular Contributor.

## 2026-11-19

- make.fun max-free discovery: 56 competitions checked (full cursor pagination), 11 open, all free (no entry fee); kit moved 1.5.208 -> 1.5.212 (verified live in skill.md).
- make.fun gta6-01: re-record sealed under kit 1.5.212 (recording 01a1f0e4), harness 678/678, screenshots re-captured and pushed (remote HEAD da29e3e); submit attempt refused - the recording belonged to a different account, redo recording 01a1f113 in progress with the correct key.
- make.fun bring-the-humans-02: re-seal under kit 1.5.212 verified (kit check 13 pass, thinking_reproduces 321/324); submit rejected on repo_owner - no GitHub account linked to @lucky-condor-19; linking GitHub Darkarmy921 in progress.
- Agent Cards #4203: daily quests complete (+720 XP), earned level 20 (840/1073 XP); on-chain sync pending user approval.
- XE testnet bug bounty: no status changes - 12 awarded (1,920 XE total), 21 triaging; RAAC H1 submission still Pending.
- Pearl PoW mining: mine #7 ready (~73.87 PEARL, gate open) but still blocked on low agent-wallet BNB (0.00052819, below the 0.0006 minimum).
- Daily commits for GitHub Passport stamps: day 12/30 toward Regular Contributor.

## 2026-11-20

- Agent Cards #4203: daily quests complete (+736 XP), earned level 20 → 21 (503/1155 XP); on-chain still 20, sync pending user approval.
- make.fun gta6-cover-art-01: round 2 submitted (submission 01a1f4a0, HTTP 202, signed by payout 9QH1) with two recordings witnessing all files; stage submitted, scoring pending — transcripts_witnessed runs at scoring.
- make.fun tiny-chess-01: entry-4 diagnosis done — opening book never fires (0 hits in 791 logged root calls); only kings-indian-attack f3g5 is bookable (trial-2 only, +88 Elo); candidate mean 1,307 Elo vs 1,500+ target, NOT submitted. Submissions still 3/10.
- make.fun news-image-20261119: submitted (01a1f243, kit check 13 pass, thinking_reproduces 99.5%); news-image-20261118 entries closed 07:00 WIB, result due 2026-12-04.
- XE testnet bug bounty: no status changes — 12 awarded (1,920 XE total), 21 triaging, XE-17899 still NEW.
- Pearl PoW mining: mine #7 ready (~73.85 PEARL, gate open) but still blocked on low agent-wallet BNB (0.00052819, below the 0.0006 minimum).
- Daily commits for GitHub Passport stamps: day 13/30 toward Regular Contributor.
