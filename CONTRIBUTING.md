# Contributing

Novus | Nexum Laboratories Inc. — nnLabs ProjectAlpha.

Read `orgdocs` before your first contribution. It covers onboarding, agreements and development procedures in full. This file is the short version.

## Before you start

- Two-factor authentication is on for your GitHub account.
- Commit signing is set up. Commits on default branches must be signed (SSH or GPG).
- Your NDA and IP assignment are signed. Access to code repositories is granted only after that.

## Workflow

1. Branch from `main`: `feat/<short-name>`, `fix/<short-name>`, `docs/<short-name>` or `chore/<short-name>`.
2. Keep each pull request to one change. Small pull requests are reviewed faster.
3. Write commit messages in the imperative mood: `Add waitlist field validation`, not `Added` or `Adds`.
   Commits are authored under your own name and the email on your GitHub account. You are responsible for every line you commit, whatever tools helped you write it. Don't add AI tool co-author trailers or "generated with" lines; CI rejects them.
4. Open a pull request using the template. Link the issue or task it addresses.
5. CI (build and secret scan) must pass, and a code owner must approve. Resolve every review conversation.
6. A maintainer merges. History on `main` is linear (squash or rebase).

Direct pushes and force pushes to `main` are blocked.

## Code standards

- Production quality only. No stubs, mock implementations or placeholder logic in merged code. If something must wait, open an issue and reference it.
- Follow the language and formatting conventions already used in the repository.
- Add or update tests for behaviour you change, where the repository has tests.
- Use `pnpm` for JavaScript and TypeScript projects.
