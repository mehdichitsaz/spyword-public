# SpyWord Public Pages

Modern public-facing web pages for **SpyWord** (iOS), including the official **Support** and **Privacy Policy** URLs used for distribution.

## Live Pages

- Home: https://mehdichitsaz.github.io/spyword-public/
- Support: https://mehdichitsaz.github.io/spyword-public/support/
- Privacy Policy: https://mehdichitsaz.github.io/spyword-public/privacy/
- app-ads.txt: https://mehdichitsaz.github.io/spyword-public/app-ads.txt

## Purpose

This repository hosts lightweight static pages and public release notes for:

- presenting SpyWord publicly with a polished landing page,
- providing the official support destination,
- publishing the official privacy policy,
- documenting high-level product updates that are safe to share publicly.

## Latest Public Update

- **Version:** 1.2.0
- **Highlights:** new category content, localization polish, iOS premium UI improvements, and App Store submission/readiness fixes.
- **Details:** see [`CHANGELOG.md`](./CHANGELOG.md).

## Local Preview

From the repository root:

```bash
python3 -m http.server 8080
```

Then open:

- http://localhost:8080/
- http://localhost:8080/support/
- http://localhost:8080/privacy/

## Project Structure

```text
.
├── index.html           # Landing page
├── support/index.html   # Support page
└── privacy/index.html   # Privacy policy page
```

## Maintenance Notes

- Keep contact email consistent across pages: `spyword.app@gmail.com`.
- Keep support/privacy paths stable (`/support/` and `/privacy/`) so store metadata links remain valid.
- Keep pages static and lightweight (no heavy frameworks) for reliability and fast load times.

## AdMob app-ads.txt

- File path in repo: `app-ads.txt`
- Current line (must remain exact):
  `google.com, pub-7251371733383885, DIRECT, f08c47fec0942fa0`
- Current public URL on this project site:
  `https://mehdichitsaz.github.io/spyword-public/app-ads.txt`

> Note: If App Store Connect's **Developer Website** uses a different domain, app-ads.txt must be reachable at that domain root (`https://<domain>/app-ads.txt`).
