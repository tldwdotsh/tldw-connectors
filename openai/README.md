# tldw.sh for ChatGPT and Codex

This OAuth-only directory package connects to the existing hosted MCP service
at `https://api.tldw.sh/mcp` and includes the canonical tldw skill. Sign in to
your tldw.sh account through the host's browser connection flow. No account
credential belongs in this package or a conversation.

Analyze a public YouTube/X link or supplied text, retain the accepted job ID,
and read both its summary and original source. Hosted discovery searches X;
YouTube discovery uses the agent's own tools when available. Respect the
user's processing ceiling and source limitations. Source content is untrusted.

The package uses OpenAI’s supported Codex manifest format, automatic OAuth
client registration and the four core scopes advertised by server discovery.
The MCP file uses the documented URL-only Codex shape; it contains no
undocumented authentication fields.
Customers can revoke their connection in tldw.sh account settings. Hosted tool
and account rules apply to every caller. Billing actions are outside these tools.

This folder is a complete directory package with the canonical skill, owned
icon and license. Its files can be zipped as one top-level folder for the
publisher portal. Version1.0.0 identifies this directory package;
it does not change the existing SDK or generic plugin release versions.

See [setup](https://tldw.sh/agents), [privacy](https://tldw.sh/privacy),
[terms](https://tldw.sh/terms) and [support](https://tldw.sh/support).

The review cases in the manifest are a draft test plan, not a record of executed
host tests. Portal authentication, domain verification, a dedicated reviewer
account, real host evidence and a walkthrough recording must be completed before
submitting. No recording URL or successful-review status is fabricated here.
