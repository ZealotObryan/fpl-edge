# FPL Edge

FPL Edge is a mobile-first Fantasy Premier League management assistant.

## Current direction
- One canonical mobile-first UI, scaling the same components to tablet and desktop.
- PWA-first delivery with live/cached FPL data and a bundled player fallback.
- Existing FPL Edge branding, navigation, data-science models and core functionality are preserved.

## Development
- `npm test`
- `npm run build`

## Source of truth
The GitHub repository is being established as the canonical source-control location for FPL Edge. The current production project on Vercel is still deployed from an uploaded source deployment rather than a verified GitHub-linked project.

## Important
Do not treat generated ZIPs or deployment artifacts as the long-term source of truth. Production changes should flow through GitHub -> preview deployment -> QA -> production once the Vercel/Git connection is authorized.
