# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1] - 2020-04-16
### Added
- Publicly accessible functions for each endpoint call on the PrivacyApi class' objects.
- README with instructions on how to use the library.

### Changed
- All test cases, which now use the new syntax for making calls to the api.
- Response types to make client usage more intuitive (using await instead of (await).data).

### Removed
- Logic which had clients call requests and pass in the api instead of the opposite.

## [0.0.1] - 2020-04-12
### Added
- Initial release with all endpoints functional with accompanying tests, documentation.

[Unreleased]: https://github.com/olivierlacan/keep-a-changelog/compare/v1.0.1...HEAD
# [1.0.1]: https://github.com/jeremigendron/privacy.com/compare/v0.3.0...v1.0.0