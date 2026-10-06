# flick-legal

Public legal documents for the Flick iOS app, in eight languages
(he, en, es, fr, de, pt, ru, ar):

- `privacy/<lang>/` — Privacy Policy (Hebrew is authoritative)
- `terms/<lang>/` — Terms of Use (Hebrew is authoritative)
- `privacy/` and `terms/` — language chooser that redirects by browser language.
  `https://ofekmoshco.github.io/flick-legal/privacy/` is the Privacy Policy URL
  entered in App Store Connect.

The pages are generated from one structured source per language (same sections,
same order). The app opens `/<doc>/<lang>/?app=1` in an in-app sheet (`?app=1`
hides the language switcher). Pages are drafts until reviewed by a lawyer.
