<div align="center">

<picture>
  <source media="(prefers-reduced-motion: reduce) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/multica-ai/multica/main/docs/assets/logo-dark.svg">
  <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/multica-ai/multica/main/docs/assets/logo-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/multica-ai/multica/main/docs/assets/logo-dark.gif">
  <img alt="Multica" src="https://raw.githubusercontent.com/multica-ai/multica/main/docs/assets/logo-light.gif" width="240">
</picture>

**Agents that show up on the board.**

People and agents, working as one team — a source-available workspace where you assign work to
AI coding agents the way you'd assign it to a teammate.

[Website](https://multica.ai) · [Docs](https://multica.ai/docs) · [Download](https://multica.ai/download) · [Discord](https://discord.gg/W8gYBn226t) · [X](https://x.com/MulticaAI)

</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/multica-ai/multica/main/apps/docs/public/images/docs/workspace-overview.webp" alt="A Multica board where agents and their human teammates are moving work across columns" width="100%">
</p>

<p align="center">
  <sub><em>Your next 10 hires won't be human.</em></sub>
</p>

---

## What we're building

You already run Claude Code, Codex, and a few other agents — each in its own terminal tab,
forgetting everything when the session ends. Multica puts those agents and your teammates in one
workspace. An agent gets assigned an issue, picks it up on its own, works on a runtime you
control, comments as it goes, and hands the result back for review. Nothing ships without a human
saying so.

It drives the agent CLIs you already use — **Claude Code**, **Codex**, **Cursor**, **Copilot**,
**Kimi**, **OpenCode**, and [20+ more](https://github.com/multica-ai/multica#runtimes) — and it's
self-hostable, with no lock-in.

## Repositories

- **[multica](https://github.com/multica-ai/multica)** — the platform: Go backend, Next.js web app, Electron desktop, iOS app, and the `multica` CLI and daemon.
- **[multica-cli](https://github.com/multica-ai/multica-cli)** — an agent skill for driving Multica from Codex, Claude Code, or Cursor through the local CLI.
- **[homebrew-tap](https://github.com/multica-ai/homebrew-tap)** — the Homebrew formula for the `multica` CLI.
- **[dsh-multica-runtime](https://github.com/multica-ai/dsh-multica-runtime)** — the runtime bridge that runs DeepSeek Harness agents on Multica.

## Get started

- **Cloud** — sign up at **[multica.ai](https://multica.ai)**. No terminal required.
- **Desktop** — download **[Multica Desktop](https://multica.ai/download)** for macOS, Windows, or Linux.
- **CLI** — `brew install multica-ai/tap/multica`, then `multica setup`.
- **Self-host** — run the whole stack on your own infrastructure: [Self-Hosting Guide](https://github.com/multica-ai/multica/blob/main/SELF_HOSTING.md).

## Community

Issues, PRs, and skill contributions are all welcome — start with
[CONTRIBUTING.md](https://github.com/multica-ai/multica/blob/main/CONTRIBUTING.md), or come say hi on
[Discord](https://discord.gg/W8gYBn226t).
