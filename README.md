# tldw.sh connector submission bundles

OAuth-only submission bundles for the hosted [tldw.sh](https://tldw.sh) MCP
service at `https://api.tldw.sh/mcp`.

These files are public installation and directory-review materials. Publishing a
bundle does not establish submission, approval or availability in a vendor directory.

| Bundle | Source folder | Manifest |
| --- | --- | --- |
| Claude | [`claude/`](claude/) | `.claude-plugin/plugin.json` |
| ChatGPT and Codex | [`openai/`](openai/) | `.codex-plugin/plugin.json` |

Each folder contains 13 files, including the canonical tldw skill **0.3.6**, an
icon and MIT license. The **1.0.3** bundles are separate from the generic agent
plugin and JavaScript/Python SDK releases. Each release ZIP has a single `tldw/`
top-level folder; use the provider-specific ZIP from the
[1.0.3 release](https://github.com/tldwdotsh/tldw-connectors/releases/tag/v1.0.3).
`connector-release.json` records source provenance and exact bundle/file SHA256
hashes. The earlier [1.0.0 release](https://github.com/tldwdotsh/tldw-connectors/releases/tag/v1.0.0)
and [1.0.2 release](https://github.com/tldwdotsh/tldw-connectors/releases/tag/v1.0.2)
remain unchanged.

Sign in through the host's OAuth flow using your own tldw.sh account. No secret
is included. Check `account_usage` before processing. Optional public metadata
tools read service configuration, activation facts and the public catalog;
these still use the authenticated MCP connection and cannot initiate purchases.
Hosted discovery searches X; supply YouTube links or use your agent's own tools.
Processing reuses captions or saved source first. Where audio processing is enabled
for the platform, missing usable captions trigger automatic original-audio
transcription on every plan at 1 credit per minute. Legacy controls cannot disable
or force audio. Read live account availability and keep the authorized ceiling.
Saved summaries and transcripts remain separate.

Start with the provider folder's README or the current
[connection instructions](https://tldw.sh/agents). Directory submission, owner
verification and real host review evidence are separate steps.

[Documentation](https://tldw.sh/docs) · [Support](https://tldw.sh/support) ·
[Privacy](https://tldw.sh/privacy) · [Terms](https://tldw.sh/terms)

The bundles are MIT licensed. The hosted service is governed by its terms and
privacy policy.
