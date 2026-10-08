### Patrick Vieira: AI platform engineer, London

I build the platforms, infrastructure and identity systems that let a small team ship like a large one, and I hold the AI agents writing that team's code to the same standard as people.

**[patrickjv.com](https://patrickjv.com)** · **[CV](https://patrickjv.com/cv)** ([PDF](https://patrickjv.com/cv.pdf)) · **[Writing](https://patrickjv.com/writing/)** · [LinkedIn](https://www.linkedin.com/in/patrickvieira/) · [hello@patrickjv.com](mailto:hello@patrickjv.com)

Most of my current work lives in private repositories. What it covers:

- **Internal developer platform for AI-assisted delivery**, built around a golden path from spec to merge: a Claude Code plugin and a versioned engineering-standards baseline rolled out to about 26 repositories, with tests first, a gate that stops an agent finishing until typecheck, lint and tests pass, and adversarial review by a second vendor's model.
- **Agent execution and evaluation platform**, being built on the same golden path: sandboxed runs with per-run credentials, durable dispatch and review gates.
- **Passkey and verifiable-credential identity**: did:web with WebAuthn passkeys and W3C Verifiable Credentials, in production as a sign-in.
- **Infrastructure as code** through Terraform Cloud and GitOps (plan on pull request, apply on merge, daily drift detection) across cloud and SaaS.
- **On-premises speech intelligence** on an NVIDIA DGX Spark: NeMo transcription, diarisation and voiceprint speaker naming.

**Ask an agent about me.** [patrickjv.com](https://patrickjv.com) is built to be read by AI assistants: [`llms.txt`](https://patrickjv.com/llms.txt), Markdown on request, schema.org data, and a remote MCP server at `https://patrickjv.com/mcp` (listed on the MCP Registry as `com.patrickjv/profile`). Its [source is public](https://github.com/PVieira04/patrickjv-eng-site): static assets and the MCP server on Cloudflare Workers, 110+ tests and a production smoke monitor.

**Writing:** [Holding agent-written code to the same standard as anyone's](https://patrickjv.com/writing/gating-agent-written-code) · [Rehearse the restore, time the rollback](https://patrickjv.com/writing/rehearse-the-restore)

**Python:** [marine-forecast-service](https://github.com/PVieira04/marine-forecast-service), a public snapshot of a service that has emailed twice-daily ensemble forecasts to a yacht at sea since February 2026 (AIS position lookup, Cloudflare Worker cron, D1 send log, watchdog).

My 2022–23 retraining projects are archived under Repositories, kept for the record.
