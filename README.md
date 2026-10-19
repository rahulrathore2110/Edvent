# EDVENT — Computer & Technology Institute website

Responsive static website built with HTML, CSS and vanilla JavaScript, using the supplied EDVENT logo and blue/cyan/orange brand colors.

## Project structure
- `index.html` — home page, course catalog, enquiry form, SEO metadata
- `styles.css` — responsive styles
- `script.js` — mobile navigation, course filters and WhatsApp enquiry behavior
- `assets/edvent-logo.png` — supplied institute logo
- `assets/favicon.svg` — favicon
- `courses/*.html` — 12 readable syllabus pages
- `downloads/*.docx` — exact uploaded Word syllabuses for download

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser, or run `python3 -m http.server 8000` from the project folder and open `http://localhost:8000`.

## Required launch edits
1. In `script.js`, replace `91XXXXXXXXXX` with the institute WhatsApp Business number in digits-only international format (India: `91` + 10-digit number).
2. Confirm `https://edventindia.com/` is the actual domain, and update canonical/structured data if the domain changes.
3. Add verified address, phone, email, opening hours, fees, batch schedules and any accreditation/certificate information that applies. Do not publish unverified claims.
4. Configure hosting, DNS and HTTPS.
5. Add a sitemap.xml, robots.txt and social share image before launch if desired.

## Syllabus display and downloads
Each syllabus page displays text extracted from its corresponding uploaded DOCX. The original Word file is linked for download, preserving its original formatting and embedded images. Some diagrams and embedded images are only present in the original download.

## Admissions form
The form validates input and prepares a WhatsApp message. It does not store enquiries in a database or send messages automatically. A visitor must review and send the message in WhatsApp. Connect a form provider or backend if you need email delivery or persistent records.
