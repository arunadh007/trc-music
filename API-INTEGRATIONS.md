# API and External Integrations

This register is based on references and calls found in the supplied XML. A visible UI button is not treated as proof of a working integration.

| Service / interface | Purpose in source | Status |
|---|---|---|
| Blogger JSON feeds | Loads posts and pages from `/feeds/posts/default` and `/feeds/pages/default` | Implemented in theme; live behavior should be tested |
| Blogger comments | Uses Blogger's native comment widgets / scripts | Blogger-managed |
| PWA manifest | Loads `manifest.webmanifest` from the GitHub Pages jsDelivr CDN path | Referenced; verify file availability |
| Apple touch icon | Loads `trc-192.png` from the same CDN path | Referenced; verify file availability |
| Web Share API | Shares the current page when browser support exists | Implemented with clipboard fallback |
| Clipboard API | Copies current page URL as a fallback | Implemented with feature detection |
| WhatsApp `wa.me` | Opens a prefilled share message | Implemented as a share link, not WhatsApp login |
| Google sign-in | Button displays “will be available soon” toast | Placeholder; no OAuth flow found |
| Spotify sign-in | Button displays “will be available soon” toast | Placeholder; no OAuth flow found |
| WhatsApp sign-in | Button displays “will be available soon” toast | Placeholder; no authentication flow found |
| Email/password | Form displays “Account access will be available soon” | Placeholder; no authentication backend found |
| Password recovery | Displays “Password recovery will be available soon” | Placeholder |

## Credentials
No API key, OAuth client secret, access token, refresh token or Firebase configuration was detected by the basic source scan. This is not a guarantee that all secrets are absent. Review the full file and commit history before publishing.

Never put secrets in this public repository. Store credentials in the relevant provider's secret manager or GitHub Actions Secrets.
