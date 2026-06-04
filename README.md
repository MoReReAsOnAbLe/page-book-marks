# Bookmarks Home Page

A clean, single-file bookmark dashboard you can set as your browser's home page or new-tab page. Click a box to open a site in a new tab, and use each box's **Pages ▾** drop-down to jump to that site's specific pages — ranked by how often you open them from here.

## Features

- **Bookmark boxes** — click to open the site in a new tab.
- **Per-site page ranking** — expand a box to see its tracked pages. Every click is counted, and pages re-sort so your most-visited ones rise to the top (e.g. "Anthropic on X — 100 visits").
- **Folders / groups** — organize bookmarks into folders. A pill row at the top filters by folder (`All` shows everything). Create, rename, and delete folders inline. Deleting a folder keeps its bookmarks (they move to "No folder").
- **Drag to reorder** — grab the grip handle (⠿) on a card to reorder bookmarks. Drag a card onto a folder pill to move it into that folder, or onto `All` to ungroup it.
- **Easy add / edit / delete** — for both bookmarks and their pages; assign a folder right from the add/edit dialog.
- **Auto favicons** — each site's icon is fetched automatically, with a colored letter tile as fallback.
- **Search** — filter bookmarks instantly (press `/` to focus).
- **Light / dark theme** — follows your system, toggle in the ⋯ menu.
- **Backup** — export/import all your data as JSON from the ⋯ menu.
- **No server, no build, no tracking** — everything lives in one HTML file and your browser's `localStorage`.

## How "most-viewed pages" works

Browsers block web pages from reading your real browsing history (for privacy). So this app counts the clicks you make **through this dashboard**. Add the specific pages you care about under a bookmark, and every time you open one from here its counter goes up and the list re-ranks.

## Use it

1. Open `index.html` in your browser.
2. (Optional) Set it as your home page / new-tab page:
   - Save the file somewhere permanent and point your browser's home-page setting at its `file://` path, **or**
   - Host it (GitHub Pages, Netlify, etc.) and use that URL.
3. Add your bookmarks, expand a box, and add the pages you visit most.

Your data is stored per-browser. Use **Export backup** to move it between machines.
