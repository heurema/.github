# Security Policy

Heurema projects deal with AI agents, developer workflows, code context, permissions, and automation boundaries. Please treat security issues seriously even when a repository is experimental.

## Reporting a vulnerability

Do not open a public issue for a security vulnerability.

Preferred reporting path:

```text
security@heurema.dev
```

If this address is not active yet, use a private GitHub Security Advisory in the affected repository or contact the maintainer privately.

Please include:

- affected repository and version/commit;
- description of the issue;
- reproduction steps;
- potential impact;
- whether secrets, code, or private data may be exposed;
- suggested mitigation, if known.

## Scope

Security-sensitive issues include:

- secret exposure;
- unintended repository writes;
- agent permission escalation;
- prompt injection paths;
- unsafe tool invocation;
- dependency or supply-chain risk;
- bypass of approval gates;
- loss or falsification of audit evidence;
- unsafe default configuration;
- data leakage to external providers.

## AI-agent safety baseline

Heurema projects should default to:

- least privilege;
- explicit approval before destructive actions;
- no production access for early-stage agent workflows;
- no secrets in prompts, logs, fixtures, screenshots, or examples;
- clear logging of agent-visible context and actions;
- reproducible verification where practical;
- vendor-neutral configuration where possible.

## Response expectations

We aim to acknowledge serious reports quickly, but exact timing depends on maintainer availability. We will prioritize issues that can expose secrets, modify code without approval, bypass gates, or misrepresent verification evidence.
