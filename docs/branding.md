# Vula Vala — initial brand guidelines

Version 0.1 · 16 November 2026 · Initial visual direction

## Identity

The hand represents human agency and operational control. The tap expresses the open/close metaphor of Vula Vala. The droplet keeps the purpose grounded in water. The hand must remain above the tap handle, visibly operating it; moving it under the spout changes the meaning.

This first pack follows the owner's explicit hand–tap–droplet direction. It is a working identity, not an approved final identity following a comparison of unrelated logo concepts.

## Logo files

| File in `assets/branding/` | Intended use | Background |
| --- | --- | --- |
| `logo-primary.png` | Stacked primary lockup, presentations, project identity | Transparent; use on light surfaces |
| `logo-horizontal.png` | Wide headers and document mastheads | Transparent; use on light surfaces |
| `logo-icon.png` | Icon-only mark, avatar concept, larger application branding | Transparent; use on light surfaces |
| `logo-dark.png` | Dark presentation panels | Opaque navy |
| `logo-monochrome.png` | Black-on-white documents and simple reproduction previews | Opaque white |

The primary, horizontal and icon-only PNGs have alpha transparency. The dark and monochrome images intentionally include their backgrounds. Do not treat the latter as transparent cutouts.

## Palette

These are intended design tokens. Generated raster pixels may vary slightly from the exact values; use these tokens for future interface work rather than sampling a compressed preview.

| Role | Colour | Hex |
| --- | --- | --- |
| Primary ink | Deep navy | `#102F3A` |
| Water / brand accent | Teal | `#087F8C` |
| Accent on dark surfaces | Aqua | `#4DD9CF` |
| Warm surface | Limestone | `#F5F2EA` |
| Attention accent | Amber | `#E9A23B` |
| Light surface | White | `#FFFFFF` |

Use navy or teal for text on white. Aqua and amber are accents, not default body text colours on white. Incident status must include a text label or icon, not colour alone. Check the contrast of actual interface combinations when the UI is built.

## Typography direction

Use a clear sans serif with distinct characters and tabular numbers for operational tables. Start with the platform's system sans-serif stack for an implementation without font downloads: `system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif`. Use bold headings sparingly and sentence case for product UI. The generated logo lettering is artwork, not an identified or bundled font.

## Placement

- Keep clear space around the logo at least equal to one droplet's width.
- Preserve aspect ratio; never stretch, rotate or crop the hand, tap or droplet.
- Use the icon-only version when the wordmark becomes difficult to read.
- Start with the stacked mark at 160 CSS pixels wide, the horizontal mark at 240, and the icon at 64. These are provisional layout starting points, not verified small-size limits.
- Keep logos on quiet, contrasting surfaces. Put imagery beside a logo or place the logo in a solid panel.
- Use the actual wordmark spelling **VULA VALA**; use **Vula Vala** in prose and **Vula-Vala** for the repository name.

## Imagery

The six pictures cover infrastructure, community reporting, field maintenance, future sensors, collaborative decision support and geographic intelligence. Warm brick and stone, restrained teal, natural light and capable people connect the images visually to South African infrastructure work without depicting a named municipality.

Every picture is AI-generated. Use a visible caption such as **AI-generated concept illustration** when a realistic scene could be interpreted as evidence or a customer story. Concept maps and cutaways are not engineering drawings. Hardware imagery does not assert product compatibility. Do not use these images as incident evidence or model-training samples.

Alt text and suggested captions are in [the manifest](../assets/manifest.json). Use empty alt text for a purely decorative image when adjacent copy already conveys its meaning; use the descriptive text when the picture contributes information.

## Production work still required

This milestone supplies high-resolution raster assets. An editable vector master, exact shared geometry across all lockups, a simplified small-size favicon, application icon exports, print proofs and formal trademark review remain future identity work. Generated variants can differ slightly in spacing and contours. Do not wrap a PNG inside an SVG and describe it as a vector master.

Keep the original PNGs as masters. Create appropriately sized web derivatives when actual page layouts are known; do not load every full-resolution image into a future dashboard.
