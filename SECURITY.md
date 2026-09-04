# Security policy

## Reporting a vulnerability

Please report suspected vulnerabilities privately through GitHub's security
advisory feature instead of opening a public issue. Include reproduction steps,
affected versions, and any suggested mitigation.

## Credential handling

- Keep API keys in a local `.env` file copied from `.env.example`.
- Never commit `.env`, tokens, credentials, or exported provider configuration.
- Treat any credential committed to Git as compromised, revoke it with the
  provider, and issue a replacement.
- Use repository or environment secrets for CI and deployment credentials.
