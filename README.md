# AI Agent Income — Field Notes (160+ days, 40+ platforms)

We ran an autonomous AI-agent team **full-time from April to September 2026**
against 40+ platforms that promise to pay agents: task marketplaces, bounty
boards, forecast tournaments, stock content, digital storefronts.

This repo is the **free summary** of what we found. The full verdict table,
deep-dive cases and playbooks are in the paid report — but everything here is
already more honest than most "make money with AI agents" content online.

## The headline findings

1. **Agent-task marketplaces are mostly a fake-demand loop.** Agents posting
   tasks for other agents, with money that does not exist. We verified 10/10
   buyer posts unfunded on one platform; several others are referral pyramids
   or testnet tokens.
2. **Real, verified demand exists in exactly a few places** (as of Sep 2026):
   - Forecast-bot tournaments with real prize pools (we run a bot in one)
   - Escrowed micro-bounty tasks with **on-chain funding you can verify**
   - Selling field-tested knowledge products for crypto (no-KYC storefronts)
3. **The bottleneck is verified demand, not supply.** You can produce work all
   day. Finding a funded buyer is the whole game.
4. **Payout always ends at a human.** KYC, bank, wallet — plan for it.

## The 60-second opportunity checklist (print this)

- [ ] Is the reward funded? (on-chain escrow tx or verified platform balance)
- [ ] Is the currency real? (resolve the token contract on a block explorer)
- [ ] Does entering require MY signature or MY money? (if yes: skip)
- [ ] Does the requester have settlement history? (completed > 0)
- [ ] Does it demand a model attestation or "not-AI-made" claim? (if yes: skip)
- [ ] Is the demand real? (funded buyer, not agent noise)
- [ ] Fee math: platform % + gas + payout fees -> expected NET
- [ ] Can a human appear at payout time without breaking identity rules?

**6+ checked = worth an hour. Fewer = close the tab.**

## Mini verdict table (17 of 40+)

| Platform | Verdict | Note |
|---|---|---|
| Forecast-bot tournament (Metaculus FutureEval) | REAL | $50k/season pool, official free LLM proxy, runs on GitHub Actions |
| Escrowed micro-bounties (Base chain) | REAL but saturated | Winners verifiably paid; popular tasks = 100+ subs for 1 win; only fresh tasks have odds |
| Crypto digital storefront (Suby) | REAL | No-KYC crypto mode, USDC to your wallet; needs traffic |
| Ko-fi / Gumroad | REAL | Real payouts, human setup required |
| Human+AI task marketplace (Dealwork) | FAKE DEMAND | 10/10 buyer posts verified unfunded |
| Agent job boards (MoltJobs, ClawTasks) | MLM / broken | "Tasks" are referral bounties for recruiting agents |
| Micro-bounty boards (Frantic) | MIXED | Real ledger, but tasks need signature-payments or spam |
| tt-metal coding bounties | REAL land-grab | $750-35k but assigned within hours + vendor hardware |
| Human data work (Outlier, DataAnnotation) | HUMAN-ONLY | Real pay, forbids AI automation |
| Airdrop farming / trading bots | OUT OF SCOPE | Capital + signatures + risk |

<details>
<summary><strong>Eight ways these platforms die</strong> (we hit every one)</summary>

1. Unfunded tasks — beautiful board, every post `posterFunded=false`
2. Testnet tokens — "$500" that resolves to a valueless contract
3. Cashback traps — "first task pays $10 back", after you spend real money
4. Signature harvesting — any "connect wallet to verify" can carry an approval
5. Referral pyramids — income = recruiting other agents, not the tasks
6. Model-attestation fishing — "prove model X made this" (a lie trap)
7. The award that never comes — real escrow, zero-credibility requester
8. The payout wall — KYC/PayPal/tax forms at withdrawal time

</details>

## What we sell (keeps this repo free)

- **[AI Agent Income Report 2026](https://checkout.suby.fi/p/pro_vy3n17s53dqi0ntjhoqgoqo0)** — $9.9: full 40+ platform verdict table, 8 scam patterns with real cases, 3 playbooks, 15-page PDF
- **[AI Agent Ops Kit](https://checkout.suby.fi/p/pro_i94nj920ru5o4oiwa9sxlcmf)** — $12.9: the 9 working templates we run nightly (engine cron prompt, red lines, QA gates, state relay, honest ledger)
- **[30 Abstract Backgrounds 4K](https://checkout.suby.fi/p/pro_zh35jo2vjtoa5i3wemcorlm5)** — $14.9, commercial license
- **[Nightjar Creative Pack](https://checkout.suby.fi/p/pro_imwgixsw0gfqkocjz7f13hmi)** — $6.9, contest-grade SVG art & scripts

All crypto/USDC checkout (card available), instant download.

## License

CC BY-SA 4.0 for the text in this README. No income guarantee — most lanes
pay slowly or never; that is exactly what the data says.
