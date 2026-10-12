# The Italian Studio Co. — project context

Hub site for **theitalianstudioco.com**, owned by Tommy Italia. Static site (plain HTML/CSS/JS, no build step), hosted on GitHub Pages from `main` / root. DNS at Porkbun (4 A records → GitHub Pages IPs, `www` CNAME → tommyitalia22.github.io).

Full brief and decisions: `Dropbox/Ventures/Sprints/the-italian-studio/BRIEF.md`.

## Brand (locked — don't change without asking)
- Name: The Italian Studio Co. · Tagline: "Built to turn your mountains into *molehills.*"
- Logo: Faceted Peak — slate `#3B5A78` / ink `#0E0F0C` peak, gold `#F2A541` molehill (`favicon.svg`)
- Type: Newsreader (serif headlines, one italic word per headline) + Geist (body)
- Palette: bg `#FBFAF8`, ink `#0E0F0C`, body `#3A3D38`, muted `#7A7A6E`, blue-gray `#EBEDEF`/`#DDE8EF`, gold accent `#F2A541` (hover fills), dark gold `#9A6212` (text)
- Hero: Fitz Roy at dusk (`assets/hero-fitzroy-dusk.jpg`, Unsplash free license) + drifting CSS clouds + live San Francisco clock

## Working rules
- Tommy is non-technical: explain changes in plain words, keep replies short.
- Tools launch on subdomains (`tool.theitalianstudioco.com`) until they earn their own domain.
- Problem-intake form posts to `FORM_ENDPOINT` in `index.html` (not yet connected). Submissions feed the Idea Backlog in `Dropbox/Ventures/Tracker/Venture_Tracker.xlsx`.
- Check mobile (390px wide) after any layout change — no horizontal scroll.
