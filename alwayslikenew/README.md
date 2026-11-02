# AlwaysLikeNew.com

Live page: https://alwayslikenew.com/

- `listings.json` holds the items shown on the page (Facebook, Depop and eBay). The page loads it from GitHub, so editing this file updates the site within a few minutes without touching GoDaddy.
- Facebook item photos and videos are in `photos/` here. The page loads them through the jsDelivr CDN. Depop and eBay photos load straight from those sites. Give new photos new file names, since the CDN can keep serving an old copy of a replaced file.
- `index.html` is the copy of the page uploaded to GoDaddy. It only needs re-uploading if the design changes.
