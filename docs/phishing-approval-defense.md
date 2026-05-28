# Phishing Approval Defense

Canonical HTML: https://czb.com/phishing-approval-defense.html

Phishing approval defense focuses on suspicious wallet interactions, misleading signing prompts and authorization patterns that can expose user funds or project operations.

## Common Risk Patterns

- Unexpected `approve`, `permit` or `setApprovalForAll` requests.
- Lookalike domains and fake claim pages.
- Front-end injection or replaced contract addresses.
- Social engineering that pushes urgent signing.
- Unlimited token approvals without clear user intent.

## Defensive Actions

- Preserve the suspicious URL, screenshots, transaction data and timestamp.
- Review contract address, spender address and token scope.
- Revoke unnecessary high-risk approvals when appropriate.
- Notify affected users with clear wording and verified links.
- Add monitoring for repeated domains, contracts and address clusters.

## Boundary

Public guidance should focus on user protection, evidence preservation and risk reduction. Avoid publishing exploit steps that enable abuse.
