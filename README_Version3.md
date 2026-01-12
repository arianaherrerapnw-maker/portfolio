# Portfolio — Ariana Teresa Herrera

This is a simple static portfolio site generated from your resume content. Direct phone number and email have been intentionally removed from the public site to protect privacy. Your LinkedIn profile has been added publicly.

Public contact shown:
- LinkedIn: https://www.linkedin.com/in/ariana-h-0732312a2

Files included:
- `index.html` — main site (LinkedIn included; email/phone removed)
- `styles.css` — styling
- `resume.pdf` — (optional; if you add a PDF here, the Download Resume button will work)
- `assets/` — folder for images and other assets (add `profile.jpg` here)

How to preview locally
1. Put the files in a folder on your computer.
2. Open `index.html` in your browser. (No build step required.)
3. For a more accurate local test, run a simple static server:
   - Python 3: `python -m http.server 8000` and open `http://localhost:8000`
   - Node: `npx serve` (if you have `serve`)

How to add other contact methods (options)
- Add GitHub link: replace `href="#"` for the GitHub anchor in the header and contact section with your GitHub profile URL.
- Add a mailto (if you want email visible again): replace the placeholder contact text or add a link: `<a href="mailto:your.email@example.com">Email</a>`
- Add a contact form (Netlify / Formspree): see previous README instructions for snippets.

Privacy note
- The public site intentionally omits your direct phone and email. The downloadable `resume.pdf` file can still contain your contact information; if you want the resume redacted, replace it with a version without contact details before upload.

Deploying
- Same instructions as before for GitHub Pages, Vercel, or Netlify. If you want me to push these updated files into your `portfolio` repo, create the empty repo on GitHub (https://github.com/new) and tell me the URL — I will push the files for you. I will not re-add your contact info unless you explicitly ask.

Next steps I can take
- Add your GitHub link (send me the URL) and I'll update the header/contact and push changes.
- Add a contact form (Formspree or Netlify) and wire it up.
- Redact or upload a resume PDF (redacted or original) and enable the Download Resume button.
- Push these files to your GitHub repo (I can push once you create the repo and share the URL).