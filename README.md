# Field Guide for Inquirers & Catechumens — SJOTL

The complete Field Guide + Metanoia Checklist as an installable web app for
St. John of the Ladder Orthodox Church.

## Publishing on GitHub Pages

1. Create a new GitHub repository (e.g. `sjotl-fieldguide`) and upload every
   file in this folder to its root (`index.html`, `manifest.webmanifest`,
   `sw.js`, and the four `.png` icons).
2. In the repository: **Settings → Pages → Source: Deploy from a branch →
   Branch: `main` / (root) → Save**.
3. After a minute the page is live at
   `https://<your-username>.github.io/sjotl-fieldguide/`
   (a custom domain like `guide.sjotl.org` can be added later under the same
   Pages settings).

To update the guide, just replace `index.html` and commit — visitors get the
new version on their next visit.

## Instructions to share with inquirers

> Open the link on your phone, then add it to your home screen:
>
> - **iPhone (Safari):** tap the Share button, then **Add to Home Screen**.
> - **Android (Chrome):** tap the ⋮ menu, then **Add to Home screen**
>   (or **Install app**).
>
> The Field Guide will appear as its own app with the gold ladder icon, works
> offline, and remembers your reading and checklist progress on that device.

## Notes

- Progress is saved per device/browser (localStorage). Clearing browser data
  clears progress.
- `manifest.webmanifest` gives the app its name, icon, and colors when
  installed. `sw.js` provides offline support. Both are optional for plain
  browsing — the page works as a simple link too.
- The print edition (`Field Guide Print Edition.html`, kept alongside this
  folder) is a separate white-background letterhead document for paper
  handouts; open it and print (Ctrl+P).
