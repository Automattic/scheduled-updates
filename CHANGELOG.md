# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.1-alpha] - unreleased

This is an alpha version! The changes listed here are not final.

### Changed
- Aligned handling of schedules that can't be found to return the same error messages.
- Scheduled Updates: Load API endpoints on WP.com so it works with public-api passthrough.

## [0.2.0] - 2024-02-26
### Added
- Show schedule information for scheduled plugin updates in wp-admin [#35917]

### Changed
- Fix up cron callback and schedule generation to make schedule execution work [#35885]

## 0.1.0 - 2024-02-26
### Added
- Generate initial package for Scheduled Updates [#35796]

[0.2.1-alpha]: https://github.com/Automattic/scheduled-updates/compare/v0.2.0...v0.2.1-alpha
[0.2.0]: https://github.com/Automattic/scheduled-updates/compare/v0.1.0...v0.2.0
