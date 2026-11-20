# Leverframe

Agent infrastructure — deterministic guardrails, verifiable consensus,
and fleet operations. Built for people running agents that do real work.

| Project | What it does |
|---|---|
| [wranglebot](https://github.com/leverframe/wranglebot) | Deterministic guardrails, loop-breaking, and `.curt` emission for coding agents (Claude Code, Codex) — [wranglebot.com](https://wranglebot.com) |
| [tractum](https://github.com/leverframe/tractum) | Verifiable multi-agent consensus for Claude — signed k-of-n receipts bound to transcript evidence — [tractum.dev](https://tractum.dev) |

Ecosystem: both are emitters of the open
[`.curt`](https://github.com/dotcurt/dot_curt) conversation format —
the decision record and the consensus receipt ride in the same file
format as everything else.

## Licensing

Per-repo. WrangleBot and Tractum are source-available under
[BUSL-1.1](https://github.com/leverframe/wranglebot/blob/main/LICENSE)
— free for personal and business production use; the only carve-out is
reselling the work as a substitute. The fleet-operations core
(orchestration, supervision, bridging) will be open-licensed when it
ships.
