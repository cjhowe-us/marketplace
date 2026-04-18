# cjhowe-us marketplace

Plugin marketplace for the cjhowe-us artifact + workflow ecosystem.

## Install

```bash
claude plugin marketplace add cjhowe-us/marketplace
claude plugin install artifact@cjhowe-us-marketplace
claude plugin install workflow@cjhowe-us-marketplace           # optional, requires artifact
claude plugin install artifact-github@cjhowe-us-marketplace    # optional, requires artifact
claude plugin install artifact-documents@cjhowe-us-marketplace # optional, requires artifact
claude plugin install env-setup@cjhowe-us-marketplace          # optional
claude plugin install rumdl@cjhowe-us-marketplace              # optional
```

## Plugins

| Plugin | Repo | Subdir | Purpose |
|--------|------|--------|---------|
| `artifact`           | [cjhowe-us/artifact](https://github.com/cjhowe-us/artifact)  | `artifact/`           | Core artifact primitive |
| `artifact-github`    | [cjhowe-us/artifact](https://github.com/cjhowe-us/artifact)  | `artifact-github/`    | GitHub backends |
| `artifact-documents` | [cjhowe-us/artifact](https://github.com/cjhowe-us/artifact)  | `artifact-documents/` | Document scheme + backends + templates |
| `workflow`           | [cjhowe-us/workflow](https://github.com/cjhowe-us/workflow)  | `workflow/`           | Workflow orchestration |
| `env-setup`          | [cjhowe-us/workflow](https://github.com/cjhowe-us/workflow)  | `env-setup/`          | Env-var onboarding helper |
| `rumdl`              | [cjhowe-us/rumdl-plugin](https://github.com/cjhowe-us/rumdl-plugin) | `.` | Markdown linting |

## License

Apache-2.0.
