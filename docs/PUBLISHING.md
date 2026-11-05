# Public content boundary

Publish only high-level project descriptions, generic setup steps, and fictional examples.

Exclude credentials, authentication exports, session tokens, private keys, real environment configuration, infrastructure identifiers, private endpoints, deployment topology, access policies, internal plans, operational logs, customer records, employee information, organization names, and private contact information.

Write public examples from scratch. Do not copy private configuration and assume removing obvious secrets is sufficient. Field names, identifiers, comments, and commit metadata can also reveal private information.

Before each update:
1. Review every staged file and its complete content.
2. Validate JSON and check for secrets and identifying details.
3. Check commit author information and remove unintended personal metadata.
4. Keep private repository history, generated bundles, screenshots, exports, and logs out of the public repository.

The ignore rules reduce accidental additions; they do not sanitize files or remove already tracked content. If a secret is ever published, revoke or rotate it immediately and review repository history.
