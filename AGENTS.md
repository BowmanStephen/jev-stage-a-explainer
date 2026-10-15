# Jev Stage A explainer

Static site. The page is index.html. Figures live in assets/. Deploy is Vercel from the repo root.

Fetch origin/main and branch from that. Cloud checkouts have started behind main and then restored dark mode and the mobile index fix that were already merged.

On main today: dark by default. On phones (max-width 820px), .index scrolls with the page (max-height none, overflow-y visible). Do not put the nested scroll pocket back.

README holds the locked scorecard numbers. If you change the page, update README in the same change. Do not hand-edit Stage A score math.
