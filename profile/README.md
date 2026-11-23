<div align="center">
  <img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/leverframe-header.gif" alt="Leverframe — agent infrastructure" width="100%">
</div>

Agent infrastructure for people running agents that do real work —
bridging, routing, guardrails, verifiable consensus, plugin trust,
and a signal box to watch it all.

**Two agent runtimes. One MCP interface. One signal box. Every lever gated.**

[![Build](https://img.shields.io/github/actions/workflow/status/leverframe/fleet-bridge/ci.yml?branch=main&style=flat-square&label=build)](https://github.com/leverframe/fleet-bridge/actions/workflows/ci.yml)
[![Secret scan](https://img.shields.io/github/actions/workflow/status/leverframe/fleet-bridge/gitleaks.yml?branch=main&style=flat-square&label=secret%20scan)](https://github.com/leverframe/fleet-bridge/actions/workflows/gitleaks.yml)
[![License](https://img.shields.io/github/license/leverframe/fleet-bridge?style=flat-square)](https://github.com/leverframe/fleet-bridge/blob/main/LICENSE)
[![Docs](https://img.shields.io/website?url=https%3A%2F%2Fdocs.leverframe.dev&style=flat-square&label=docs)](https://docs.leverframe.dev)

Leverframe is named for the railway signal box: an interlocking where
every lever is mechanically prevented from conflicting with any other.
The tools here apply that discipline to agent fleets — deterministic
guardrails, signed consensus receipts, signed plugin installs, one
audited bridge between your MCP clients and your agent runtimes, and
a read-only panel that shows you the whole board.

### The stack

#### Bridge & routing

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/fleet-bridge"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/fleet-bridge-mark.png" width="112" alt="fleet-bridge mark"></a><br><br>
      <a href="https://github.com/leverframe/fleet-bridge"><strong>fleet-bridge</strong></a><br>
      <sub>One stdio MCP server bridging <strong>OpenClaw</strong> and <strong>Hermes</strong> agents<br>into any MCP client — cross-runtime by construction.</sub><br><br>
      <a href="https://github.com/leverframe/fleet-bridge/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="MIT"></a>
      <a href="https://www.npmjs.com/package/fleet-bridge"><img src="https://img.shields.io/npm/v/fleet-bridge?style=flat-square&label=npm&labelColor=0E1116&color=FFB224" alt="npm"></a>
    </td>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/agent-gateway"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/agent-gateway-mark.png" width="112" alt="agent-gateway mark"></a><br><br>
      <a href="https://github.com/leverframe/agent-gateway"><strong>agent-gateway</strong></a><br>
      <sub>Plugin-based gateway routing platform messages<br>(Discord, Slack, Telegram) to your agents — plus an<br>HTTP-to-stdio bridge for external MCP tools.</sub><br><br>
      <a href="https://github.com/leverframe/agent-gateway/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-BUSL--1.1-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="BUSL-1.1"></a>
    </td>
  </tr>
</table>

#### Guardrails & verification

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/wranglebot"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/wranglebot-mark.png" width="112" alt="wranglebot mark"></a><br><br>
      <a href="https://github.com/leverframe/wranglebot"><strong>wranglebot</strong></a><br>
      <sub>Deterministic guardrails, loop-breaking, and <code>.curt</code> emission<br>for coding agents (Claude Code, Codex).</sub><br><br>
      <a href="https://github.com/leverframe/wranglebot/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="MIT"></a>
      <a href="https://www.npmjs.com/package/@wranglebot/cli"><img src="https://img.shields.io/npm/v/@wranglebot/cli?style=flat-square&label=npm&labelColor=0E1116&color=FFB224" alt="npm"></a>
    </td>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/skillguard"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/skillguard-mark.png" width="112" alt="skillguard mark"></a><br><br>
      <a href="https://github.com/leverframe/skillguard"><strong>skillguard</strong></a><br>
      <sub>Signed + transparent plugin directory for Claude Code —<br>minisign-verified installs only, atomic and versioned,<br>with a nightly trust-annotated index. Unsigned is refused.</sub><br><br>
      <a href="https://github.com/leverframe/skillguard/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-BUSL--1.1-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="BUSL-1.1"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/tractum"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/tractum-mark.png" width="112" alt="tractum mark"></a><br><br>
      <a href="https://github.com/leverframe/tractum"><strong>tractum</strong></a><br>
      <sub>Verifiable multi-agent consensus for Claude —<br>signed k-of-n receipts bound to transcript evidence.</sub><br><br>
      <a href="https://github.com/leverframe/tractum/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-BUSL--1.1-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="BUSL-1.1"></a>
      <a href="https://tractum.dev"><img src="https://img.shields.io/website?url=https%3A%2F%2Ftractum.dev&style=flat-square&label=tractum.dev&labelColor=0E1116&color=FFB224" alt="tractum.dev"></a>
    </td>
    <td width="50%"></td>
  </tr>
</table>

#### The signal box

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/cabinet-lite"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/cabinet-mark.png" width="112" alt="cabinet-lite mark"></a><br><br>
      <a href="https://github.com/leverframe/cabinet-lite"><strong>cabinet-lite</strong></a><br>
      <sub>The signal box made software: a cross-runtime fleet dashboard —<br>what needs you, who's free, what happened.</sub><br><br>
      <a href="https://github.com/leverframe/cabinet-lite/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="MIT"></a>
      <a href="https://docs.leverframe.dev"><img src="https://img.shields.io/website?url=https%3A%2F%2Fdocs.leverframe.dev&style=flat-square&label=docs&labelColor=0E1116&color=FFB224" alt="docs"></a>
    </td>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/hermes-fleet"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/hermes-fleet-mark.png" width="112" alt="hermes-fleet mark"></a><br><br>
      <a href="https://github.com/leverframe/hermes-fleet"><strong>hermes-fleet</strong></a><br>
      <sub>Operator dashboard plugin for Hermes Desktop —<br>cabinet state, agent roster, journal freshness,<br>and an accountability queue in one tab.</sub><br><br>
      <a href="https://github.com/leverframe/hermes-fleet/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-BUSL--1.1-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="BUSL-1.1"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <br>
      <a href="https://github.com/leverframe/heartbeat-collector"><img src="https://raw.githubusercontent.com/leverframe/.github/main/profile/assets/heartbeat-collector-mark.png" width="112" alt="heartbeat-collector mark"></a><br><br>
      <a href="https://github.com/leverframe/heartbeat-collector"><strong>heartbeat-collector</strong></a><br>
      <sub>Fleet liveness: the collector polls each agent's<br>/health on a 30s cycle; dashboards read the state.</sub><br><br>
      <a href="https://github.com/leverframe/heartbeat-collector/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-BUSL--1.1-0E1116?style=flat-square&labelColor=0E1116&color=FFB224" alt="BUSL-1.1"></a>
    </td>
    <td width="50%"></td>
  </tr>
</table>

### How it fits

<p align="center">
  <img src="https://github.com/leverframe/.github/raw/main/profile/assets/how-it-fits.png" width="830" alt="How Leverframe fits together: wranglebot supervises coding agents such as Claude Code and Codex; their tool calls reach the OpenClaw gateway and Hermes agent runtimes through fleet-bridge, one stdio MCP server where every lever is gated; tractum verifies multi-agent consensus with signed k-of-n receipts; cabinet-lite reads across the whole fleet as a read-only signal box">
</p>


Ecosystem: wranglebot and tractum are emitters of the open
[`.curt`](https://github.com/dotcurt/dot_curt) conversation format —
the decision record and the consensus receipt ride in the same file
format as everything else. Per-product reference for the whole stack
lives at **[docs.leverframe.dev](https://docs.leverframe.dev)**.

## Licensing

Per-repo, stated plainly. **MIT** — take it, run it, fork it — for
fleet-bridge, cabinet-lite, and wranglebot. Everything else in the
stack (tractum, skillguard, agent-gateway, hermes-fleet,
heartbeat-collector) is source-available under
[BUSL-1.1](https://spdx.org/licenses/BUSL-1.1.html): free for personal
and noncommercial production use; commercial use requires a written
license from the Licensor. All BUSL repos convert to MIT on
2030-10-12.

## Get started

Bridge your agents (no clone needed):

```bash
npm install -g fleet-bridge
```

Five minutes to your first bridged agent: the
[quickstart](https://github.com/leverframe/fleet-bridge/blob/main/docs/QUICKSTART.md).

Then stand up the signal box — point
[cabinet-lite](https://github.com/leverframe/cabinet-lite#quickstart)
at the same roster files and watch the board.
