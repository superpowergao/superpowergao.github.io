# AGENTS.md — Rules for working on this site

This repo is Eve Gao's personal website (superpowergao.github.io), published with GitHub Pages.
Anything committed here can become public. Follow these rules every time.

## 1. Never publish

- **Phone number.** It appears on the CV but must never appear on the site, in code, comments, or commit messages.
- **Home address, date of birth, ID numbers, visa/immigration status, salary or compensation figures.**
- **The CV PDF itself** (`Eve Gao - Resume copy.pdf` or any `cv.pdf`). It contains the phone number. Do not commit it or link to it unless Eve provides a version with the phone number removed.
- **Grades or scores beyond what the CV already lists** (the CV lists GPA 3.99/4.00 and GRE 336; nothing else).
- **Confidential employer material**: internal UN, Jinke, or People's Daily documents, dashboards, screenshots, client data, or unreleased product details beyond what the CV states.
- **Other people's personal information** (names, photos, contact details of colleagues, classmates, or students).
- **Secrets**: API keys, tokens, passwords, `.env` files.
- **Invented content.** Do not add achievements, numbers, testimonials, or skills that aren't in the CV or given by Eve.

## 2. Ask Eve first

- Before any `git commit`, `git push`, or change to GitHub settings / GitHub Pages. **Nothing gets pushed without explicit permission.**
- Before adding a photo, a new contact method, or a downloadable CV.
- Before adding analytics, tracking scripts, cookies, contact forms, or any third-party service.
- Before deleting or renaming existing files.
- When CV content is unclear or conflicts with other sources (for example, the CV's LinkedIn URL `yu-gao-9348a2336` differs from the one Eve gave, `eve-gao-9348a2336`; the site uses the one Eve gave).
- Before rewording CV bullets in a way that changes their meaning or numbers.

## 3. Style

- **Vibe:** professional but casual — confident, warm, easy to read. No buzzword padding.
- **Colors:** Columbia blue `#B9D9EB` as the signature color, with navy `#002B49` / `#1D4F91` for text and accents, on white or very light blue backgrounds. Keep contrast readable (WCAG AA).
- **Navigation:** streamlined — one slim sticky top bar with links to each section; tiles on the home page jump to sections. Works on phones.
- **Content order:** follow the CV — Education, Experience, Additional Information.
- **Tech:** plain HTML + CSS (small inline JS only if needed). No frameworks or build steps. Fonts from Google Fonts only.
- **Accessibility:** semantic headings, alt text for any images, visible focus states, mobile-friendly layout.
- **Writing:** keep CV wording; light edits only for typos or line breaks. Use plain language.
