# Contributing

Thank you for improving πAI Lab projects. Contributions may include code, documentation, evaluation, data curation, design, issue triage, or scientific review.

## Before starting

1. Read the target repository's README, contribution guide, license, and current lifecycle status.
2. Search existing issues and pull requests.
3. Open an issue before substantial work, interface changes, new dependencies, data redistribution, or claims that affect scientific interpretation.
4. Keep changes focused and explain how they were validated.

For a defect in one capability, use that repository's issue tracker. For work that crosses data, methods, evidence, agent execution, or scientific artifacts, first identify the research workflow, affected repositories, interface owner, and compatibility boundary. If no public repository clearly owns the problem, use the organization contact in [`SUPPORT.md`](SUPPORT.md).

## Cross-capability contributions

New capabilities and material interface changes should explain:

- the scientific task and the researcher or agent that will consume the capability;
- why an existing capability or interface is insufficient;
- inputs, outputs, provenance, permissions, validation, and failure behavior;
- compatibility, migration, rollback, and maintenance responsibility;
- whether the capability is independently reusable or tied to a specific workflow.

Do not present planned interoperability as an existing integration. Shared naming or a claimed connection to an organization-backed research environment requires organization-level review of scope, evidence, naming, and maintenance; it is not established by code reuse alone.

## Scientific and technical evidence

Contributions must distinguish:

- observed results from interpretation;
- source evidence from derived claims;
- supported use cases from speculation;
- benchmark performance from real-world validity;
- software correctness from scientific or clinical validity.

Include reproducible commands, inputs, environment details, tests, benchmarks, or source references appropriate to the change. Do not commit confidential data, credentials, restricted datasets, or material without redistribution rights.

## AI-assisted contributions

AI-assisted work is welcome when it is reviewed rather than forwarded. Contributors remain responsible for correctness, provenance, licensing, security, and scientific claims. Generated code, text, citations, data, or images must be checked against primary evidence and project policy.

## Pull requests

A pull request should state:

- the problem and why it matters;
- the chosen approach and important trade-offs;
- validation performed and results;
- scientific, security, compatibility, or migration risks;
- any remaining limitations.

Maintainers may request changes or decline work that lacks evidence, duplicates the roadmap, creates unsustainable maintenance, or exceeds the project's scope.
