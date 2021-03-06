# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic
Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased

## [1.2.0] - 2020-02-12

### Added
- Added support for 386 Windows

### Changed
- Replace Travis CI with Github Actions
- Use github.com/sensu-community/sensu-plugin-sdk@v0.6.0
- Replace dep with Go modules

### Fixed
- Fix Windows build
- Truncate pagerduty summary to 1024 bytes as per spec

## [1.1.0] - 2019-03-15

### Changed
- Updated travis, goreleaser configurations.
- Updated license.
- Added hostname and check name to summary alert

### Removed
- Removed redundant post deploy scripts for travis.

## [1.0.2] - 2019-01-09
### Added
- Use PAGERDUTY_TOKEN envvar for default value for accessToken, for security. This is a backwards compatible change.

## [1.0.1] - 2018-12-12
### Added
- Bonsai Asset Index configuration

### Changed
- Dropped odd platforms and architectures from the build matrix (e.g.
dragonfly and mips).

## [1.0.0] - 2018-12-07

### Changed
- No longer JSON serializing custom details (no need to)

## [0.0.3] - 2018-12-05

### Changed
- Updated GITHUB_TOKEN

## [0.0.2] - 2018-12-05

### Changed
- Updated dep

## [0.0.1] - 2018-12-05

### Added
- Initial release
