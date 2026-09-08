# Selfcare Scan public site

This public repository publishes the marketing, support, privacy, and terms
pages for Selfcare Scan. It can stay public for GitHub Pages while the app's
source repository remains private.

## Files

- `app.html` — Marketing page
- `support.html` — Support page
- `index.html` — Privacy Policy
- `terms-of-use.html` — Terms of Use
- `styles.css` — Shared responsive styling

## App Store Connect links

Use these exact addresses for the app version:

- **Marketing URL:** `https://pavlopro7.github.io/selfcareai-privacy/app.html`
- **Support URL:** `https://pavlopro7.github.io/selfcareai-privacy/support.html`
- **Privacy Policy URL:** `https://pavlopro7.github.io/selfcareai-privacy/`

The Marketing URL and Support URL should be different pages. They can still
belong to the same GitHub Pages site.

## Additional public links

- **Privacy policy:** `https://pavlopro7.github.io/selfcareai-privacy/`
- **Delete data URL:** `https://pavlopro7.github.io/selfcareai-privacy/#delete-data`
- **Delete account URL:** `https://pavlopro7.github.io/selfcareai-privacy/#delete-account`
- **Terms of Use:** `https://pavlopro7.github.io/selfcareai-privacy/terms-of-use.html`

## GitHub Pages deployment

In the GitHub repository, open **Settings → Pages**, choose **Deploy from a
branch**, and select the `main` branch with the repository root (`/`). After a
push and deployment, the URLs above will become public.

## Account deletion API

The app sends authenticated deletion requests to:

`https://dvuhntbmzctmmumqaoqg.supabase.co/functions/v1/delete-account`

This is an API endpoint, not the public page for Google Play.

## Account controls

- **Reset skin data** removes the skin profile, scans, and cached thumbnail but
  keeps the account.
- **Delete account** permanently removes the account and its associated skin
  data. It does not cancel an active App Store or Google Play subscription.

Keep `03ppcv@gmail.com` active for support and deletion requests. Update the
legal pages whenever the app starts collecting or using data differently.
