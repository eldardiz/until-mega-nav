# UNTIL mega-nav wireframe

Interactive wireframe of the proposed navigation for [until.co.uk](https://www.until.co.uk). Structure and behaviour only, no visual design yet.

Open `index.html` in a browser. v2 (client feedback, 23 Sep 2026) is `index.html`; the first version is kept at `v1.html`. No build step, no dependencies (Google Fonts only, with system fallbacks).

## Structure

`Find your space` · `Memberships` · `Locations` · `Find a practitioner` · `Resources` · **Apply now**

- **Find your space**: mega panel with TRAIN / TREAT / COACH / MEDICAL / DENTAL, one keyword link per room type ("Gym space to rent"), plus a featured card.
- **Memberships**: Thrive and Teams.
- **Locations**: one card per club (Soho, Liverpool St, Marylebone, Canary Wharf).
- **Find a practitioner**: Health Concierge first, then the specialist client pages.
- **Resources**: Journal, State of the Industry report, careers, contact.

All links use real until.co.uk paths.

## Interactions

- Hover intent: 120 ms delay before the first menu opens, instant switching after that.
- One dropdown container that morphs width and height between menus, with a cross-fade and a sliding underline.
- Click, Enter and Space toggle; Esc closes; clicking outside or scrolling closes.
- Under 900px: full-screen drawer with staggered accordions and Apply now pinned to the bottom.
- Respects `prefers-reduced-motion`.
