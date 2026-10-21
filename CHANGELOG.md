# Change Log

All notable changes to **Hyperdark** are documented here. Or at least as much as I felt like updating to a certain point 😆.

---

## [1.6.0] – 2026-10-21

### Changed

- Lightened the base background from `#191a1f` to a neutral `#202122` across the editor, sidebar, activity bar, status bar, title bar, tabs, panel, breadcrumbs, minimap, and widgets (menus, hovers, suggest, peek view, notifications, dropdowns, inputs, and debug toolbar), dropping the blue tint
- Brightened comments from `#4C4C4C` to `#666666` for better legibility
- README now describes Hyperdark as a higher contrast, yet mellow theme inspired by the Habamax vim theme, and the Philosophy section was condensed
- README title now reads "Hyperdark (formerly 'Hypedown' Theme)" to reflect the rename
- README preview image is now a local `image.png` (refreshed to show the new palette) instead of a GitHub-hosted asset, and the review/rating request was reworded
- Marketplace keywords: dropped `low contrast` and added `dark` and `flat` to match the new positioning
- Expanded `.gitignore` (`.DS_Store`, `dist`, `build`, `coverage`, `.env*`)
- Added `.vscodeignore` so only the theme, icons, README, changelog, and license are packaged (keeps `.env`, `.vscode/`, and `image.png` out of the `.vsix`)

### Fixed

- `repository.url` pointed at `wgrzr` instead of `wxgrzr`, which broke the Marketplace README preview image link

### Removed

- The unused `vsc-extension-quickstart.md`

---

## [1.5.0] – 2026-01-05

### Added

- MIT `LICENSE` file and `license` field in `package.json`
- Roughly 10 new Marketplace keywords (e.g. `dark mode`, `tsx`, `readable`, `cozy`) for discoverability

### Changed

- Rewrote the extension description with a clearer, less joke-driven pitch
- Dropped the `vim` and `developer` keywords
- Restored the `engines.vscode` requirement (`^1.77.0`) that was removed in 1.4.0

---

## [1.4.0] – 2026-01-05

### Changed

- Publisher changed from `wxgrzr` to `voidfaithnull`
- Theme label in `package.json` corrected from "Hypedown" to **Hyperdark**

### Removed

- Temporarily removed the `engines.vscode` lock (restored in 1.5.0)
- Empty `configuration` contribution (`"title": "Hyp"`)

---

## [1.3.3] / [1.3.2] – 2026-01-05

- Version bumps only; no user-facing changes

---

## [1.3.1] – 2026-01-05

### Added

- Refreshed the icon set (16/32/128/512) and marketplace metadata to support the Hyperdark branding
- Introduced explicit colors for bracket highlighting/pair guides along with clearer Lightbulb hint accents

### Changed

- Renamed the remaining Hypedown TS variant to **Hyperdark** and removed the unused duplicate theme file for a single, consistent marketplace listing
- Reframed the README/philosophy content with the new preview capture to better communicate the theme intent
- Tweaked JSX attributes, imported aliases, hover/suggest borders, and CodeLens coloring to sharpen TypeScript/React readability

---

## [1.3.0] – 2025-12-30

### Changed

- Refined documentation and marketplace positioning
- Clarified theme variants and intended use cases

---

## [1.2.1] – 2025-11-21

### Changed

- Removed the active border color on inputs, panel titles, and tabs for a flatter, borderless UI

---

## [1.2.0] – 2025-11-21

### Added

- **Hypedown TS** variant
- Enhanced semantic token support for:
  - Default library functions
  - Methods & properties
  - Types and interfaces

### Improved

- JSX / TSX tag, attribute, and embedded expression coloring for better component scanning
- Object and prop readability in dense React files
- String and quote tones to reduce white-on-white glare in template-heavy code
- Overall contrast balance without increasing visual noise

---

## [1.1.0] – 2025-11-21

### Initial Release

- Core Hypedown theme palette
- Focused on calm UI chrome and readable syntax highlighting
