# Habbet developer website

Use this folder as the root of a public static site for Play Console and AdMob verification.

## Files

- `index.html` - simple developer website landing page
- `app-ads.txt` - AdMob authorized seller entry

## Publish

Place these files at the root of a public site and make sure the `app-ads.txt` file is reachable at:

- `https://your-domain.com/app-ads.txt`

If you use GitHub Pages, prefer a user/organization site or a custom domain so the file is served from the site root. A project URL like `https://username.github.io/Habbet/` is usually not the right shape for `app-ads.txt` verification because the file needs to be at the domain root.

## Required Play Console step

Add the same public website URL in your app's Google Play listing under the developer website / contact details field.
