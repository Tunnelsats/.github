# Security Policy

## Reporting a Vulnerability

We take the security and privacy of TunnelSats node operators seriously. If you discover a potential security or privacy vulnerability across any TunnelSats repository, client package, or API endpoint, please report it responsibly before disclosing it publicly.

### How to Report a Vulnerability

1. **GitHub Private Vulnerability Reporting (Recommended):**
   Open the **Security** tab of the affected `Tunnelsats` repository on GitHub and click **Report a vulnerability** to open a private, encrypted advisory thread with the maintainers.
2. **Encrypted Nostr DM (NIP-17 / NIP-59):**
   Send an encrypted direct message to our official Nostr pubkey:
   `npub1n9z4y3xjramqes8fp9rl96x5e4nl0hff57ynw7vqnjpq370tq78sljsp8y`
3. **Email:**
   Send a report to `security@tunnelsats.com` or `info@tunnelsats.com`.
4. **Community Channels (For Initial Coordinator Contact Only):**
   Reach out to an administrator in our [Armada Nostr Community](https://tunnelsats.com/join-armada) or [Telegram Group](https://tunnelsats.com/join-telegram) to request a direct contact channel (never post exploit details in public channels).

### What to Include in Your Report

- The affected repository, package version, or API endpoint.
- A clear description of the vulnerability and its potential impact (such as clearnet IP leakage, privilege escalation, or authentication bypass).
- Step-by-step reproduction instructions or a minimal proof-of-concept.

### Our Commitment

- **Acknowledgment:** We will acknowledge receipt of your report within 5 business days.
- **Remediation:** We will investigate, verify, and ship a fix as quickly as possible.
- **Coordinated Disclosure:** We ask that you keep vulnerability details confidential until a patch is released and node operators have had an opportunity to update.

### Supported Versions

Security updates are applied to the latest release on the default branch of each active repository:

| Version / Branch | Supported |
| :--- | :---: |
| Latest release / Default branch (`main` / `master`) | ✅ |
| Older releases and legacy `setupv2.sh` installs | ❌ |
