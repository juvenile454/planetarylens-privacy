# PlanetaryLens Privacy Policy

Public, bilingual privacy policy for the Android app **PlanetaryLens** (`de.timo.planetarylens`).

- Site: <https://juvenile454.github.io/planetarylens-privacy/>
- Policy in `index.html`: **PlanetaryLens 0.9, 0.9.1, 0.9.2, 1.0 and 1.0.1**, updated **27 October 2026** (controller address changed to the legal address c/o Block Services, Stuttgarter Str. 106, 70736 Fellbach; no change to data processing). Preserves provider-log, email, optional-data and objection disclosures and explains the server-only VIIRS/MODIS fire-feed transition, with the app's legacy-feed request only after HTTP 404. Build 1.0.1 carries forward the EmojiCompat startup protection prepared for the revised 1.0 build; the original 1.0 and earlier installed versions remain covered. No source-control URL is configured, so no control file is requested or stored.
- Privacy and support contact: `PlanetaryLens@web.de`
- App source code, signing material and user data are **not** part of this repository.

The site is a self-contained static HTML document. English and German contain the same privacy information. It uses no first-party cookies, analytics, external fonts or external scripts.

The page is generated from the Android project's `docs/privacy-policy.md` and `docs/privacy-policy.en.md` by `scripts/prepare_release.py` as `store/privacy/index.html`. Keep web and offline wording synchronized; do not maintain a separate manual translation here. Generation does not publish anything.

GitHub Pages deploys from `main`. After each publication, fetch the public URL and compare its bytes and SHA-256 with this file; a Git commit alone does not prove deployment.
