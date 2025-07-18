# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2025-07-14

### Added

- Event hooks: `on` and `off` methods for `tagClick`, `tagHover`, and `tagLeave` events, allowing custom interactivity (tooltips, pop-ups, etc.).
- Documentation updated to describe event hooks and usage examples.

## [1.0.2] - 2025-06-21

### Fixed

- Tag opacity now correctly reflects depth: closer tags are more opaque, further tags are more transparent.

## [1.0.1] - 2025-06-20

### Fixed

- Speed slider and initialization now respect UI value (minimum speed clamp lowered, velocity logic fixed)
- node_modules no longer tracked by git

### Changed

- .npmignore and .gitignore updated for cleaner repo and npm package

## [1.0.0] - 2025-06-20

### Added

- Initial TypeScript conversion and type definitions
- ESM and CJS builds with Rollup
- React and Vue wrappers
- Unit tests (Vitest)
- Accessibility improvements (keyboard navigation, ARIA, focus styles)
- SVG/image tag support
- GitHub Actions CI/CD
- Community files: CONTRIBUTING, LICENSE, issue/PR templates

### Changed

- Modernized build and distribution for npm

### Fixed

- N/A
