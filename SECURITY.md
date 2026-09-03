# Security Policy

This policy applies to every repository in the **Teifi-Digital** GitHub organization
unless a repository publishes its own `SECURITY.md`.

## Reporting a vulnerability

**Do not open a public issue or pull request for a security problem.**

| You are | Report via |
| --- | --- |
| Teifi staff | `security@teifi.com`, or page on-call through incident.io for anything live |
| Client or partner | Your Teifi delivery contact, or `security@teifi.com` |
| External researcher | `security@teifi.com` |

Please include, where you can: affected repository or URL, a description of the issue,
reproduction steps or a proof of concept, and the impact you believe it has.

## What happens next

| Stage | Target |
| --- | --- |
| Acknowledgement of your report | 2 business days |
| Triage, severity assigned, owner named | 5 business days |
| Remediation plan shared with the reporter | 10 business days |

Critical issues affecting production are handled as incidents and start immediately,
outside the targets above.

## Scope

In scope: source code, build and deploy pipelines, and Teifi-operated services in
this organization's repositories.

Out of scope: findings against third-party platforms we build on (Shopify, hosting
providers, SaaS vendors). Please report those to the vendor directly. Automated
scanner output with no demonstrated impact is also out of scope.

## Supported versions

Teifi repositories are client applications and internal services rather than
released libraries. Only the currently deployed revision of each application is
supported; fixes ship to the deployed branch and are not backported.

## Our own controls

Dependency vulnerabilities are tracked with Dependabot alerts and security updates
across the organization, reviewed as part of SOC 2 monitoring. Access to repositories
is granted by team through the `github-access` Terraform configuration; every
access change goes through a reviewed pull request.

## Safe harbour

We will not pursue or support legal action against anyone who reports a vulnerability
in good faith, stays within the scope above, avoids accessing or modifying data that
is not theirs, and gives us reasonable time to fix the issue before disclosing it.
