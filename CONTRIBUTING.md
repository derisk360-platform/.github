# Contributing

## Development Flow

1. Create a branch from `main` using `type/ticket-short-description`.
2. Keep pull requests small enough to review in one sitting.
3. Include tests for behavioral changes.
4. Update documentation when interfaces, configuration, or operational behavior changes.
5. Request review from the owning team.

## Pull Request Requirements

- At least two approvals for production repositories
- CODEOWNERS approval for owned paths
- Passing `lint`, `test`, and `build` checks
- No unresolved conversations
- No high or critical security alerts introduced by the change

## Commit Standards

Use concise conventional commits where practical:

```text
feat(api): add customer risk endpoint
fix(ci): pin docker build action
chore(deps): update python dependencies
```

## Security

Do not commit credentials, tokens, private keys, customer data, or production exports. If a secret is committed, rotate it immediately and notify support@derisk360.com.
