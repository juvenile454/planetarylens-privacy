# PlanetaryLens Privacy Policy

Public, bilingual privacy policy for the Android app **PlanetaryLens** (`de.timo.planetarylens`).

- Site: <https://juvenile454.github.io/planetarylens-privacy/>
- Policy in `index.html`: **PlanetaryLens 0.9, 0.9.1, 0.9.2 and 1.0**, updated **6 October 2026**. Clarifies direct provider requests, email handling, optional data and the right to object. The revised 1.0 build disables automatic EmojiCompat font initialization; earlier installed versions remain covered.
- Privacy and support contact: `PlanetaryLens@web.de`
- App source code, signing material and user data are **not** part of this repository.

The site is a self-contained static HTML document. English and German contain the same privacy information. It uses no first-party cookies, analytics, external fonts or external scripts.

The page is generated from the Android project's `docs/privacy-policy.md` and `docs/privacy-policy.en.md` by `scripts/prepare_release.py` as `store/privacy/index.html`. Keep web and offline wording synchronized; do not maintain a separate manual translation here. Generation does not publish anything.

GitHub Pages deploys from `main`. After each publication, fetch the public URL and compare its bytes and SHA-256 with this file; a Git commit alone does not prove deployment.
