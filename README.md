# morcyber.github.io

Static site for https://morcyber.com, served by GitHub Pages from the `main` branch (root). `CNAME` must stay as `morcyber.com`.

## Pages
- `index.html` – HIPAA-focused homepage (offers, pricing, process, FAQ, contact)
- `services.html` – HIPAA services and pricing (site is HIPAA/healthcare only)
- `why-morcyber.html`, `get-started.html`
- `site.css` – shared nav / legal note styles; `script.js` – nav, contact form

## Booking
All "Book" / "Schedule" buttons use the HighLevel (LeadConnector) calendar:
https://outlook.office.com/book/Free30MinHIPAAConsultation@Morcyber.com/

## Contact form (Formspree) – ACTION NEEDED
The "Send us a message" form is **hidden** until a real Formspree ID is set; visitors see a mailto link to Mordecai@Morcyber.com instead.
1. Create a free account at https://formspree.io and create a new form (notification email: Mordecai@Morcyber.com).
2. Copy the form ID (the part after `/f/` in the endpoint, e.g. `xyzabcd`).
3. In `index.html`, replace `YOUR_FORMSPREE_ID` in `action="https://formspree.io/f/YOUR_FORMSPREE_ID"` with that ID.
4. Push; the form appears automatically. Send a test message.
Do not ask visitors to send patient information through the form (Formspree free plan is not covered by a BAA).

## Content rules
No invented testimonials, clients, statistics, or certifications. Add credentials / testimonials only when real and approved.
The site must not claim HIPAA certification or guaranteed compliance; the "not legal advice" note is in every footer.
