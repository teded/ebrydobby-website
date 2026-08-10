# Ebry Dobby Website

Static site for `www.ebrydobby.com`.

## Branding
- Official Ebry Dobby logo included at `assets/images/ebry-dobby-logo.png`.
- Logo is used in the header and footer across all pages.

## Pages
- Home
- Plates
- Support
- Privacy
- Contact

## Monetization
AdSense publisher loader is included on each page using `ca-pub-4069077007727159`.
The root `ads.txt` contains the Google authorized-seller entry.

## Store links
- Google Play: https://play.google.com/store/apps/details?id=com.ebrydobby.app.plates.free
- Apple App Store: https://apps.apple.com/us/app/plates-family-travel-game/id1335335602

## Local preview
```bash
python3 -m http.server 8080
```
Open http://localhost:8080

## GitHub Pages
1. Create a repo such as `ebrydobby-website`.
2. Push this folder to the default branch.
3. Settings → Pages → Deploy from a branch → default branch → `/ (root)`.
4. Set custom domain to `www.ebrydobby.com`.
5. Update DNS at IONOS after GitHub shows the required records.
6. Keep the old site live until the new custom domain is ready, then switch DNS.

## Before final production launch
- Reconcile the draft privacy policy with current app-store privacy disclosures.
- Add real Plates screenshots / brand artwork.
- Confirm AdSense site approval and ad-serving status.
- Add analytics only after choosing the desired provider.

## v3 changes
- Updated the Plates privacy policy to match the supplied January 1, 2024 policy.
- Added privacy-by-design language and data-deletion guidance.
- Added a privacy highlights section to the homepage.
