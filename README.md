# library-template

This repository is the starter template for reusable libraries, packages, SDKs, and shared modules in the `SaagarPatelOne` organization.

It stays language-agnostic, but it assumes the repository will expose an interface that other code depends on.

## What this template gives you

- the org baseline for CI, secret scanning, and pull-request hygiene
- lightweight contribution and security guidance
- CODEOWNERS and editor defaults
- a minimal package-friendly starting point without forcing a release system too early

## Good fit

- shared libraries
- packages published internally or publicly
- SDKs and client utilities
- reusable modules that need compatibility discipline

## First edits to make

1. Replace this README with installation, usage, and compatibility guidance.
2. Document the supported environments, runtimes, or versions.
3. Add real test and release steps once the language and packaging strategy are chosen.
4. Clarify the public API surface early so changes are easier to review.

## Baseline expectations

- Keep the default branch as `main`.
- Prefer pull requests for non-trivial changes.
- Be explicit about breaking changes and compatibility.
- Add release notes once the package starts being consumed by other repos.
