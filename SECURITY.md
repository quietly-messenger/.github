# Security Policy

Quietly is a messenger built around end-to-end encryption, so we take security reports seriously and want to make it easy to report issues responsibly.

## Supported Versions

Quietly is in early, active development. There are no stable releases yet — please report vulnerabilities against the `main` branch of the relevant repository (`quietly-server`, `quietly-client`, or `quietly-crypto`). Once versioned releases exist, this section will be updated with which versions receive security fixes.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, use **GitHub Security Advisories**:

1. Go to the relevant repository (e.g. `quietly-messenger/quietly-server`).
2. Open the **Security** tab.
3. Click **"Report a vulnerability"**.

This opens a private disclosure channel visible only to you and the maintainer, so the issue can be investigated and fixed before it's public.

If you're unsure which repository a vulnerability belongs to (for example, something in the cryptographic protocol design rather than a specific implementation), it's fine to open the advisory on `quietly-server` — it will be redirected to the right place.

## What to Include

To help us investigate quickly, please include as much of the following as you can:

- A description of the vulnerability and its potential impact
- Steps to reproduce, or a proof of concept
- The affected repository, commit, or version
- Any suggested mitigation, if you have one

## What to Expect

- We aim to acknowledge new reports within **a few days**.
- We'll keep you updated as the issue is investigated and fixed.
- We ask for reasonable time to ship a fix before any public disclosure. We're a small, early-stage project, so please bear with us on timelines — but we won't go silent on you.
- With your permission, we're happy to credit you for the finding once it's disclosed.

## Scope

This policy covers all repositories under the `quietly-messenger` organization, including the client, server, and cryptographic core. Given that Quietly's core promise is end-to-end encryption, reports involving the cryptographic protocol, key handling, or the federation trust model are especially welcome — even if they're more of a design concern than an exploitable bug.

Thank you for helping keep Quietly and its users safe.
