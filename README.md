# privacy-policy

Hosted privacy policies for [KawaNova](https://github.com/KawaNova) Android apps and Chrome extensions (GitHub Pages).

## Live site

- Index: https://kawanova.github.io/privacy-policy/
- OffMoji (com.kawanova.talktext): https://kawanova.github.io/privacy-policy/privacy.html
- Wanpo Alert (com.kawanova.wanpo_alert): https://kawanova.github.io/privacy-policy/WanpoAlert.html
- TabMarkList (Chrome): https://kawanova.github.io/privacy-policy/tabmarklist.html

## GitHub Pages setup

1. **Repository visibility**: GitHub Pages on **private** repos requires a paid GitHub plan (Pro/Team/Enterprise). For a policy-only repo with no secrets, **public** is recommended and works on free accounts.
2. In the repo: **Settings → Pages**
   - **Source**: Deploy from a branch
   - **Branch**: main
   - **Folder**: / (root)
3. Commit HTML at repo root (e.g. privacy.html, index.md for the listing page).
4. After the workflow completes, open the Pages URL shown under Settings → Pages.

This repo is configured with Pages from **main / root** (uild_type: legacy).

## Adding or updating a policy (Android)

Naming rule:

- `android-{slug}.md` — source / editable draft
- `android-{slug}.html` — published page for Play Console

Examples: `android-rakuphotoai.html`, `android-lazyfitnessai.html`

1. Add or edit both files at the repository root.
2. Link the HTML from `index.md`.
3. Push to `main`; Pages rebuilds automatically.
4. Register `https://kawanova.github.io/privacy-policy/android-{slug}.html` in Play Console.

Do **not** put Play Store policies only inside private app repos (Pages may be unavailable). Use this public `privacy-policy` repo.


## OffMoji source of truth (app repo)

The canonical draft for OffMoji lives in the app repository at docs/privacy.html. Copy changes here when the in-app or Play Console policy is updated.