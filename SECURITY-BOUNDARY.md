# Security And Public Release Boundary

This repository is public. It must stay safe to read, clone, archive, and share.

## Do Not Publish

- API keys, OAuth secrets, SSH keys, cookies, passwords, seeds, private access tokens, or private credentials.
- Database URLs, internal admin URLs, private deployment paths, raw logs, backups, or server-only configuration values.
- Matrix signing keys, recovery keys, Synapse secrets, database credentials, TURN secrets, or appservice tokens.
- Private ZMath / CallChat Shield implementation code.
- Private ZeroThink prompts, private model routing prompts, hidden policy files, or non-public prompt libraries.
- Raw private DNA files, customer files, vault files, payment records, support screenshots with sensitive data, or user account exports.
- Exploit instructions or operational detail that would make live services easier to attack.
- Unrelated private work.

## Good Public Update Style

- Explain what changed for users.
- Explain where people can try it or read more.
- Keep the architecture high level.
- Use cautious language for security and research claims.
- Mention model families and public product roles only when helpful.
- Keep protected implementation details out of public commits.

## ZMath / Shield Boundary

Public docs may describe:

- user-visible behaviour
- threat models
- file container goals
- entitlement and licensing concepts
- compatibility boundaries
- standard cryptographic posture at a high level

Public docs must not disclose:

- proprietary source
- internal derivation logic
- private keys or salts
- bypass instructions
- license enforcement implementation details
- server-only policy code

## Security Contact

Use the public contact route for security or privacy reports:

https://docs.talktoai.org/contact/
