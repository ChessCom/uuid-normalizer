# Change Log

All notable changes to this project will be documented in this file based on the [Keep a Changelog](http://keepachangelog.com/) Standard.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased](https://github.com/gbprod/uuid-normalizer/compare/v1.3.0...HEAD)

- Fix bug in supporting denormalization of classes implementing `UuidInterface` (#35)

## [v1.3.0](https://github.com/gbprod/uuid-normalizer/compare/v1.2.2...v1.3.0)

- Drop php `<7.4` and Symfony `<=5.4`
- Remove scrutinizer & travis
- Use Github actions
- Fix Sf 6.1 deprecation warnings

## [v1.2.2](https://github.com/gbprod/uuid-normalizer/compare/v1.2.1...v1.2.2)

- Symfony 6 support
- Drop php `< 7.2` and Symfony unmaintained version
- Remove versioneye
- Upgrade scrutinizer & travis

## [v1.2.1](https://github.com/gbprod/uuid-normalizer/compare/v1.2.0...HEAD)

- Fix array of UuidInterface deserialization (#12)

## [v1.2.0](https://github.com/gbprod/uuid-normalizer/compare/v1.1.0...v1.2.0)

- Update dependencies to php 8, Symfony 5 and Ramsey Uuid 4
- Changing licence

## [v1.1.0](https://github.com/gbprod/uuid-normalizer/compare/v1.0.1...v1.1.0)

- Symfony 4 compatibility
- Add Contributing file
- Drop php 5.5 compatibility

## [v1.0.0](https://github.com/gbprod/uuid-normalizer/compare/v1.0.0...v1.0.1)

### Added

- Version eye badge
- Changelog
- Compatibility and tests for Symfony Serializer 3.1 and Ramsey/Uuid 3.3 and 3.4
- More examples in documentation

### Changed

- Scrutinizer use PSR2 codesniffer
- Use codecov instead of scrutinizer for coverage
