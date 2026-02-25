# cofy-x `.github`

This repository powers the **cofy-x organization profile** and provides default community health files for repositories that do not define their own.

## What This Repository Controls

- **Organization profile page**: [`profile/README.md`](profile/README.md)
- **Default community files** (fallback for org repositories):
  - `CODE_OF_CONDUCT.md`
  - `CONTRIBUTING.md`
  - `SECURITY.md`
  - `SUPPORT.md`
  - `.github/ISSUE_TEMPLATE/*`
  - `.github/pull_request_template.md`

GitHub applies these defaults only when a target repository has not overridden them locally.

## Maintainer Workflow

1. Update templates and policy files in this repository.
2. Keep links and contact channels GitHub-first (Issues, Discussions, Security Advisories).
3. Use clear, repo-agnostic language so templates are valid across all cofy-x projects.
4. When a specific repository needs special rules, define local files in that repository to override these defaults.

## Organization Profile

- English: [`profile/README.md`](profile/README.md)
- 简体中文: [`profile/README.zh-CN.md`](profile/README.zh-CN.md)

## License

Licensed under [Apache License 2.0](LICENSE).
