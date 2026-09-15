# UNTIL mega-nav wireframe

Interactive wireframe of the proposed navigation for [until.co.uk](https://www.until.co.uk). Structure and behaviour only, no visual design yet.

Open `index.html` in a browser. No build step, no dependencies (Google Fonts only, with system fallbacks).

## Structure

`Spaces` · `Memberships` · `Locations` · `Find a practitioner` · `Resources` · **Apply now**

- **Spaces**: mega panel with TRAIN / TREAT / COACH / CONSULT as columns, practitioner links under each, plus a featured card.
- **Memberships**: Thrive, Teams, pay-as-you-go credits.
- **Locations**: one card per club (Soho, Liverpool St, Marylebone, Canary Wharf), New York as coming soon.
- **Find a practitioner**: the client-facing Health Concierge pages.
- **Resources**: Journal, State of the Industry report, careers, contact.

All links use real until.co.uk paths.

## Interactions

- Hover intent: 120 ms delay before the first menu opens, instant switching after that.
- One dropdown container that morphs width and height between menus, with a cross-fade and a sliding underline.
- Click, Enter and Space toggle; Esc closes; clicking outside or scrolling closes.
- Under 900px: full-screen drawer with staggered accordions and Apply now pinned to the bottom.
- Respects `prefers-reduced-motion`.
