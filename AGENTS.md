# AGENTS.md — Rules for working on Kristen Pan's personal site

Site: kristenjpan.github.io (static HTML/CSS, no build step).
Owner: Kristen Julia Pan. Source of truth for content: `Kristen Pan_CBS Resume.docx`.

## Never publish
- Phone number, home address, or any government/financial ID.
- Email addresses (including the Columbia address on the resume) unless Kristen explicitly approves it for the page. Default contact path is LinkedIn and GitHub.
- Anything from the other documents in this folder (`CIA Marketing, Branding.docx`, `Marriott Marketing Manager.docx`, `Rosewood Marketing Manager.docx`). They are job-application material, not site content.
- Confidential employer information: no internal figures, unreleased projects, or manuscript text. The Forbes memoir may be mentioned only as the resume describes it.
- Claims not in the resume or approved by Kristen: no invented metrics, titles, dates, awards, testimonials, or photos.
- Secrets, tokens, or credentials of any kind.

## Ask Kristen first
- Before any `git push`, commit to a remote, GitHub Pages change, or other action that makes the site public. Local files and local preview are fine.
- Before adding personal contact details, a photo, analytics, trackers, forms, or third-party embeds/scripts.
- Before adding or rewording any factual claim, number, or date, or dropping anything from the resume.
- Before deleting or overwriting any existing file, or touching files outside this folder.
- When resume and site wording conflict, or when something is ambiguous (e.g., currency, dates, titles).

## Style
- Tone: professional, confident, concise. Fits someone with both academic (Columbia MBA) and industry (hospitality brand leadership) experience. Plain language, active verbs, no hype or buzzwords.
- Content: preserve all resume facts exactly (numbers, dates, names). Light tightening is fine; changing meaning is not.
- Visual: modern and clean. Columbia blue (#B9D9EB) paired with deep navy (#0B2545) for contrast; generous whitespace; tile/card layout for scannability.
- Navigation: sticky top nav with anchor links to every section; fully usable on mobile.
- Accessibility: semantic HTML, sufficient color contrast (text on Columbia blue must be navy), visible focus states, alt text for any images, respects `prefers-reduced-motion`.
- Tech: single-file-friendly, no frameworks, no external scripts; web fonts only if needed. Keep pages fast and readable without JavaScript.
- Pronouns: use first person on the site or avoid pronouns; use they/them if referring to Kristen in third person in notes.

## Process
- Report outcomes honestly, and list every file created or changed at the end of a task.
- Keep temporary files out of this folder.
