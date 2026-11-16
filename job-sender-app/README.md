# Driver Job Sender (installable app)

Static web app: no server, no database. Bookings, tours and drivers stay on each device.

## Put it online (free, one-off)

### Option A: GitHub Pages
1. Create a new public repo, e.g. `job-sender`.
2. Upload everything in this folder (keep the `icons/` folder).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
4. After a minute it's live at `https://<your-username>.github.io/job-sender/`.

### Option B: Netlify
1. Sign in at netlify.com (free) → Add new site → Deploy manually.
2. Drag this folder onto the page. You get a `https://<name>.netlify.app` link.

## Install it

- **Android (Chrome):** open the link → ⋮ menu → **Install app** / **Add to Home screen**.
- **iPhone (Safari):** open the link → Share → **Add to Home Screen**.
- **Laptop (Chrome or Edge):** open the link → install icon at the right of the address bar (or ⋮ → Cast, save and share → **Install page as app**).

## Updating later
Replace the changed files, then bump `VERSION` in `sw.js` (e.g. `job-sender-v2`).
Installed copies pick up the update the next time they're opened online.

## Phone + laptop
Tours and drivers are saved per device. Set them up on one, then
Tours tab → **Copy backup** → paste into the other device's Backup box → **Restore**.
