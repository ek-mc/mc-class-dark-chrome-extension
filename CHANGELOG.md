## [Unreleased]

## [0.1.5] - 2026-03-07

### Fixed
- Improved login text readability on dark blue backgrounds by forcing light text color for login-text selectors.

## [0.1.5] - 2026-03-04

### Added
- Documented GitHub Actions workflows in README.

# Changelog

## [Unreleased]

## [0.1.4] - 2026-03-03
- Synced store package with latest dark theme behavior and placeholder SVG logic.
- Added Chrome Web Store assets and metadata files (`assets/icons/*`, `PRIVACY.md`, `STORE-LISTING.md`).
- Built updated store upload archive in `dist/`.
- Bumped extension version to `0.1.4`.

## [0.1.3] - 2026-03-03
- Added `LICENSE` file with MIT license.
- Bumped extension version to `0.1.3`.

## [0.1.2] - 2026-03-03
- Replaced external placeholder URL with inline SVG data URI (no third-party dependency).
- Added local `assets/placeholder.svg` reference asset.
- Bumped extension version to `0.1.2`.

## [0.1.1] - 2026-03-03
- Synced Chrome extension styles with latest Tampermonkey script.
- Added component-specific dark style coverage (Lesson/Accordion/Notifications/Absences/etc.).
- Added `content.js` to patch `NoPhoto.jpg` placeholders with a dark preview image.
- Updated manifest to inject both CSS and JS at `document_start`.
