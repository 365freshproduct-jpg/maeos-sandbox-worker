# MAEOS Sandbox Worker

Isolated GitHub-hosted runner used by MAEOS to verify public third-party code without exposing MAEOS server secrets.

- public repositories only
- no MAEOS secrets
- read-only repository permission
- short-lived GitHub-hosted runner
- no deployments, signing, wallets, payments, or cloud credentials
- test output is evidence only; a passing run is not proof of payment or bounty acceptance
