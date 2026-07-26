# Huma — Urdu Language Expert Portfolio Website

A single-page professional services website built from your resume: Homepage, About, Services, Portfolio, Experience, Testimonials, Contact — clean navy/teal design, no Urdu-script styling this time.

## What's in here
- `index.html` — the entire site in one file (HTML, CSS, JS). No build step.
- `audio/` — put your voice-over demo MP3 file(s) here.

## Already filled in from your resume
- Name, title, location (Karachi, Pakistan), summary, core competencies
- Work history: Upwork freelance role (2022–present), Syntech Fibers (2020–2022), Ibex Global (2015–2019)
- Education: MA Urdu and BA Economics, University of Karachi
- Tools: MS Office, Google Workspace, CAT Tools, Audacity, Subtitle Edit, AI Annotation Platforms
- Contact links: your real Upwork profile, LinkedIn, email, and phone number

## Still needs your input
1. **Photo** — swap the dark "PHOTO" placeholder box in the hero for a real `<img>` tag with your headshot.
2. **Voice-over demo** — the Portfolio section has one `<audio>` player pointing to `audio/demo-educational.mp3`. Add your real MP3 file to the `audio/` folder with that name, or update the `src` path. Duplicate the card if you want more than one demo.
3. **Testimonials** — currently placeholder quotes (clearly marked in the page). Replace with real quotes from your Upwork reviews once you have permission to share them.
4. **Portfolio samples** — the six project cards describe project *types* from your resume's "Key Projects" list. If you want to link out to actual writing samples or case studies, add `<a href="...">` links to those cards.

## Publish with GitHub Pages
1. Go to [github.com/new](https://github.com/new) and create a repository:
   - `your-username.github.io` → publishes at the root of your GitHub domain, or
   - any other name, e.g. `huma-portfolio` → publishes at `your-username.github.io/huma-portfolio/`
2. Set it to **Public**, skip the README option, click **Create repository**.
3. On the repo page: **Add file → Upload files** → drag in `index.html` and this `README.md`.
4. Add your MP3 by dragging it in with the path `audio/demo-educational.mp3` (GitHub creates the folder from the path automatically).
5. Click **Commit changes**.
6. Go to **Settings → Pages** → under "Build and deployment," set **Source** to "Deploy from a branch," choose `main` and `/ (root)`, then **Save**.
7. Wait 1–2 minutes and refresh — your live URL will appear at the top of that page.

### Custom domain (optional)
Add it under "Custom domain" in the same Pages settings, then point your domain's DNS at GitHub Pages per [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
