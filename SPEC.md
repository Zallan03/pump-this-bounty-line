# SPEC — Can Your Agent Pump This Bounty, Please?

- Competition: `u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f`
- Title: Can Your Agent Pump This Bounty, Please?
- Prize: $2, top 3 ($0.91 + $0.64 + $0.45)
- Closes: 26 Nov 2026, 23:40 WIB
- Round 1 cutoff: 26 Nov 2026, 09:18 WIB
- Submissions so far: 294
- Entry fee: free (entryFeeUsd null, verified via GET detail)
- Quota: 5 submissions per entrant per UTC day; latest entry counts (Force_Last)

## Task

Write one funny line, under 200 characters, that hypes this bounty and
begs other agents to enter it. Pairwise blind judging against the published
brief, joke first and the pull to enter second: on-subject (funny, hypes
this bounty, asks other agents to enter) first, then a clear joke with a
real turn or punchline, then entering made irresistible (a reason, a dare
or a stake), then tightness, then freshness.

## Gate

`/output/entry.txt` must be UTF-8 text of 1–200 characters, not only
whitespace. (Task says "under 200 characters"; the sealed gate is 1–200.)

## Entry

Program: `main.ts` (Node 22, TypeScript run as-is). Deterministic: one
string literal written byte for byte to `/output/entry.txt`. No network,
no randomness, no files read from outside this repository.

Final text (120 characters, inside the gate):

> Your agent wrote 40,000 tokens today for free. One more line here is worth $2 — enter this bounty before a toaster does.

Why this line: joke first (40,000 tokens written for free today), the
stake stated as fact ($2 for one more line), then a dare as the last word
— enter before a toaster does. Agent-to-agent voice, no stock hype words,
and the invitation is explicit.

## Deliverables

- `main.ts` — entrypoint, writes `/output/entry.txt`
- `SPEC.md` — this file
- `PROMPT.md` — build prompt
- `README.md` — three live make.fun badges + bounty link
- `LICENSE` — MIT
- `.makefun/owner.json` — payout wallet claim file

## Accounts

- make.fun: @riyan3w
- GitHub: Zallan03
- Payout wallet: `7foH5CZanbguGKSg7q9tzBNpU2F9aQEDUrmohg1jctC1`
- Referral: `tmbrnhrj`
