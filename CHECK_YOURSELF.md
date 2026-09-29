# What you need to do
## Build a dashboard that shows at least three KPIs, three drivers, and operational details (tables or lists) in the three blocks described above. It must work well on mobile, tablet, and desktop (at least three breakpoints; design mobile-first).

- [x] Plan the layout: Decide the main structure: navbar/header or sidebar, and how the content is split (top block = KPIs, middle = drivers, bottom = tables/lists). Think in reusable components (cards, widget boxes, tables) and section-based structure.
- [x] Design mobile-first: Start from the smallest screen; then adapt with Tailwind breakpoints (sm, md, lg) so the same components work on tablet and desktop. Avoid pixel-based sizes; use Tailwind spacing and sizing utilities.
- [x] Use semantic HTML: Use appropriate tags (<header>, <nav>, <main>, <section>, <table>, etc.) so the dashboard has a clear document outline.
- [x] Use Tailwind only: Apply styles with Tailwind utility classes (and Preflight if you use the Tailwind build). Do not mix in other CSS frameworks or custom CSS except for Chart CSS if needed.
- [x] Charts (optional): For KPIs or drivers you can use Chart CSS (CSS-only). Data can be sample data; focus on clear hierarchy and readability.
- [x] Consistency: Reuse the same patterns for similar elements (e.g. all KPI cards share the same structure and style).


# What we will evaluate
- [x] Semantic HTML: Correct use of structural and landmark tags; clear, logical hierarchy.
- [x] Tailwind CSS: Styles applied via utility classes; no conflicting or redundant custom CSS; appropriate use of breakpoints and layout utilities (flex/grid).
- [x] Layout and components: Clear separation of the three blocks (KPIs, drivers, operational); consistent grouping and visual hierarchy; reusable-looking components (cards, sections, tables).
- [x] Responsive design: Usable on at least three device sizes (e.g. phone, tablet, desktop); mobile-first approach; no horizontal scroll or broken layout on small screens.
