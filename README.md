# Parivahan — a citizen's concept redesign (unofficial)

**This is not a government website.** It's a clickable concept made by a citizen to show how India's Parivahan transport services (driving licence, vehicle registration, traffic fines) could be easier to use. Everything runs in your browser and nothing you type is sent anywhere. All names, numbers and amounts are dummy data.

## What's inside
- `Website-Concept.html` — the whole concept in one file: no server, no tracking, no external code. **To view it, just double-click it**; it works offline in any browser.
- `REPORT.md` — the audit: problems, fixes, evidence, and how the official team could use this.

## Journeys covered (English + हिन्दी)
1. Renew driving licence: quick eligibility check (medical certificate? Aadhaar?), then details, review and tracking
2. Get a learner's licence: plain-language vehicle types, practice question, online test
3. Pay a traffic fine: find by vehicle, DL or challan number; pay several at once; contest a fine
4. Transfer vehicle ownership: ready-to-transfer checklist (insurance, PUC, loan, unpaid fines), then buyer confirmation by SMS
5. Track applications: licence and vehicle applications in one list, with a step-by-step timeline
6. Download DL or RC
Plus: update mobile number, service status page, and a single sign-in placeholder.

Tap **"What changed?"** at the top of any page to see why each change was made and which problem on the current site it fixes.

## Principles followed
- Task-first homepage: the six most-used services come first, with a search box
- State asked once and remembered
- No popups; one dismissible notice
- Plain language, with official codes (COV, LMV) shown only as secondary labels
- Mobile-first, large tap targets, no sideways scrolling, full Hindi toggle
- A safety line on every page (".gov.in only") to fight fake e-challan sites
- Built in the spirit of GIGW 3.0 and the UX4G design system

## For the official team
You're free to reuse any part of this. The design ideas matter more than the code: real implementation would sit on Vahan/Sarathi/eChallan back ends, with proper authentication, payments and accessibility testing (including screen readers).

## Optional: hosting a preview on GitHub Pages
1. On GitHub, create a new **public** repository (e.g. `parivahan-concept`).
2. On the repository page, choose **Add file → Upload files** and drag in `Website-Concept.html`, `README.md` and the `screenshots` folder. Click **Commit changes**.
   GitHub Pages opens `index.html` by default, so either rename a copy to `index.html` or visit `https://<your-username>.github.io/parivahan-concept/Website-Concept.html`.
3. Open **Settings → Pages** (in the "Code and automation" section of the sidebar).
4. Under **Build and deployment → Source**, choose **Deploy from a branch**. Under **Branch**, pick `main` and `/ (root)`, then click **Save**.
5. After a few minutes the page shows your site's address: `https://<your-username>.github.io/parivahan-concept/`.

### Guardrails, please keep these
- Keep the "Concept redesign — not an official government website" banner. It is sticky on purpose.
- Don't add the State Emblem or any official logo, and don't use a web address that looks official (no "gov", no "parivahan" lookalike domains).
- Don't connect any form to a real back end or payment gateway.
- `noindex` is set so search engines don't show it to people looking for the real site.

## Known limits
- Hindi text was drafted with AI help. A native-speaker review is welcome.
- Timelines such as "3–7 working days" and "about 10 minutes" are illustrative, not official figures.
- Services outside the six main journeys open a "not in the concept yet" page.
