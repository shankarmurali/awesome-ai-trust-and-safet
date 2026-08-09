# Awesome AI Trust & Safety

> A curated list of resources for defending AI systems and platforms against abuse — AI security, prompt injection, payment fraud, account integrity, and trust & safety practice.

Maintained by practitioners, for practitioners. Every entry earns its place by being something a working defender would actually use. Contributions welcome — see [Contributing](#contributing).

## Contents

- [Frameworks & Standards](#frameworks--standards)
- [Incident Databases](#incident-databases)
- [Foundational Research](#foundational-research)
- [Security Tools](#security-tools)
- [Threat Intel & Abuse Data Feeds](#threat-intel--abuse-data-feeds)
- [Blogs & Practitioner Voices](#blogs--practitioner-voices)
- [Newsletters & Podcasts](#newsletters--podcasts)
- [Communities & Conferences](#communities--conferences)
- [Fraud & Payments](#fraud--payments)

## Frameworks & Standards

- [OWASP GenAI Security Project](https://genai.owasp.org/) — Home of the LLM Top 10 and the Agentic Applications Top 10; the shared vocabulary for AI application risk.
- [MITRE ATLAS](https://atlas.mitre.org/) — Adversarial threat landscape for AI systems; ATT&CK's sibling for ML.
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) — The reference governance framework for AI risk.

## Incident Databases

- [AI Incident Database](https://incidentdatabase.ai/) — The long-running general registry of AI harms.
- [AI Agent Incident Tracker](https://shankarmurali.github.io/ai-agent-incidents/) — Structured, sourced records of agentic failures: destructive actions, injection exploits, supply-chain compromises.

## Foundational Research

- [Not what you've signed up for (Greshake et al., 2023)](https://arxiv.org/abs/2302.12173) — The paper that defined indirect prompt injection.
- [Universal and Transferable Adversarial Attacks on Aligned Language Models (Zou et al., 2023)](https://arxiv.org/abs/2307.15043) — The GCG jailbreak paper; adversarial suffixes that transfer across models.
- [Simon Willison's prompt injection series](https://simonwillison.net/series/prompt-injection/) — The running practitioner's record of the problem since it was named.

## Security Tools

- [garak](https://github.com/NVIDIA/garak) — LLM vulnerability scanner; probes models for known failure modes.
- [PyRIT](https://github.com/Azure/PyRIT) — Microsoft's Python risk identification toolkit for red-teaming generative AI.
- [promptfoo](https://github.com/promptfoo/promptfoo) — Test and red-team LLM apps with declarative evals.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — Programmable guardrails for LLM applications.
- [LLM Guard](https://github.com/protectai/llm-guard) — Input/output scanning toolkit for LLM interactions.

## Threat Intel & Abuse Data Feeds

- [abuse.ch URLhaus](https://urlhaus.abuse.ch/) — Free feed of malicious URLs.
- [OpenPhish](https://openphish.com/) — Phishing intelligence feed.
- [PhishTank](https://phishtank.org/) — Community-verified phishing URL database.
- [Have I Been Pwned](https://haveibeenpwned.com/) — Credential-breach corpus underpinning account-takeover defense.
- [Spamhaus](https://www.spamhaus.org/) — The long-standing abuse and reputation datasets.

## Blogs & Practitioner Voices

- [Embrace the Red](https://embracethered.com/) — Johann Rehberger's working exploits against production AI agents.
- [KrebsOnSecurity](https://krebsonsecurity.com/) — Cybercrime economics: carding, mules, and the fraud supply chain.
- [DoublePulsar](https://doublepulsar.com/) — Kevin Beaumont on active exploitation, increasingly AI-adjacent.
- [Nicholas Carlini](https://nicholas.carlini.com/) — Adversarial ML research and rigorous skepticism.
- [Frank on Fraud](https://frankonfraud.com/) — Fraud-scheme analysis, including AI-enabled scams.
- [Techdirt](https://www.techdirt.com/) — Platform governance and trust & safety policy analysis.
- [Signal Desk daily brief](https://github.com/shankarmurali/signal-desk) — Auto-generated daily digest across many of the voices above; fork it with your own roster.

## Newsletters & Podcasts

- [tl;dr sec](https://tldrsec.com/) — Weekly security engineering digest with strong AI security coverage.
- [Unsupervised Learning](https://danielmiessler.com/) — Daniel Miessler on security and AI.
- [Risky Business](https://risky.biz/) — The long-running security news podcast.
- [Fraudology](https://podcasts.apple.com/us/podcast/fraudology-podcast-with-karisse-hendrick/id1530461089) — Karisse Hendrick on fraud fighting and CNP crime.

## Communities & Conferences

- [Trust & Safety Professional Association](https://www.tspa.org/) — The professional home of T&S, and the host of TrustCon.
- [Integrity Institute](https://integrityinstitute.org/) — Community of integrity workers from across platforms.
- [AI Village](https://aivillage.org/) — The DEF CON village where AI security red-teaming grew up.
- [Merchant Risk Council](https://merchantriskcouncil.org/) — The payments fraud and risk professional community.

## Fraud & Payments

- [About-Fraud](https://about-fraud.com/) — Practitioner community and vendor landscape for anti-fraud.
- [Journal of Online Trust and Safety](https://tsjournal.org/) — Peer-reviewed research on online abuse and platform integrity.

## Contributing

One pull request per suggestion. Each entry needs: a working link, a one-line description saying what it *is* and why a defender would use it, and placement in the right section. Quality bar: would a working practitioner bookmark this? No product pitches, no exploit code, no paywalled-only resources unless they're genuinely canonical.

## License

[CC0 1.0](LICENSE) — public domain dedication, as is customary for awesome lists.
