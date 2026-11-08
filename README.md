# beemosaic-legal

Public legal documents for the mobile game **Bee Mosaic** (`com.ragendom.beemosaic`),
published by **Ragendom** (Ronald Farkas, Hungary).

Served by GitHub Pages from the `docs/` folder on `main`.

| Document | URL |
|---|---|
| Landing | https://ragendom69.github.io/beemosaic-legal/ |
| Privacy Policy | https://ragendom69.github.io/beemosaic-legal/privacy/ |
| Terms of Use | https://ragendom69.github.io/beemosaic-legal/terms/ |

## Where these URLs go

- **Google Play Console** -> App content -> Privacy policy -> the privacy URL
- **In-game** -> Settings -> Privacy Policy / Terms of Use
- Store listing description footer (optional but good practice)

## Editing

Plain static HTML, no build step, no dependencies, no trackers.
Edit the file, commit to `main`, and GitHub Pages redeploys within a minute or two.

When you change anything material, update **both** the `Last updated` date in the
page header and announce the change in-game before it takes effect.

## Keep in sync

The Privacy Policy must stay consistent with the **Google Play Data safety** form.
If you add, remove or swap an SDK (ad network, analytics, attribution), update both together.

Currently declared SDKs: **Google AdMob** (with the User Messaging Platform), **Google Play Billing**
(via Unity In-App Purchasing), **Unity engine**.
