# SpendWise Dashboard Shell - Week 4

Rebuilt tracker layout with Flexbox and Grid.

## What I Built
- Sidebar navigation, header, 6 category cards (Food, Transport, Rent, Entertainment, Utilities, Savings)

## What Each Part Does
- **index.html**: Dashboard structure with sidebar, header, and cards. Cards have tabindex="0" for keyboard focus.
- **style.css**:
    - Grid: `.dashboard` (sidebar + main), `.content` (cards grid)
    - Flexbox: `.sidebar`, `.sidebar nav`, `.header`, `.card`
    - Theme: `:root` variables for brand, accent, surface, primary/secondary text
    - Responsive: media query below 768px collapses to single-column
    - Micro-interactions: card hover/focus uses transform + box-shadow in 200ms
    - Dark theme: `@media (prefers-color-scheme: dark)` overrides root variables

## How to View
Open index.html in browser, test responsive with DevTools Device Toolbar.