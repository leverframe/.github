# leverframe/.github

Org-level shared assets: reusable workflows consumed by all leverframe repos.

- `format.yml` — reusable format gate (markdown prettier check). Repos opt in with a 5-line caller workflow.
- `gitleaks.yml` — reusable secret scan (binary install, not the licensed action).

Caller stub:

```yaml
name: format-gate
on:
  pull_request:
  push:
    branches: [main]
jobs:
  format:
    uses: leverframe/.github/.github/workflows/format.yml@main
    permissions:
      contents: read
```
