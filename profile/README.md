# Leverframe

Agent infrastructure for people running agents that do real work —
bridging, guardrails, and verifiable consensus.

| Project | What it does | License |
|---|---|---|
| [fleet-bridge](https://github.com/leverframe/fleet-bridge) | One stdio MCP server that bridges OpenClaw gateway agents **and** Hermes agents into any MCP client — cross-runtime by construction. Runs a real 20-agent fleet daily. | [MIT](https://github.com/leverframe/fleet-bridge/blob/main/LICENSE) |
| [wranglebot](https://github.com/leverframe/wranglebot) | Deterministic guardrails, loop-breaking, and `.curt` emission for coding agents (Claude Code, Codex) — [wranglebot.com](https://wranglebot.com) | [BUSL-1.1](https://github.com/leverframe/wranglebot/blob/main/LICENSE) |
| [tractum](https://github.com/leverframe/tractum) | Verifiable multi-agent consensus for Claude — signed k-of-n receipts bound to transcript evidence — [tractum.dev](https://tractum.dev) | [BUSL-1.1](https://github.com/leverframe/tractum/blob/main/LICENSE) |

Ecosystem: wranglebot and tractum are emitters of the open
[`.curt`](https://github.com/dotcurt/dot_curt) conversation format —
the decision record and the consensus receipt ride in the same file
format as everything else.

## Licensing

Per-repo, stated plainly. The fleet-operations core (bridging) is
**MIT** — take it, run it, fork it. WrangleBot and Tractum are
source-available under [BUSL-1.1](https://spdx.org/licenses/BUSL-1.1.html):
free for personal and business production use; the only carve-out is
reselling the work as a substitute.

## Get started

```bash
git clone https://github.com/leverframe/fleet-bridge
cd fleet-bridge && npm ci && npm run build
```

Five minutes to your first bridged agent: the
[quickstart](https://github.com/leverframe/fleet-bridge/blob/main/docs/QUICKSTART.md).
