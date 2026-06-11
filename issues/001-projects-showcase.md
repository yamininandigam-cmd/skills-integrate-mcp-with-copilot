# Add a "Projects" showcase section to the site

Description
-----------
Add a visually rich "Projects" section to the static frontend that showcases project tiles with hover overlays, tags, short descriptions and links to live demos or repos. This mirrors the interactive project tiles from Harshita Agarwal's portfolio.

Acceptance criteria
-------------------
- New `#projects` section appears on `src/static/index.html` with at least one example project tile.
- Each tile includes image, title, description, tags and a link.
- Hover overlay effect implemented via CSS (`src/static/styles.css`) similar to `figure.effect`.
- Project data should be easy to extend (HTML or a small JSON snippet).

Suggested files to update
-------------------------
- `src/static/index.html` (add `#projects` section)
- `src/static/styles.css` (add tile + overlay styles)
- `src/static/images/` (add sample project image)

Notes
-----
Keep this purely static (no additional backend changes required). Use existing static hosting path.
