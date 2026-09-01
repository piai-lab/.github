# Project policy

## Admission baseline

A repository may enter πAI Lab only when it has:

1. A clear scientific or infrastructure purpose consistent with the organization mission.
2. A named maintainer who accepts ongoing responsibility.
3. A reproducible entry point: installation, environment, example, or testable workflow.
4. An explicit license and documented provenance for code, data, models, and external assets.
5. A written evidence boundary separating verified behavior, evaluation results, interpretation, and aspiration.
6. Basic quality gates appropriate to the project, such as tests, linting, type checks, benchmark scripts, or data validation.
7. Security, privacy, and sensitive-data handling notes when relevant.
8. A maintenance status and a credible path for issues, releases, and deprecation.
9. A declared role in the broader research process, including upstream dependencies, intended consumers, integration boundaries, and whether the capability can be used independently.

Repository transfer is not a substitute for admission review. Experimental or personal work should remain outside the organization until the baseline is met.

## Project roles

Organization projects may contribute to one or more roles:

- scientific data and method infrastructure;
- evidence and research-intelligence systems;
- agent architecture and continuous research environments;
- scientific communication and editable research artifacts;
- question formation and evaluation research;
- domain programs and reusable capability packs;
- benchmarks, validation, reproducibility, and governance artifacts.

These roles describe scientific responsibility, not a product hierarchy. Projects may remain independently useful while participating in larger cross-project workflows.

## Interoperability and evidence

A project that exposes a reusable capability should document:

- its inputs, outputs, versions, applicability conditions, and permissions;
- provenance, validation, resource requirements, and known limitations;
- explicit failure returns, recovery or fallback behavior, and human review points;
- the interface contract and compatibility policy used by consuming agents or products;
- the evidence supporting any claim of integration, reliability, adoption, or scientific value.

Planned integration is not completed integration. Shared naming, an API wrapper, a demonstration, or use by one agent does not establish an organization-wide capability. Public claims must follow released interfaces and reproducible evidence.

## Lifecycle states

Every project should declare one of these states in its README:

- **Incubating:** direction is promising, interfaces may change, and adoption carries higher risk.
- **Adopted:** maintained organization project with documented scope, releases, and support boundaries.
- **Flagship:** strategically important, actively maintained, and held to the strongest evaluation and release standards.
- **Maintenance:** stable but receiving limited feature development; critical fixes remain supported.
- **Archived:** no longer maintained. The repository stays readable with a final status and migration guidance when available.

## Promotion

Promotion requires evidence, not age or repository popularity. The maintainer submits a short review covering scientific value, users, reproducibility, evaluation, ownership, security, licensing, and maintenance capacity. Organization owners approve admission and flagship designation.

## Transfer and naming

Before transfer, maintainers must review package names, container registries, documentation URLs, citations, badges, automation secrets, release workflows, and downstream references. Redirects are useful but are not a complete migration plan.

Repository names should be stable, pronounceable, and specific enough to avoid misleading scope. Names must not imply clinical, regulatory, institutional, or scientific validation that the project has not earned.

Shared naming or participation in a larger workflow does not by itself imply public availability, maturity, integration, endorsement, or flagship status.

## Deprecation and archival

Projects are deprecated when their central assumptions fail, maintenance ownership disappears, a successor replaces them, or unresolved risk makes continued use misleading. Deprecation should include a visible notice, final supported version, known risks, and successor guidance where possible.
