# Contributing to OnixResearch projects

This guide supplies organization-wide defaults. The target repository's contribution instructions, licensing, publication policy, and required checks take precedence.

## Before making a change

- Read the repository's README, contributor documentation, and any applicable `AGENTS.md` instructions.
- Check the intended branch and its status. A source-only publication may not be the development upstream; follow its documented contribution route.
- Search existing issues and pull requests. Discuss substantial behavior, API, architecture, or dependency changes before implementing them.
- Use the repository's pinned toolchain and documented development environment. There is no organization-wide build or test command.

## Bug reports and proposals

Open issues in the affected repository when its issue tracker is enabled.

For a bug, include the commit or release, environment, minimal reproduction, expected and observed behavior, and relevant redacted output. For a proposal, explain the concrete problem, intended behavior, and alternatives considered.

Do not publish credentials, personal data, private source, private host details, or unredacted logs. For security-sensitive reports, follow the repository's security reporting instructions; use GitHub's private vulnerability reporting when the repository offers it. Do not put vulnerability details in a public issue.

## Changes and verification

- Keep each pull request focused on one problem. Reuse existing patterns and avoid unrelated cleanup or generated-file churn.
- Update affected callers and documentation when changing a public contract.
- Follow the repository's change-management process. If it uses Cairn, use its native `.cairn/` workflow and repository-selected policy rather than introducing another specification layout.
- Run the relevant documented checks and exercise the changed behavior. Include regression coverage for consumer-visible bugs where practical.
- Record exact commands and results. Identify checks not run and their blockers; distinguish observations from assumptions.
- Keep proof, provenance, and release claims bound to the exact source and toolchain they cover. Do not relabel historical evidence as verification of a new revision.

## Pull requests

Describe the problem, change, compatibility or migration impact, and verification. Link the relevant issue or change record. Keep private information out of the patch, commit history, screenshots, and attachments.

Contributions remain subject to the target repository's own license and contribution terms. This shared guide does not change those terms or imply release approval.
