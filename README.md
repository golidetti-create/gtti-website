# GTTI Website — Scholar Edition

Golide Technical Training Institute (GTTI), Kenya

## What is included

- Responsive multi-page website for desktop, tablet and mobile.
- Scholar-inspired visual refinement using GTTI's violet, gold, white and plum identity.
- Accessible navigation with keyboard and mobile support.
- **Golide Guide**, a lightweight site navigation assistant that helps visitors find programme, admissions, fees, ODeL/Moodle, qualification-route, FAQ and contact pages.
- Existing contact enquiry form powered by Formspree (must be tested live).
- Programme, fees, admissions, ODeL, contact and FAQ pages, plus branded 404 page.

## Important: what “AI assistant” means in this edition

Golide Guide is currently a browser-based, rule-driven navigation assistant. It does not send visitor messages to an AI provider, and it does not require API keys. It is intentionally transparent and privacy-friendly, but it is **not a generative AI model** and cannot reliably answer every open-ended question.

For a true AI assistant, connect a server-side endpoint to an approved model provider. Keep API keys on the server, add rate limiting and abuse protection, provide only approved GTTI information as grounding, and clearly label AI-generated answers. Do not put a private API key in `site.js` or any browser-delivered file.

## Local test on Windows

1. Extract this ZIP.
2. Open PowerShell inside `gtti-website-main`.
3. Run `python -m http.server 8000`.
4. Visit `http://localhost:8000`.
5. Test the assistant, every navigation item, contact links, and the Moodle link on desktop and mobile.

## Before publishing

1. Preserve your existing `.git`, `.github`, workflow files, `CNAME`, and domain configuration when copying this folder into an existing repository.
2. Confirm that `https://gtti.moodiy.school/` is the current official student portal and test login with a valid account.
3. Submit a real contact enquiry and verify that it arrives at the correct GTTI inbox. The form endpoint is external, so source inspection alone cannot confirm delivery.
4. Confirm current programme availability, exact awarding bodies, entry requirements, intake dates, fee schedules, institutional approvals and physical address before publication. Avoid presenting indicative KCSE pathways as guaranteed admission decisions.
5. Test accessibility, mobile layouts, page titles, broken links and 404 handling on the deployed site.

## Suggested next phase for a truly functional digital campus

- A secure application form with submission confirmation and application reference number.
- A student dashboard integrated with the actual LMS (Moodle), not a duplicate account system.
- A verified programme catalogue with downloadable course outlines, entry requirements, duration and approved fees.
- Automated enquiry acknowledgement and a clear human-support handoff.
- Privacy notice, data-retention policy, consent wording and secure handling of applicant documents in line with applicable Kenyan data-protection requirements.
- Analytics and search-console setup, with a consent-aware privacy approach.

This package improves the front-end experience, but it does not create a backend database, process admissions decisions, take payments, or modify Moodle accounts. Those capabilities require properly configured external services or a backend.
