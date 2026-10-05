# Security policy

Novus | Nexum Laboratories Inc. — nnLabs ProjectAlpha.

## Reporting a vulnerability

Email **daniel@novusnexumlabs.com** with the subject `Security: <repository>`.

Do not open an issue, pull request or discussion about a vulnerability.

Include what is affected, how to reproduce it, and the impact you expect. We acknowledge reports within 3 business days.

## Rules for everyone with access

- Never commit secrets: API keys, tokens, passwords, private keys, signed URLs or `.env` files. Every repository runs a secret scan on each push and pull request, and push protection blocks known secret formats.
- Never commit real customer data, personal data or health information, including in test fixtures, screenshots and logs. Use obviously fake data.
- If you commit a secret by mistake, tell a maintainer immediately. The secret must be rotated first; removing it from history alone is not enough.
- Report a lost or compromised device or account the same day.
