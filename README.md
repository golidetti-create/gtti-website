GTTI WEBSITE — PHASE 1 MOBILE & VISUAL POLISH
Golide Technical Training Institute

PROJECT
Static HTML/CSS website. No build step or package installation is required.

KEY FILES
- index.html: homepage
- gtti.css: shared styles for standard pages
- odel.html: ODeL page with its own responsive design system
- remaining HTML files: programme, admissions and support pages

PHASE 1 CHANGES
- More consistent electric-violet and radiant-gold accents, retaining the deep-violet institutional base and text-only GTTI wordmark.
- Responsive navigation collapses before standard-page links become crowded on small laptops/tablets.
- ODeL navigation receives a matching tablet breakpoint while retaining its distinct layout.
- Improved spacing, headings, cards, form controls, keyboard focus and reduced-motion handling.
- More resilient grids and buttons for narrow viewports; two-column layouts on tablets and single-column layouts on phones.
- Updated shared stylesheet cache version to gtti.css?v=4.

DEPLOYMENT TO EXISTING HOSTING
1. Download and extract this ZIP on your computer.
2. Back up the current live website files before replacing anything.
3. Upload the contents of the gtti-website-main folder into the same public web directory as the existing site, preserving filenames and relative paths.
4. Confirm that index.html is in the public web root and gtti.css sits beside it.
5. Visit the site in a private/incognito browser window, then hard-refresh on desktop and phone to avoid cached CSS.
6. Test menu opening/closing, every primary navigation link, all programme cards, Moodle login, and the contact form.
7. Keep the previous version until the live checks pass.

MAINTENANCE NOTES
- Update shared navigation consistently across pages.
- Check phone/WhatsApp, email, fees and admissions information before publishing.
- The contact form uses a Formspree endpoint in contact.html; submit a test enquiry to confirm live delivery.
- Moodle login should continue to open https://gtti.moodiy.school/login/index.php directly; this site does not collect Moodle passwords.
- ODeL has a separate navigation and inline stylesheet by design.

VALIDATION LIMIT
This package has been checked for local HTML links, expected navigation elements, stylesheet references and basic source structure. It has not been tested on your live hosting account or in a full browser/device lab. Test before replacing the live site.
