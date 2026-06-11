# Integrate Bootstrap utilities and enhance responsive layout

Description
-----------
Bring in Bootstrap (or selective utility classes) to simplify responsive grid layout and provide consistent typography and spacing for the expanded resume and projects sections.

Acceptance criteria
-------------------
- Bootstrap added via CDN link in `src/static/index.html` (or minimal subset copied locally).
- Layout updated to use Bootstrap grid classes for the `#profile`, `#projects`, and `#abilities` sections.
- Ensure mobile breakpoints render correctly and match current styling goals.

Suggested files to update
-------------------------
- `src/static/index.html` (add Bootstrap link and update markup)
- `src/static/styles.css` (adjust/override Bootstrap variables as needed)

Notes
-----
Bootstrap is optional for this small site; use it only if it helps accelerate layout work.
