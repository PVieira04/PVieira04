### Patrick Vieira: platform engineer, London

I build the platforms, infrastructure and identity systems that let a small team ship like a large one, with AI agents held to the same standard as people.

**[patrickjv.com](https://patrickjv.com)** · **[CV](https://patrickjv.com/cv)** ([PDF](https://patrickjv.com/cv.pdf)) · [LinkedIn](https://www.linkedin.com/in/patrickvieira/) · [hello@patrickjv.com](mailto:hello@patrickjv.com)

Most of my current work lives in private repositories. What it covers:

- **Internal developer platform for AI-assisted delivery**, built around a golden path from spec to merge: a Claude Code plugin and a versioned engineering-standards baseline rolled out to about 26 repositories, with tests first, a gate that stops an agent finishing until typecheck, lint and tests pass, and adversarial review by a second vendor's model.
- **Agent execution and evaluation platform**, in build on the same golden path: sandboxed runs with per-run credentials, durable dispatch and review gates.
- **Passkey and verifiable-credential identity**: did:web with WebAuthn passkeys and W3C Verifiable Credentials, in production as a sign-in.
- **Infrastructure as code** through Terraform Cloud and GitOps (plan on pull request, apply on merge, daily drift detection) across cloud and SaaS.
- **On-premises speech intelligence** on an NVIDIA DGX Spark: NeMo transcription, diarisation and voiceprint speaker naming.

**Ask an agent about me.** patrickjv.com is built to be read by AI assistants: [`llms.txt`](https://patrickjv.com/llms.txt), Markdown on request, schema.org data, and a remote MCP server at `https://patrickjv.com/mcp` (listed on the MCP Registry as `com.patrickjv/profile`).

The archived repositories below are from my 2022–23 retraining into software engineering, kept for the record.
