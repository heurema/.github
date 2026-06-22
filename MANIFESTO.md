# The Heurema Manifesto

## Craft, not conjuring

AI agents are not magic workers. They are fast, fallible executors. The more work we delegate to them, the more discipline we need around intent, scope, context, verification, security, and accountability.

Heurema exists to make agentic software delivery trustworthy enough for real teams.

## The problem

Most teams start with AI in the wrong layer. They buy an AI coding tool, give it repository context, and hope delivery gets faster.

Sometimes it does. Often it creates a new kind of chaos:

- vague tasks become confident wrong code;
- code review becomes a hallucination cleanup process;
- generated tests prove the wrong thing;
- sensitive context leaks into tools without policy;
- prompts become undocumented production infrastructure;
- nobody can explain why an agent changed something;
- teams get tool adoption without process improvement.

The bottleneck is rarely the model alone. The bottleneck is the operating system around the model.

## Our belief

Agentic work must be bounded before it is automated.

A good AI delivery workflow defines:

1. the business intent;
2. the delivery contract;
3. the allowed context;
4. the allowed tools;
5. the human owner;
6. the verification evidence;
7. the risk level;
8. the approval gate;
9. the rollback path;
10. the learning loop.

This is how software teams move from demos to dependable delivery.

## Principles

### 1. Discovery before automation

Do not automate broken work. First understand where value is lost: unclear requirements, context gaps, missing tests, slow review, weak release discipline, or poor ownership.

### 2. Accountability is not delegatable

Agents can draft, inspect, transform, test, and propose. Humans remain accountable for product intent, security posture, production risk, and business outcomes.

### 3. Context is a product

The quality of agent output depends on context design. Context must be curated, versioned, minimal, reviewable, and safe to share.

### 4. Boundaries beat prompts

A prompt asks. A boundary constrains. Reliable agent workflows need scope limits, permissions, budgets, allowed actions, and explicit stop conditions.

### 5. Verification is part of the work

A task is not done when an agent says it is done. A task is done when it carries evidence: tests, static checks, security scans, review notes, traces, and known limitations.

### 6. Silent autonomy is a defect

Agent actions must leave receipts. Teams need to know what was read, what was changed, which tools were called, what checks passed, and where humans approved.

### 7. Security gates before scale

Unsafe acceleration compounds risk. Agent workflows must respect secrets handling, data classification, least privilege, dependency review, and rollback.

### 8. Vendor-neutral by design

A team should be able to change models, IDEs, orchestration layers, vector stores, and cloud providers without rewriting its delivery process from scratch.

### 9. Local-first where it matters

Sensitive code, customer data, business logic, and proprietary context should remain local or inside controlled boundaries unless the team has an explicit reason and policy.

### 10. No magic claims

We do not promise that AI will replace teams or cut development cost by a fixed percentage. We measure cycle time, review time, rework, defects, adoption, model/tool cost, and delivery proof.

## What we build

Heurema builds open-source tools, templates, and field methods for:

- AI-native software delivery;
- agent workflow governance;
- delivery contracts;
- context packaging;
- proof-carrying changes;
- adversarial review;
- local-first agent tooling;
- vendor-neutral AI adoption;
- evals and observability;
- secure SDLC with AI agents.

## What we reject

We reject:

- black-box autonomy in production workflows;
- tool-first transformation;
- unverifiable AI claims;
- prompts that become undocumented infrastructure;
- agents with broad permissions and no audit trail;
- vendor lock-in disguised as convenience;
- replacing process design with model worship.

## The outcome

The outcome we want is simple:

> A team can take a business intent, turn it into a bounded delivery contract, let agents assist within safe limits, and receive a verified code change with evidence.

That is craft.
