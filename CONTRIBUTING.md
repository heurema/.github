# Contributing to Heurema

Heurema contributions should make AI-agent workflows more bounded, auditable, secure, or useful.

## What we value

We prefer contributions that improve:

- clear delivery boundaries;
- verification evidence;
- local-first behavior;
- security and least privilege;
- reproducibility;
- vendor neutrality;
- practical team adoption.

## Before opening a pull request

For small fixes, open a PR directly.

For new tools, broad rewrites, or behavior changes, open an issue first and describe:

1. the problem;
2. the workflow affected;
3. the proposed boundary;
4. the security impact;
5. how the change will be tested;
6. any vendor-specific assumptions.

## Pull request checklist

- [ ] The change has a clear scope.
- [ ] The README/docs are updated if behavior changed.
- [ ] Tests or reproducible checks are included where possible.
- [ ] New dependencies are justified.
- [ ] No secrets, customer data, or private context are included.
- [ ] The change does not create hidden vendor lock-in.
- [ ] Failure modes and rollback are documented for risky changes.

## AI-assisted contributions

AI-assisted code is acceptable only when the contributor remains responsible for the result.

If AI materially helped produce the change, please verify:

- generated code is understood by the contributor;
- licenses and dependencies are acceptable;
- tests or manual checks were run;
- security-sensitive changes received extra review.

## Tone

Be direct, specific, and respectful. We optimize for clear engineering discussion, not performative certainty.
