# Contributing to Awesome Internet Freedom

Thank you for helping build the most comprehensive internet freedom resource list.

## How to Submit

### Option 1: Open an Issue

[Open an issue](../../issues/new?template=submit-resource.yml) with details about the resource you'd like to add.

### Option 2: Submit a Pull Request

1. Fork this repository
2. Add your resource to the appropriate section in `README.md`
3. Follow the format: `- [Name](URL) — Short description.`
4. Submit a pull request

## Guidelines

### What belongs here

- Tools for circumventing internet censorship
- Platforms measuring or documenting censorship
- Encrypted communication tools
- Privacy-preserving software (VPN, DNS, email, browsers, OS)
- Mesh networking and decentralized infrastructure
- AI agent frameworks and communication protocols
- Research organizations studying digital rights
- Open datasets related to censorship
- Developer libraries for building freedom technology
- Policy organizations defending internet freedom
- Whistleblower platforms and file sharing tools
- Metadata removal and document security tools

### What doesn't belong here

- Commercial products without a free/open-source component or clear public benefit
- Tools primarily designed for surveillance or offensive use
- Abandoned projects (no updates in 2+ years, unless historically significant)
- Resources behind paywalls with no free tier

### Quality standards

- The resource must be actively maintained or historically significant
- It must serve a legitimate internet freedom purpose
- Descriptions should be factual and concise (one sentence)
- Links must be to official sources (not mirrors or forks)
- No duplicate entries

### Formatting

```markdown
- [Tool Name](https://example.com) — One-sentence description ending with a period.
```

- Use an em dash (—) between the link and description
- End descriptions with a period
- Keep descriptions under 150 characters when possible
- Place entries alphabetically within their section, or by significance/adoption

## Code of Conduct

Be respectful. This project exists to support human rights and digital freedom. Contributions that undermine these values will not be accepted.

## File Map

| File | Purpose |
|------|---------|
| `README.md` | Main curated list (human-readable) |
| `agents.json` | Structured data for programmatic access |
| `llms-full.txt` | Full text index for large LLM context windows |
| `llms.txt` | Compact summary for smaller context windows |
| `AGENTS.md` | Instructions for AI agents |
| `TRANSPARENCY.md` | Relay threat model and centralization audit |

When adding resources, update `README.md` — the other files will be regenerated periodically.
