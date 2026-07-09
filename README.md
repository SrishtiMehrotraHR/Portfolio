# Portfolio Website

A single-page portfolio site showcasing all seven projects: RecruiterCopilot, SQL and Excel recruitment analytics, and the full HR Operations lifecycle series (Onboarding, Leave & Attendance, Exit/Offboarding, Compliance Calendar).

## What's inside

- `index.html` — the whole site (self-contained: HTML, CSS, and JS in one file)
- `assets/` — dashboard screenshots for each Excel project, plus your résumé PDF for the download button

## How to publish it for free — GitHub Pages

1. Create a new GitHub repo (e.g. `portfolio` or `srishtimehrotra`)
2. Upload `index.html` **and** the entire `assets` folder (keep the folder structure exactly as-is — the page links to `assets/...`, so if that folder moves, images and the résumé link will break)
3. Go to the repo's **Settings → Pages**
4. Under "Source," select **Deploy from a branch** → branch **main** → folder **/ (root)** → **Save**
5. GitHub will give you a live URL, usually in this format:
   ```
   https://SrishtiMehrotraHR.github.io/portfolio/
   ```
   (It can take 1–2 minutes to go live the first time.)

## Before you publish — quick checklist

- [ ] Open `index.html` in a browser first and click every link (all six project repos, RecruiterCopilot live app, LinkedIn, email, résumé) to confirm nothing 404s
- [ ] Confirm all six HR Ops / analytics repos are public (a private repo link will 404 for visitors)
- [ ] Once live, add this URL to your LinkedIn profile's "Featured" section and to your résumé

## Making changes later

Everything — text, links, colors — lives in `index.html`. It's plain HTML/CSS, so any text editor works; no build step or install required. If you swap out a project or update a repo name, just find and replace the relevant `href` in the file.
