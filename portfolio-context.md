# Portfolio Site — Claude Context Document
> Paste this at the start of any new Claude chat to resume work on the portfolio site instantly.

---

## Who I am
- **Name**: Sunil Kumar Reddy K
- **Role**: Senior QA Automation Engineer / SDET
- **Experience**: 6+ years
- **Email**: kalluru.skr@gmail.com
- **Phone**: +91 96039 16766
- **LinkedIn**: https://www.linkedin.com/in/sunil-kalluru
- **GitHub**: https://github.com/Sunil-Kumar-Reddy-K

---

## The portfolio site

- **Live URL**: https://sunil-kumar-reddy-k.github.io/Resume/
- **GitHub repo**: https://github.com/Sunil-Kumar-Reddy-K/Resume
- **Tech**: Single `index.html` file — no frameworks, no build step, pure HTML/CSS/JS
- **Deployed via**: GitHub Pages — `main` branch, root `/`
- **To update**: edit `index.html` locally → upload/replace file in the repo → GitHub Pages auto-deploys in ~2 min

---

## Design decisions (don't change these without asking)

- **Font**: JetBrains Mono (headings/code feel) + Familjen Grotesk (body)
- **Theme**: Dark — `#080810` background, `#39ff8f` accent green
- **Style**: Terminal / engineering aesthetic — scanlines, grid background, monospace-led
- **Layout**: Single page, section-by-section scroll
- **Hero headline**: *"Automation first. Quality built in, // not tested in afterwards."*

---

## Sections currently on the site (in order)

1. **Visitor counter bar** — hits.sh badge (top of page)
2. **Nav** — links to skills, projects, certs, experience, contact + resume download
3. **Hero** — profile photo, name, headline, stats, terminal JSON widget
4. **Stack / Skills** — 6 blocks: UI Automation, API Testing, AI-Powered Testing, Languages, CI/CD, Tooling
5. **Featured Projects** — 5 client projects (Socotra, Tempus LIMS, Woodcock Johnson, ESN Sports, SHAP)
6. **GitHub Frameworks** — 3 OSS repos (Playwright TS, Playwright Python, Rest Assured)
7. **Certifications** — placeholder cards (awaiting real certificate names + images)
8. **Beyond Code** — CAD 2D, 3D Modelling (Fusion 360), 3D Printing (Bambu Labs)
9. **Work History** — timeline (Trigent, Adeptpros, SHAP)
10. **Contact** — links + Formspree contact form

---

## Integrations

- **Formspree**: contact form wired up and tested — submissions go to kalluru.skr@gmail.com
  - Form action URL: `https://formspree.io/f/mbdzkwzn` ← replace with actual ID if rebuilding
- **Visitor counter**: hits.sh badge — works only on live GitHub Pages URL, not in local preview
  - Badge URL: `https://hits.sh/sunil-kumar-reddy-k.github.io/Resume/.svg?style=flat&color=39ff8f&labelColor=111120&label=views`

---

## Profile photo

- Embedded as base64 JPEG directly inside `index.html` (no separate image file needed)
- 130px circular, accent border glow, positioned next to name/role in hero
- Original file: `sunil_profile_photo.png` — if re-embedding needed, resize to 400x500px JPEG quality 82

---

## Industries covered

Healthcare · Insurance · Education · eCommerce · Automotive (5 industries)

---

## Technical skills on the site

| Category | Tools |
|---|---|
| UI Automation | Playwright, Selenium WebDriver, Protractor, POM, BDD/Cucumber |
| API Testing | Rest Assured, Postman, OVH Venom, GraphQL, Playwright API |
| AI Testing | Applitools Preflight, Playwright Zero-Step |
| Languages | TypeScript, JavaScript, Java, Python, YAML |
| CI/CD | GitHub Actions, Jenkins, Concourse CI, Docker, AWS, Sauce Labs, LambdaTest |
| Tooling | Gatling, Jira, Zephyr, Xray, MySQL |

---

## What's pending / TODO

- [ ] **Certifications** — add real certificate names, issuers, and images
  - Format: Udemy / training completion certificates
  - Display: badge-style cards with image + issuer + name
  - To add: upload certificate images to Claude and share names/issuers
- [ ] **Visitor counter** — verify hits.sh is rendering on live site (may need URL path tweak)
- [ ] **Profile README** — GitHub org-level README still not created
- [ ] **Resume PDF** — rename PDF to remove date from filename (currently `..._08102024.docx`)

---

## Preferences & constraints

- **No-code approach** — Sunil prefers template/guided approach, not writing raw HTML from scratch
- **Single file** — keep everything in one `index.html`, no separate CSS/JS files
- **Photo embedded** — keep photo as base64 in HTML, not a separate file
- **Dark theme only** — do not suggest light theme variants
- **Font locked** — JetBrains Mono + Familjen Grotesk, do not change without asking

---

## How to update the site

When making changes, always:
1. Read this document first for full context
2. Ask clarifying questions before rebuilding
3. Generate updated `index.html`
4. Remind Sunil to replace `YOUR_FORM_ID` with actual Formspree ID before uploading
5. Remind Sunil to upload to the `Resume` repo (not a new repo)

---

*Last updated: March 2026*
