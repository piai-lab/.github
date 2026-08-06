# Governance

## Purpose

πAI Lab exists to develop and steward an open, composable system of scientific capabilities that can support rigorous discovery across disciplines. Governance protects scientific credibility, continuity, interoperability, security, and the distinction between experiments and organization-backed projects.

## Roles

### Organization owners

Owners are custodians of the GitHub organization. They manage membership, security, billing, organization-wide policy, repository creation and transfer, and continuity of access. Owner access is deliberately rare.

The organization should maintain at least two trusted owners as soon as a second qualified custodian is appointed. Owners must use strong two-factor authentication and must not share accounts or credentials.

### Project maintainers

Each adopted repository must name at least one active maintainer. Maintainers own the roadmap, review and release process, dependency and security response, documentation quality, and lifecycle status of that repository.

Maintainers may make decisions within their repository, but may not represent private opinions as organization policy or weaken organization-wide security and evidence requirements.

### Capability coordination

πAI Lab projects may address different parts of the research process, including data, methods, evidence, agent systems, scientific artifacts, research intelligence, evaluation, and domain workflows. The scientific lead and affected maintainers coordinate shared contracts, cross-project dependencies, public positioning, and integration decisions.

No project automatically owns another project because it consumes or integrates its capabilities. A capability may be used through OmniMind or another research environment while remaining independently reusable through documented interfaces.

### Scientific stewards

Projects making domain-specific scientific claims should identify reviewers or stewards with relevant expertise. Scientific stewards review claim boundaries, evidence provenance, evaluation design, and known limitations. This role does not replace engineering review.

### Contributors

Contributors participate through issues, discussions, code, documentation, evaluation, data, design, or scientific review. Contribution does not automatically confer organization membership or governance authority.

## Decision-making

Projects should prefer documented, reversible decisions and rough consensus among affected maintainers. A maintainer records material decisions in an issue, pull request, or architecture decision record.

Organization-wide decisions require owner review. Decisions involving scientific integrity, security, privacy, licensing, repository transfer, shared capability contracts, public naming, or public claims must not be made by silent assumption.

When consensus fails, the accountable maintainer decides within a project; organization owners decide matters that cross repositories or affect the organization itself. The decision and dissenting evidence should remain documented.

## Cross-capability decisions

Changes that affect more than one project must identify the scientific use case, affected interfaces, compatibility and migration impact, provenance and permission requirements, validation evidence, failure behavior, and accountable maintainers. Integration must not erase the standalone scope, evidence boundary, or lifecycle status of a contributing capability.

## Conflicts of interest

Reviewers should disclose financial, institutional, authorship, competitive, or personal interests that could reasonably affect a decision. A conflicted person may provide evidence but should not be the sole approver.

## Changes to governance

Governance changes are proposed by pull request in this repository. The proposal must explain the problem, affected roles or projects, migration impact, and rollback path. At least one organization owner approves the final change.
