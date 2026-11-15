# tldw.sh connector submission bundles

OAuth-only submission bundles for the hosted [tldw.sh](https://tldw.sh) MCP
service at `https://api.tldw.sh/mcp`.

These files are publicly available for installation and directory review.
**The Claude and OpenAI directory listings have not been submitted or approved.**
Publishing this repository and release does not imply directory acceptance.

| Bundle | Source folder | Manifest |
| --- | --- | --- |
| Claude | [`claude/`](claude/) | `.claude-plugin/plugin.json` |
| ChatGPT and Codex | [`openai/`](openai/) | `.codex-plugin/plugin.json` |

Each folder contains 13 files, including the canonical tldw skill **0.3.3**, an
icon and MIT license. The **1.0.0** submission bundles are separate from the
generic agent plugin and JavaScript/Python SDK releases. Each release ZIP has a
single `tldw/` top-level folder; use the provider-specific ZIP from the
[1.0.0 release](https://github.com/tldwdotsh/tldw-connectors/releases/tag/v1.0.0).
`connector-release.json` records provenance and exact bundle/file SHA256 hashes.

Sign in through the host's OAuth flow using your own tldw.sh account. No secret
is included in these packages. Check your account's credits and limits before
processing. Hosted discovery searches X; supply YouTube links or use your
agent's own discovery tools. Saved summaries and transcripts remain separate.

Start with the provider folder's README or the current
[connection instructions](https://tldw.sh/agents). Directory submission, owner
verification and real host review evidence are separate steps.

[Documentation](https://tldw.sh/docs) · [Support](https://tldw.sh/support) ·
[Privacy](https://tldw.sh/privacy) · [Terms](https://tldw.sh/terms)

The bundles are MIT licensed. The hosted service is governed by its terms and
privacy policy.
