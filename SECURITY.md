# Security policy

## Scope and support

This repository is a legacy sample application, not a bank or payment service.
Its .NET Core 3.1 applications are out of support; no production security support
or response-time guarantee is provided. Do not deploy them with real accounts,
credentials, or customer data.

Reports are in scope when they affect this repository's code or GitHub Actions
workflows. The repository cannot investigate or change bank systems, external
accounts, or tokens issued by third parties.

## Reporting a vulnerability

If GitHub's private vulnerability reporting is enabled, use the repository's
**Security** tab to submit a report. Otherwise, contact the maintainer through a
non-public channel. Do not publish exploit details, credentials, private keys,
tokens, or personal/customer data in an issue.

Include the affected file or version, impact, and a minimal reproduction that
does not use real accounts or data. Revoke any credential that has been exposed.

## Deployment

Before any deployment, migrate to a supported .NET version, remove sample
credentials, conduct an independent security review, and use only provider-issued
test credentials and endpoints until the integration is formally authorized.
