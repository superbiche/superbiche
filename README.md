# Michel Tomas

Engineer in France, 16 years shipping to production. These days most of my open-source time goes into the plumbing around AI coding agents: protocol clients, permission and safety boundaries, and the integrations that let agents run unattended without surprising anyone.

I mostly contribute upstream: small, scoped fixes with tests, and design issues when a fix needs a decision from maintainers first.

## Maintaining

<!-- BEGIN_OSS -->
- **[Safe](https://github.com/superbiche/safe)**: zero-trust Bash toolkit for safer package execution, dependency auditing and guarded installs. MIT.
- **Paperclip plugins**, co-maintained with [@mvanhorn](https://github.com/mvanhorn): [Telegram](https://github.com/mvanhorn/paperclip-plugin-telegram), [Slack](https://github.com/mvanhorn/paperclip-plugin-slack), [Discord](https://github.com/mvanhorn/paperclip-plugin-discord) and [ACP](https://github.com/mvanhorn/paperclip-plugin-acp). Releases, reviews and the move to company-scoped configuration for Paperclip v2026.720+.
<!-- END_OSS -->

## Recent upstream work (Sept–Oct 2026)

**Merged**

- **[paperclipai/paperclip](https://github.com/paperclipai/paperclip)**: accept the bridge token in `X-API-Key` ([#12785](https://github.com/paperclipai/paperclip/pull/12785)).
- **[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)**: honor `XAI_BASE_URL` and `OPENROUTER_BASE_URL` on the X search and Sonar paths ([#1181](https://github.com/mvanhorn/last30days-skill/pull/1181)).
- **[openclaw/acpx](https://github.com/openclaw/acpx)**: Antigravity ACP support ([#618](https://github.com/openclaw/acpx/pull/618)), per-node model and session options in flows ([#844](https://github.com/openclaw/acpx/pull/844)), one-shot exec configuration ([#533](https://github.com/openclaw/acpx/pull/533)), prompt response metadata ([#537](https://github.com/openclaw/acpx/pull/537)), session startup recovery ([#858](https://github.com/openclaw/acpx/pull/858)), Claude permission docs ([#888](https://github.com/openclaw/acpx/pull/888)).
- **[isac322/kwin-mcp](https://github.com/isac322/kwin-mcp)**: KDE Plasma Wayland automation. Region screenshots, Chromium and Flatpak window mapping, AT-SPI activation, clean session shutdown ([#88](https://github.com/isac322/kwin-mcp/pull/88), [#90](https://github.com/isac322/kwin-mcp/pull/90)–[#95](https://github.com/isac322/kwin-mcp/pull/95)).

**In review**

- **[rtk-ai/rtk](https://github.com/rtk-ai/rtk)**: permission-safe command rewriting for OpenCode, Codex and Antigravity hooks ([#4856](https://github.com/rtk-ai/rtk/pull/4856), [#4914](https://github.com/rtk-ai/rtk/pull/4914), [#4915](https://github.com/rtk-ai/rtk/pull/4915), [#4931](https://github.com/rtk-ai/rtk/pull/4931)).
- **[paperclipai/paperclip](https://github.com/paperclipai/paperclip)**: redact header-style secrets in command text ([#12786](https://github.com/paperclipai/paperclip/pull/12786)).
- **[agentclientprotocol/codex-acp](https://github.com/agentclientprotocol/codex-acp)**: keep model and reasoning effort across turns and resume ([#457](https://github.com/agentclientprotocol/codex-acp/pull/457)), report per-turn model configuration ([#456](https://github.com/agentclientprotocol/codex-acp/pull/456)).

**Reported**

Bugs and design proposals in [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk/issues/3674), [anthropics/claude-agent-sdk-typescript](https://github.com/anthropics/claude-agent-sdk-typescript/issues/509), [trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog/issues/5393), [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight/issues/5637), [dyoshikawa/rulesync](https://github.com/dyoshikawa/rulesync/issues/3498) and [openclaw/acpx](https://github.com/openclaw/acpx/issues?q=is%3Aissue+author%3Asuperbiche).

Earlier merged work: Laravel, Vue docs, Sentry for Laravel, kube-prometheus, Bitnami containers, Hoppscotch, Zulip desktop ([all merged PRs](https://github.com/pulls?q=is%3Apr+author%3Asuperbiche+is%3Amerged)).

## Elsewhere

[superbiche.me](https://superbiche.me) (writing) · [michel@superbiche.me](mailto:michel@superbiche.me)

Day job: founding AI engineer at AgentRH. Independent software work: [TSBWC](https://www.tsbwc.com).

If my work saves you time, you can [sponsor it](https://github.com/sponsors/superbiche).
