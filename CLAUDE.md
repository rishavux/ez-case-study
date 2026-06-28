# EZ Brow & Beauty — Portfolio Case Study

A UX/design case study page for EZ Brow & Beauty, the user's mom's small beauty business in San Francisco. Built as a static HTML/CSS page, no frameworks or JavaScript.

## Structure

```
newest_version/
  index.html   ← main page (all content lives here)
  style.css    ← all styles + design tokens
images/        ← local screenshots/moodboard (some assets served from Figma MCP URLs)
```

## Stack

- Pure HTML + CSS, no JS
- Google Fonts: Cinzel, Spectral, Spectral SC, Montserrat, Beiruti
- Images: some pulled from Figma MCP asset URLs (`figma.com/api/mcp/asset/...`)

## Design System (style.css)

90 CSS custom property tokens across 10 color groups defined in `:root`:

| Group | Key aliases |
|-------|------------|
| Ink | `--ink` (dark neutrals) |
| Surface | warm beige neutrals |
| Oxide Red | `--oxide-red`, `--oxide-red-dark` — primary accent |
| Clay Brown | earthy warm browns |
| Terracotta | light warm orange-tan |
| Linen | warm off-white |
| Harvest Gold | `--harvest-gold` — secondary accent |
| Saffron | bright yellow-gold |
| Botanical Green | muted greens |
| Mineral Blue | muted blues |

## Page Sections (top → bottom)

1. Header — logo + "Brow & Beauty" title
2. Info Bar — Role / Context / Platform
3. Screens Strip — 4 mobile mockup screenshots + hero quote
4. Project Overview — Problem / Solution / Delivery
5. The Starting Point — origin story (personal narrative)
6. Design Strategy — 4 theme cards (Royal, Precise, Familiarity, Clarity)
7. Key Design Decisions — 3 decisions with before/after screens and flow diagrams
8. Reflection — personal reflection text
9. What's Next — Physical Renovation / Herbal Product Line / Custom Booking

## Responsive Breakpoints

- Desktop: default (no query)
- Tablet: `max-width: 900px`
- Mobile: `max-width: 480px`

## Current Status

- Desktop design is complete and styled
- Mobile/tablet breakpoints only partially implemented (header + quote adjusted; most sections not yet made mobile-responsive)
- Prototype lives in Figma; this page is the coded case study presentation

## Planned Next Steps

- Expand responsive CSS for all sections at tablet + mobile
- Design and build a custom booking system to replace Vagaro entirely (user's brother, a senior dev, is aligned on building it)
- Desktop and tablet Figma designs still to be created
- Physical salon renovation planned in parallel
- Herbal product line (Ayurveda-inspired) in development
