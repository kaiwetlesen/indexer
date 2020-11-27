# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.7-alpha.0] - 2020-11-17
### Changed
- Update `@graphprotocol/common-ts` to 0.3.13

## [0.3.4] - 2020-10-29
### Changed
- Update and pin all dependencies

## [0.3.3] - 2020-10-28
### Fixed
- Preserve `$DAI` on updates
- Fix injecting `$DAI` into `null` variables
- Fix adding `$DAI` to `null` cost models in `setCostModel` mutation
- Don't accidentally clear non-`$DAI` variables

### Added
- Inject `$DAI` into new models when they are created

### Changed
- Change cost model variable columns in the database to JSONB

## [0.3.2] - 2020-10-27
### Added
- Add 'deleteIndexingRules' mutation

### Fixed
- Fix clearing of cost models

## [0.3.1] - 2020-10-15
### Changed
- Update common-ts to 0.3.3

## [0.3.0] - 2020-10-13
### Changed
- Update common-ts to 0.3.2

### Added
- Add cost model management with tests
- Add helpers for allocation IDs and attestation signer keys

## 0.2.6 - 2020-10-13
### Added
- Move indexing rule management here from `@graphprotocol/common-ts`

[Unreleased]: https://github.com/graphprotocol/indexer/compare/v0.3.7-alpha.0...HEAD
[0.3.7-alpha.0]: https://github.com/graphprotocol/indexer/compare/v0.3.4...v0.3.7-alpha.0
[0.3.4]: https://github.com/graphprotocol/indexer/compare/v0.3.3...v0.3.4
[0.3.3]: https://github.com/graphprotocol/indexer/compare/v0.3.2...v0.3.3
[0.3.2]: https://github.com/graphprotocol/indexer/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/graphprotocol/indexer/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/graphprotocol/indexer/compare/v0.2.6...v0.3.0