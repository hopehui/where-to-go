# Where to go

A simple tool to pick a random place from your Google Maps saved list.

🔗 <a href="https://hopehui.github.io/where-to-go/" target="_blank">**where-to-go**</a>

---

## How it works

Google Maps doesn't let you export saved lists, so this app uses a bookmarklet — a small piece of JavaScript saved as a browser bookmark — to copy your place names directly from the Google Maps page. You paste them into the app, and it picks one at random and links you straight to it on Google Maps.

## Usage

### Desktop

1. Visit the app and drag the **Copy my places** button to your bookmarks bar — you only need to do this once
2. Go to your Google Maps saved list and scroll to the bottom so all places are loaded
3. Click the bookmarklet — it will copy all the place names to your clipboard
4. Paste into the app and hit **Pick a random place**
5. Your list is saved automatically and will still be there next time you visit

### Mobile

Bookmarklets don't work on mobile browsers, but you can transfer your list from desktop:

1. Set up your list on desktop following the steps above
2. Click **Copy link to list** — this generates a URL with your list encoded in it
3. Send that link to your phone (iMessage, WhatsApp, email, etc.)
4. Open the link on your phone — your list loads and saves automatically
5. Use the app normally on mobile from then on

## Notes

- The bookmarklet works by finding place name elements on the Google Maps page. If Google updates their UI the selector may need updating — open an issue if this happens
- The "Open in Google Maps" link uses Google's search API format (`maps/search/?api=1&query=...`) which resolves accurately for most named places
- Your list is saved in your browser's localStorage — it persists across sessions but is local to each device
- No data is stored or sent anywhere — everything runs in the browser
