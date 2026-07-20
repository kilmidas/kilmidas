# kilmidas

I maintain [OSS Maintainer Evidence](https://github.com/kilmidas/oss-maintainer-evidence), a local, read-only CLI that turns public GitHub maintenance activity into source-linked Markdown and JSON reports.

[![CI](https://github.com/kilmidas/oss-maintainer-evidence/actions/workflows/ci.yml/badge.svg)](https://github.com/kilmidas/oss-maintainer-evidence/actions/workflows/ci.yml)
[![CodeQL](https://github.com/kilmidas/oss-maintainer-evidence/actions/workflows/codeql.yml/badge.svg)](https://github.com/kilmidas/oss-maintainer-evidence/actions/workflows/codeql.yml)
[![Release](https://img.shields.io/github/v/release/kilmidas/oss-maintainer-evidence)](https://github.com/kilmidas/oss-maintainer-evidence/releases/latest)
[![License](https://img.shields.io/github/license/kilmidas/oss-maintainer-evidence)](https://github.com/kilmidas/oss-maintainer-evidence/blob/main/LICENSE)

## Project

- [Source and documentation](https://github.com/kilmidas/oss-maintainer-evidence)
- [Latest release](https://github.com/kilmidas/oss-maintainer-evidence/releases/latest)
- [v0.3.0 Markdown example](https://github.com/kilmidas/oss-maintainer-evidence/blob/main/examples/oss-maintainer-evidence-v0.3.0.md)
- [v0.3.0 JSON example](https://github.com/kilmidas/oss-maintainer-evidence/blob/main/examples/oss-maintainer-evidence-v0.3.0.json)

## Maintenance workflow

I use Codex locally to reproduce issues, write regression tests, review changes, and prepare release candidates. Project changes go through public pull requests, Node.js 22 and 24 CI, dependency review, CodeQL scanning, package-install verification, checksummed and attested release artifacts, and signed-out evidence-link verification. Codex assists the workflow; I review and authorize public repository changes and releases.

For reproducible bugs and feature requests, use the project [issue tracker](https://github.com/kilmidas/oss-maintainer-evidence/issues). For vulnerabilities, follow the project [security policy](https://github.com/kilmidas/oss-maintainer-evidence/security/policy) and use private vulnerability reporting.
