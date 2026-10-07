# Security Policy

## Reporting a Vulnerability

If you believe you have found a security vulnerability in an ArbiSee OS project, please report it privately rather than opening a public issue.

For BinHardS, send vulnerability reports to:

security@os.arbisee.com

Please include enough information to reproduce and understand the issue, such as:

- affected project and version or commit
- affected platform or binary format, when relevant
- steps to reproduce
- security impact
- proof-of-concept material, when safe to provide
- any suggested mitigation or fix

Please do not include credentials, private keys, or unrelated sensitive information.

## Coordinated Disclosure

Please allow the maintainers an opportunity to investigate and address a reported vulnerability before publicly disclosing details.

When a report concerns a third-party dependency or another component outside the maintainers' control, the maintainers may coordinate with the relevant upstream project.

## Scope

This policy covers security vulnerabilities in ArbiSee OS projects and their maintained infrastructure.

For BinHardS, examples include vulnerabilities in the scanner's command-line processing, binary parsing or analysis that can cause security-impacting behavior, CI/CD or release configuration that could compromise project artifacts, and dependencies when the project is affected through its use of them.

Reports about a binary being flagged or not flagged by a heuristic are generally product-quality issues unless they create a security vulnerability in the scanner or its surrounding infrastructure.

## Public Issues

Please avoid publishing sensitive vulnerability details in a public GitHub issue before the maintainers have had an opportunity to investigate.

For non-sensitive bugs, false positives, feature requests, and other normal development issues, use the project's regular issue tracker.