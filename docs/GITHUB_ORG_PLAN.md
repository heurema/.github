# Heurema GitHub Organization Plan

## Goal

Make the GitHub organization understandable in 30 seconds for three audiences:

1. **Potential clients** — small software teams that need safe AI-native delivery.
2. **Technical users** — engineers looking for local-first AI-agent tooling.
3. **Contributors** — builders who want to improve bounded, auditable agent workflows.

## Current positioning to keep

- `Craft, not conjuring.`
- Open-source AI agent tools.
- Auditable, bounded, trustworthy workflows.
- Discovery, accountability, context, tests, audit trail, failure ownership.

## Positioning to add

- `from business intent to verified code change`
- vendor-neutral AI delivery
- secure SDLC with agents
- proof-carrying changes
- local-first where sensitive
- process transformation, not just coding acceleration

## Recommended organization description

Short version:

```text
Bounded, auditable AI-agent systems for software delivery. Craft, not conjuring.
```

Alternative:

```text
Open-source tools for vendor-neutral AI-native software delivery.
```

## Recommended website field

Use one of:

```text
https://heurema.dev
https://goalrail.dev
https://github.com/heurema/goalrail
```

Until there is a proper landing page, point to `goalrail`.

## Recommended pinned repositories

Pin only six. The pins should explain the story, not merely show activity.

1. `goalrail` — flagship operating layer and commercial bridge.
2. `signum` — delivery pipeline and bounded AI-assisted development.
3. `proofpack` — proof-carrying CI gate.
4. `arbiter` — multi-model review/orchestration.
5. `nex` — cross-CLI plugin distribution.
6. `code-intel-kernel` or `agent-bench-lab` — evidence-backed context or evals.

If `ai-delivery-audit` or `goalrail-playbook` is created, pin it instead of one lower-level tool.

## Repo taxonomy

Use consistent prefixes or topics rather than many unrelated names.

### Product / operating layer

- `goalrail`
- `goalrail-playbook`
- `goalrail-examples`

### Agent runtime and workflow tools

- `signum`
- `arbiter`
- `proofpack`
- `nex`
- `emporium`

### Context and intelligence

- `code-intel-kernel`
- `context-pack-template`
- `legacy-codebase-onboarding`

### Governance and security

- `agent-permission-matrix`
- `ai-delivery-security-audit`
- `vendor-neutral-ai-sdlc`

### Evaluation and observability

- `agent-bench-lab`
- `proofpack`
- `evals-template`

### Field guides

- `teams-field-guide`
- `ai-sdlc-field-guide`

## Repository description rules

Every repo should answer:

```text
What is it?
Who is it for?
What problem does it solve?
Is it stable, experimental, or archived?
```

Recommended description pattern:

```text
[Status] [Object] for [audience] to [outcome] without [risk].
```

Examples:

```text
Experimental local-first code intelligence kernel for evidence-backed repository inspection.
```

```text
Proof-carrying CI gate for agent-assisted code changes.
```

```text
Field guide for small software teams adopting AI agents without losing accountability.
```

## Topics to standardize

Use a consistent set across repos:

```text
ai-agents
agentic-sdlc
ai-assisted-development
secure-sdlc
vendor-neutral-ai
local-first
ai-governance
evals
software-delivery
devtools
```

## Immediate cleanup checklist

- [ ] Replace org README with the new profile README.
- [ ] Upload `assets/heurema-avatar.png` as org avatar.
- [ ] Upload `assets/heurema-wordmark.svg` and `assets/heurema-mark.svg` to `.github/assets`.
- [ ] Set org description.
- [ ] Add website field.
- [ ] Pin the six recommended repos.
- [ ] Add default `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`, and issue templates to `.github`.
- [ ] Add topics/descriptions to key repos.
- [ ] Add `stability: experimental` or `stability: alpha` to repos that are not ready.
- [ ] Archive or unpin repos that distract from the story.
- [ ] Create a `goalrail-playbook` or `ai-delivery-audit` repo as the commercial entry point.

## Commercial bridge

Create one public repository that is not a product, but a lead magnet:

```text
heurema/ai-delivery-security-audit
```

Suggested contents:

```text
README.md
checklists/ai-delivery-readiness.md
checklists/agent-security.md
templates/sdlc-map.md
templates/context-package.md
templates/agent-permission-matrix.md
templates/roi-baseline.md
examples/agency-workflow.md
examples/saas-team-workflow.md
```

This repo should make a potential client think: “These people understand the real implementation problem.”

## Messaging hierarchy

### 5-second message

```text
heurema builds bounded, auditable AI-agent systems for software delivery.
```

### 15-second message

```text
We help teams move from business intent to verified code change by adding contracts, gates, proofs, and accountability around AI-assisted development.
```

### 60-second message

```text
AI coding tools help engineers write code faster, but they do not automatically improve delivery. Teams also need better intake, context packaging, review gates, security controls, evals, and proof that a change is safe. Heurema builds open-source tools and implementation patterns for vendor-neutral AI-native delivery without silent autonomy or security debt.
```
