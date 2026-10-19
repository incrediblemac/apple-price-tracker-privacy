# Privacy Policy — Apple Price Tracker for Amazon Deals & Alerts

**Last updated: October 19, 2026**

This privacy policy covers the Chrome extension **"Apple Price Tracker for Amazon Deals & Alerts"** (the "Extension").

## Summary

The Extension does not collect, store, or sell any personal information. There are no user accounts, no analytics, and no tracking of any kind.

## What the Extension stores

All Extension data is stored **locally on your device** using Chrome's extension storage:

- Your **watchlist** (product IDs, prices, and dates of products you choose to watch)
- Your **price drop alerts** (generated locally on your device)
- Your **preferences** (selected region, theme, notification settings)
- **Cached product listings** (for example the current deals list, kept for up to 12 hours so the Extension loads quickly)

None of this data is transmitted to us or to any third party.

### Optional Chrome Sync

If you enable **"Sync Across Devices"** in Settings, your watchlist is stored in your own Google account via Chrome's built-in sync (`chrome.storage.sync`). This data goes to Google's Chrome Sync service under your Google account — we never see it and have no access to it. This feature is off by default and can be disabled anytime, which also deletes the synced copy.

### Backup files

**Export** saves your watchlist as a JSON file on your computer, and **Import** reads a file you choose. Both happen entirely on your device; nothing is uploaded.

## Network requests

The Extension fetches Apple product listings, prices, and deal information from our API server at **technewsprice.com**. These requests:

- contain **no personal information and no identifiers** — only what is needed to show you prices: the Amazon store you selected, product IDs, search terms, or (if you enable the Amazon page button, below) the product ID of the Amazon page you are viewing
- are standard HTTPS requests; like any web server, ours processes your IP address transiently for rate limiting and abuse prevention, and does not use it to identify or profile you

**Product images** are loaded directly from Amazon's image servers (`media-amazon.com`), as they are on Amazon's own site. Amazon receives a normal image request, including your IP address, under [Amazon's privacy notice](https://www.amazon.com/gp/help/customer/display.html?nodeId=GX7NJQ4ZB8MHFRNJ). When you click a link to a product, it opens on Amazon in a new tab.

## Optional Amazon page button

If you enable the **"Amazon Page Button"** in Settings (off by default), the Extension runs a small script on Amazon product pages that:

- reads **only the product ID (ASIN) from the page address**, and sends that ID to our API server to check whether it is an Apple product we track
- does **not** read, collect, or modify any other page content, and does **not** track your browsing — nothing is stored about which pages you visited

You can turn this off anytime in Settings, which removes the script and the associated permission.

## Notifications

Price drop notifications are generated locally on your device by comparing prices you watch. They can be disabled in Settings.

## Affiliate disclosure

Links to Amazon in the Extension are affiliate links. As an Amazon Associate, we earn from qualifying purchases. This does not involve any collection of your personal data by us.

## What we do NOT do

- No collection of personal information
- No user accounts or server-side profiles
- No analytics or telemetry
- No browsing history tracking
- No selling or sharing of data with third parties
- No advertising

## Changes to this policy

Any changes will be posted on this page with an updated date.

## Contact

Questions about this policy: open an issue on this repository, or email **fullscreendev@gmail.com**.

## About us

Apple Price Tracker is made by the team behind [TechStoriesIndia.com](https://techstoriesindia.com/), covering tech news, launches and how-tos, and [TechStoriesIndia.in](https://techstoriesindia.in/), covering gadget launches, specs and buying guides.

---

*This extension is not affiliated with, endorsed by, or sponsored by Amazon or Apple Inc.*
