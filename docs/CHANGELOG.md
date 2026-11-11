# Changelog

## v1.0.0 — Archived source baseline

This release documents what is present in the supplied XML snapshot, not a comparison against earlier versions.

### Added / present in this snapshot
- TRC Music Blogger theme with a dark, electric-violet music-app design.
- Responsive app shell with header, menu and bottom navigation.
- Home, Discover, Library, Liked, Player and Profile screens.
- Blogger feed loading from `/feeds/posts/default` and `/feeds/pages/default`.
- Song-card artwork and a swipe interaction that reveals lyrics.
- Client-side song-list text filtering.
- Like-button visual toggle and share actions using the Web Share API / clipboard where supported.
- WhatsApp share link generation through `wa.me`.
- PWA manifest and Apple touch icon references hosted through jsDelivr.
- Profile Login / Sign Up tab UI with Full Name hidden by default and shown in Sign Up mode.
- Violet-themed authentication field and heading styling.

### Important limitations confirmed in source
- Email/password form submission is a placeholder toast: account access is not connected to a backend.
- Google, Spotify and WhatsApp sign-in buttons are placeholder actions, not configured OAuth authentication.
- Forgot Password is a placeholder toast.
- Audio play controls change their visual state; the source explicitly says audio playback will connect when a backend is added.
- Comments display a placeholder message that backend connection is pending.

### Notes
- The uploaded XML parses as well-formed XML.
- No previous source revision was supplied, so this file is an archived baseline rather than a verified diff.
