# Privacy and terms

Legal pages for Selfcare Scan live here so they stay separate from the
skincare notes in the main `docs` folder.

## Files

- `index.html` — Privacy Policy
- `terms-of-use.html` — Terms of Use

## Google Play links

Use the published Privacy Policy address for the **Privacy policy** field.
Check the address in an incognito window before submitting it; do not assume a
GitHub Pages address from the repository name.

For **Delete account URL**, use the Privacy Policy address followed by
`#delete-account`. The public page already contains that section.

## Account deletion API

The app sends authenticated deletion requests to:

`https://dvuhntbmzctmmumqaoqg.supabase.co/functions/v1/delete-account`

This is an API endpoint, not the public page for Google Play.

## Account controls

- **Reset skin data** removes the skin profile, scans, and cached thumbnail but
  keeps the account.
- **Delete account** permanently removes the account and its associated skin
  data. It does not cancel an active Google Play subscription.

Keep `03ppcv@gmail.com` active for support and deletion requests. Update the
legal pages whenever the app starts collecting or using data differently.
