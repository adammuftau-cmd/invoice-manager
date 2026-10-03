# Business Invoice & Receipt Manager (PWA)
1. **Create repo**: github.com → New repository → name it (e.g. `invoice-manager`) → Public.
2. **Upload**: Add file → Upload files → drag ALL files/folders from this project (keep folder structure) → Commit.
3. **Enable Pages**: Settings → Pages → Branch `main`, folder `/ (root)` → Save. Your site: `https://<user>.github.io/<repo>/`.
4. **Install**: open the site in Chrome (Android/desktop) → menu → *Install app* / *Add to Home screen*. Visit once online so it caches for offline use.
5. **Update**: re-upload changed files and bump `V` in `service-worker.js` (e.g. `bim-v2`).
6. **Backup**: Settings → *Backup data* saves `business-backup-DATE.json`. Do this regularly.
7. **Restore**: Settings → *Restore data* → choose the JSON file → confirm (replaces current data).
8. **PDF**: use Print on an invoice/receipt and choose *Save as PDF*.
