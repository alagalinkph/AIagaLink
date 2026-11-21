AlagaLink 2.1 — Corrected bilingual geriatric health education website

FILES (keep all in the same GitHub repository root):
- index.html
- styles.css
- script.js
- group-photo.jpg
- alagalink-logo.svg

WHAT WAS CORRECTED
- All photo areas now use the supplied BSN-3B group photo, including the lower caregiver section. The previous remote portrait image has been removed.
- Replaced topic pictograms with matching inline SVG medical icons: heart/pulse for blood pressure, droplet for diabetes, bone for bones/joints, eye and ear for vision/hearing, salad for nutrition, brain for mental well-being and memory concerns, pill for medication safety, and footprints for fall prevention.
- Replaced the heart-only text mark with a simple green AlagaLink logo that includes a warm gold medical cross and increased its size.
- SVG topic icons are inline, so no external icon library is required.

PUBLISH ON GITHUB PAGES (Android tablet)
1. Extract this ZIP.
2. Open your GitHub repository and choose Add file > Upload files.
3. Upload/replace all five files listed above into the repository ROOT (not a nested folder).
4. Commit changes. Keep filenames exactly as shown, including group-photo.jpg and alagalink-logo.svg.
5. Wait for GitHub Pages deployment, then refresh the site. If an old image remains, hard refresh or clear the browser cache.

TESTING NOTES
- HTML references only local group-photo.jpg for the three photo placements.
- Inline SVGs mean the health topic icons do not rely on emoji fonts or third-party icon packages.
- JavaScript syntax is checked with Node. This is a static school project, not a live telehealth service or secure medical-record system. Do not enter real patient identifiers or sensitive health information.
- The tracker and consultation request are demonstrations only; they do not transmit data or book appointments.
- For emergencies call 911. Educational information does not replace advice from a licensed healthcare professional.
