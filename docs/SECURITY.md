# Security Notes

This repository is public. Before committing source or assets:
- Inspect the complete file and Git history for API keys, OAuth secrets, tokens, passwords and personal data.
- Never commit production credentials or private user information.
- Rotate any credential that was previously exposed.
- Confirm you have permission to publish all embedded images, fonts, audio and other assets.
- Keep production credentials in a secret manager, not in Blogger XML or Git.
- Treat third-party scripts and CDN assets as external dependencies; verify their ownership and integrity.

A basic scan of this XML did not detect common Google API key, GitHub token, OAuth secret or access-token patterns. That scan is not a comprehensive security audit.
