# SpyWord Public Pages

Modern public-facing web pages for **SpyWord** (iOS), including the official **Support** and **Privacy Policy** URLs used for distribution.

## Live Pages

- Home: https://mehdichitsaz.github.io/spyword-public/
- Support: https://mehdichitsaz.github.io/spyword-public/support/
- Privacy Policy: https://mehdichitsaz.github.io/spyword-public/privacy/

## Purpose

This repository hosts lightweight static pages for:

- presenting SpyWord publicly with a polished landing page,
- providing the official support destination,
- publishing the official privacy policy.

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
