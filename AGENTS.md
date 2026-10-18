# Working on the Row & Reason organization profile

This public repository owns the Row & Reason GitHub organization profile.
It does not automatically supply agent instructions to other repositories.

## Work tracking and communication

- Track all work in Linear. Read the matching issue before starting; create it
  when missing, reuse existing issues, and keep scope, status and blockers current.
  Link branches/PRs and relevant project work. Do not ask the user to file it.
- For new issues, use Linear's tools to discover, read and apply the standard
  **Work**, **Bug** or **Investigation** template. Fill its prompts and omit unused
  sections. Report unavailable Linear access/templates as a blocker.
- In issues, comments, project descriptions and updates, lead with the outcome,
  current state and next action/decision. Use concise paragraphs and useful
  headings/lists. Preserve decisions and reasons, material results (units,
  denominators, conditions), uncertainties and limitations.
- Maintain one current summary; link detailed evidence in named Linear documents
  or authoritative repo records. Comment on meaningful changes, not tool calls or
  unchanged progress. Put completion/replacement and successor links first.

## Engineering practice

- Inspect Git status and preserve unrelated work. Prefer small changes, supported
  APIs and maintained upstream components over speculative abstractions.
- Consult the relevant official docs below and installed guides, matching versions
  to manifests/lockfiles. Follow documented best practices; explain material
  deviations in Linear. Read only the references relevant to the task.
- Run appropriate checks and behavioral tests, update affected docs, and report
  passed/failed/not-run checks and limitations. Local checks do not prove live
  deployment. Existing production and approval boundaries still apply.

## Scope and validation

- `profile/README.md` is the public GitHub organization profile; the root README
  also contains company copy. Keep factual claims and product links consistent.
- Preserve the established voice and branding. Do not publish unverified legal,
  customer, availability or performance claims. Never include private operational
  information, credentials or customer data in this public repository.
- For documentation-only changes, check Markdown, relative paths, external links
  and the rendered profile. There is no application build or test suite here.
- This repository's AGENTS.md governs this repository only; other repositories
  retain their own root instructions.

## Official technology documentation

| Area | Official documentation |
| --- | --- |
| Organization profile | [GitHub organization profiles](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile), [GitHub Markdown](https://docs.github.com/en/get-started/writing-on-github) |
| Tracking | [Linear issue templates](https://linear.app/docs/issue-templates), [Linear MCP](https://linear.app/docs/mcp) |
