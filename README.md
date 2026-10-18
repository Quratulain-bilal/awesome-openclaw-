# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for [OpenClaw](https://github.com/openclaw/openclaw) — the AI agent gateway that lets you run AI agents across Slack, Discord, Telegram, WhatsApp, browser automation, and more.

OpenClaw is an open-source AI agent gateway with a growing ecosystem of plugins, skills, channels, and integrations. This list collects the best community and official resources in one place.

## Contents

- [Official](#official)
- [Plugins](#plugins)
- [Skills](#skills)
- [Browser & Automation](#browser--automation)
- [Channels & Integrations](#channels--integrations)
- [Memory & Context](#memory--context)
- [Tutorials & Guides](#tutorials--guides)
- [Blog Posts & Articles](#blog-posts--articles)
- [Videos & Talks](#videos--talks)
- [Templates & Starters](#templates--starters)
- [Tools for OpenClaw Developers](#tools-for-openclaw-developers)
- [Community](#community)
- [Contributing](#contributing)

---

## Official

- [OpenClaw](https://github.com/openclaw/openclaw) — The main monorepo: gateway, CLI, bundled plugins, channels.
- [Documentation](https://docs.openclaw.ai) — Official docs covering CLI, configuration, tools, and plugin authoring.
- [ClawHub](https://clawhub.ai) — Plugin registry for publishing and discovering native OpenClaw plugins.
- [CHANGELOG](https://github.com/openclaw/openclaw/blob/main/CHANGELOG.md) — Release notes and credited contributors.
- [Configuration Reference](https://docs.openclaw.ai/gateway/configuration-reference) — All `~/.openclaw/openclaw.json` keys, defaults, and semantics.

## Plugins

Community-built plugins distributed via npm and ClawHub.

- [openclaw-rewind](https://www.npmjs.com/package/@syeda_quratualin/openclaw-rewind) — Git-like time-travel for AI conversations: save, list, restore, branch, and diff session snapshots.

- [reply-push-v2](https://github.com/verdeoc/reply-push-v2) — Native iOS push notifications for the official OpenClaw app; Free edition 2.1.1 covers `agentFinished`, with Pro event categories. By [@verdeoc](https://github.com/verdeoc).

> See [Contributing](#contributing) to add your plugin.

## Skills

Reusable skill bundles agents can load on demand.

- [`browser-automation`](https://docs.openclaw.ai/tools/browser) — Bundled. The snapshot, stable-tab, stale-ref, and manual-blocker recovery loop for browser-controlled agents.

## Browser & Automation

- [Browser tool docs](https://docs.openclaw.ai/tools/browser) — OpenClaw-managed Chrome/Brave/Edge/Chromium profile control via CDP.
- [Browser troubleshooting](https://docs.openclaw.ai/tools/browser-linux-troubleshooting) — Linux display, headless fallback, CDP readiness fixes.
- [Browserless](https://browserless.io) — Hosted Chromium service supported as a remote CDP profile.
- [Browserbase](https://www.browserbase.com) — Cloud headless browsers with CAPTCHA solving and stealth mode, supported as a remote CDP profile.

## Channels & Integrations

OpenClaw ships bundled channel plugins. See [`docs/gateway/config-channels`](https://docs.openclaw.ai/gateway/config-channels) for full list.

- **Slack** — Bot mentions, threads, DMs, multi-account.
- **Discord** — Channels, threads, voice (with model override), subagent thread bridging.
- **Telegram** — Bot API integration with forwarded messages, replies, inline-via metadata.
- **WhatsApp** — Bundled WhatsApp channel.
- **Matrix** — Matrix federation channel.
- **iMessage** — macOS-native iMessage channel.

## Memory & Context

- [Memory configuration reference](https://docs.openclaw.ai/reference/memory-config) — `agents.defaults.memorySearch.*`, `memory.qmd.*`, `memory.citations`, dreaming.
- [Plugin: memory-core](https://docs.openclaw.ai/tools/plugin) — Bundled memory plugin powering long-running session recall.

## Tutorials & Guides

> See [Contributing](#contributing) to add a tutorial.

## Blog Posts & Articles

> See [Contributing](#contributing) to add a post.

## Videos & Talks

> See [Contributing](#contributing) to add a talk.

## Templates & Starters

> Plugin and skill starter templates. See [Contributing](#contributing) to add yours.

## Tools for OpenClaw Developers

Tools that help you build, debug, or distribute OpenClaw extensions.

- [`openclaw config schema`](https://docs.openclaw.ai/gateway/configuration-reference) — Prints the live JSON Schema used for validation and Control UI.
- [`openclaw browser doctor`](https://docs.openclaw.ai/tools/browser) — Gateway, plugin, profile, browser, and tab readiness diagnostics.
- [`openclaw doctor`](https://docs.openclaw.ai/cli) — Migrates legacy extension config and validates browser config.

## Community

- [GitHub Issues](https://github.com/openclaw/openclaw/issues) — Bug reports and feature requests.
- [GitHub Pull Requests](https://github.com/openclaw/openclaw/pulls) — In-flight contributions.
- [ClawHub Registry](https://clawhub.ai) — Browse community plugins.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

**Quick rules:**

1. One link per pull request — keeps reviews focused.
2. Use the format: `- [Name](URL) — Description.`
3. Description should be 1 sentence and end with a period.
4. Resources should be useful, well-maintained, and OpenClaw-related.
5. New categories require justification in the PR description.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
