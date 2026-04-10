# Where to eat

A simple tool to pick a random place from your Google Maps saved list.

🔗 **[where-to-eat](https://hopehui.github.io/where-to-eat/)**

---

## How it works

Google Maps doesn't let you export saved lists, so this app uses a bookmarklet — a small piece of JavaScript saved as a browser bookmark — to copy your place names directly from the Google Maps page. You paste them into the app, and it picks one at random and links you straight to it on Google Maps.

## Usage

1. Visit the app and drag the **Copy my places** button to your bookmarks bar — you only need to do this once
2. Go to your Google Maps saved list and scroll to the bottom so all places are loaded
3. Click the bookmarklet — it will copy all the place names to your clipboard
4. Paste into the app and hit **Pick a random place**

## Notes

- The bookmarklet works by finding place name elements on the Google Maps page. If Google updates their UI the selector may need updating — open an issue if this happens
- The "Open in Google Maps" link uses Google's search API format (`maps/search/?api=1&query=...`) which resolves accurately for most named places
- No data is stored or sent anywhere — everything runs in the browser
