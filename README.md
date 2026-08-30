# ColorLayer

ColorLayer turns artwork into editable flat-color manufacturing layers for 3D printing and inlay-style assembly.

## Deployment channels

- **LIVE:** `https://bulls192.github.io/ColorLayer/`
- **DEV:** `https://bulls192.github.io/ColorLayer/dev/`

`LIVE` is the last promoted/tested build. `DEV` is the newest iteration for phone, tablet, and desktop testing before promotion.

## Current baseline

V0.3.1 PWA

- Editable color palette and layer names
- Filament/spool assignments
- Background selection and layer visibility
- Color merging and small-island cleanup
- Closed contour SVG/DXF generation
- Physical sizing in millimeters
- PNG/SVG/DXF/STL layer export
- Backing and frame STL generation
- Assembly 3MF export
- Manufacturing ZIP + manifest
- Project save/open
- Installable PWA and offline app-shell cache

## Development workflow

1. Build and publish the next iteration to `/dev/`.
2. Test from phone/iPad/desktop.
3. Fix issues in DEV.
4. Promote the tested DEV build to the repository root (LIVE).

The `development` branch mirrors the active development baseline, while `main` remains the source for the published LIVE/DEV site structure.
