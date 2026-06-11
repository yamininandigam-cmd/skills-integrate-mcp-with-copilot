# Add custom fonts, Font Awesome, and visual assets

Description
-----------
Integrate web fonts (Open Sans / Oswald), Font Awesome icons, and decorative images to make the frontend visually richer and closer to the portfolio reference.

Acceptance criteria
-------------------
- Fonts loaded via `@font-face` or Google Fonts in `src/static/styles.css` (or a small stylesheet import).
- Font Awesome included (local files or CDN) and used for at least one icon in the site (e.g., contact/social links).
- Add a background/hero image placeholder in `src/static/images/` and reference it in CSS.

Suggested files to update
-------------------------
- `src/static/styles.css` (font-face or import, hero background rules)
- Add `src/static/fontawesome/` or reference CDN in `src/static/index.html`
- `src/static/images/` (add hero/project images)

Notes
-----
Prefer CDN for initial implementation to keep the repo small; switch to local assets if offline support required.
