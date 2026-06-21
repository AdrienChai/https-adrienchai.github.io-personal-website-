# Publish this site at adrienchai.github.io/personal-website/

You already have a site at the root (`adrienchai.github.io`). This guide adds
this new site as a **subfolder** so it lives at
`adrienchai.github.io/personal-website/` without touching your existing site.

## 1. Open your existing repo
Go to GitHub and open the **`adrienchai.github.io`** repository (the one that
already powers your root site).

## 2. Upload the folder
1. Click **Add file → Upload files**.
2. Drag the **whole `personal-website` folder** from `Documents/Claude Code/`
   into the upload area — drag the *folder*, not just the file, so GitHub keeps
   the `personal-website/` structure.
3. Click **Commit changes**.

GitHub Pages is already on for this repo, so no settings changes are needed.

## 3. Visit your site
After ~1 minute, reload:

**https://adrienchai.github.io/personal-website/**

(Note the trailing slash.)

## Why the earlier 404 happened
The `personal-website` folder only existed on your computer. GitHub Pages can
only serve files that are actually committed to the repo, so the URL had nothing
to point at until you upload the folder.

---

### Optional cleanup
Dragging the whole folder also uploads this `DEPLOY-github-pages.md`. It's
harmless (it won't show on your site), but you can delete it from the repo
afterward if you want things tidy.

### Updating later
Re-upload an edited `index.html` into the `personal-website/` folder
(Add file → Upload files → Commit). Changes go live within a minute.

### Note on links
This site uses only relative links, so it works correctly in a subfolder — no
path changes are needed.
