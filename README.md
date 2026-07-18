# Bootstrap Landing Page

A responsive landing page built with Bootstrap 5 for Week 5 of my internship.

## Live Demo

https://inkphantom-coder.github.io/bootstrap-landing-page/

## What's Included

- **Responsive navbar** — collapses to hamburger menu on mobile
- **Hero section** — large heading, tagline, and call-to-action button
- **3-column features** — Bootstrap cards that stack on mobile, sit side-by-side on desktop
- **Contact form** — uses Bootstrap form classes (`form-control`, `form-label`)
- **Consistent spacing** — utility classes (`py-5`, `g-4`, `mb-3`) instead of custom CSS

## Tech Stack

- HTML5
- Bootstrap 5 (CDN)
- Custom CSS for brand colors (gold/dark theme)

## How the Grid Works

| Screen Size | Card Layout | Class Used |
|-------------|-------------|------------|
| Mobile (&lt;768px) | 1 column, full width | `col-12` |
| Tablet+ (≥768px) | 3 columns | `col-md-4` |

`col-12 col-md-4` means: full width by default, then 4 of 12 columns (one-third) starting at the medium breakpoint. This is Bootstrap's mobile-first approach.

## Key Bootstrap Components Used

- `navbar` with `navbar-expand-lg` for responsive collapse
- `container` for centered content with padding
- `row` and `col-*` for grid layout
- `card` with `h-100` for equal heights
- `btn`, `form-control`, `form-label` for styled elements

## Testing

Tested at:
- 375px (iPhone) — navbar collapses, cards stack
- 768px (iPad) — cards in 3 columns
- 1440px (desktop) — full layout

## Author

- Intern: Inkphantom-coder
- Program: Week 5 Internship Task
