# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [Unreleased](https://github.com/inspirum/coding-standard-php/compare/v1.6.0...master)


## [v1.6.0 (2024-05-17)](https://github.com/inspirum/coding-standard-php/compare/v1.5.0...v1.6.0)
### Removed
- Removed custom property values for `SlevomatCodingStandard.Functions.ArrowFunctionDeclaration` rule


## [v1.5.0 (2024-05-17)](https://github.com/inspirum/coding-standard-php/compare/v1.4.0...v1.5.0)
### Added
- Added exclude for `Generic.Formatting.MultipleStatementAlignment.NotSame` rule
### Removed
- Removed exclude for `SlevomatCodingStandard.Classes.SuperfluousAbstractClassNaming.SuperfluousPrefix` rule
- Removed exclude for `SlevomatCodingStandard.Classes.SuperfluousInterfaceNaming.SuperfluousSuffix` rule
- Removed exclude for `SlevomatCodingStandard.TypeHints.ReturnTypeHint.UselessAnnotation` rule
- Removed exclude for `SlevomatCodingStandard.TypeHints.ParameterTypeHint.UselessAnnotation` rule
- Removed exclude for `SlevomatCodingStandard.TypeHints.PropertyTypeHint.UselessAnnotation` rule


## [v1.4.0 (2023-09-18)](https://github.com/inspirum/coding-standard-php/compare/v1.3.0...v1.4.0)
### Added
- Added exclude for `Squiz.PHP.NonExecutableCode.Unreachable` rule
- Added exclude for `Squiz.Commenting.FunctionComment.SpacingAfterParamType` rule
### Fixed
- Fixed invalid properties for `SlevomatCodingStandard.Namespaces.FullyQualifiedGlobalFunctions` rule


## [v1.3.0 (2023-02-08)](https://github.com/inspirum/coding-standard-php/compare/v1.2.0...v1.3.0)
### Changed
- Updated `dealerdirect/phpcodesniffer-composer-installer` to version `^1.0`
- Updated `doctrine/coding-standard` to version `^11.0`


## [v1.2.0 (2022-07-04)](https://github.com/inspirum/coding-standard-php/compare/v1.1.1...v1.2.0)
### Changed
- Updated `doctrine/coding-standard` to version `^10.0`


## [v1.1.1 (2022-07-04)](https://github.com/inspirum/coding-standard-php/compare/v1.1.0...v1.1.1)
### Added
- Added exclude `SlevomatCodingStandard.Commenting.RequireOneLinePropertyDocComment.MultiLinePropertyComment` rule


## [v1.1.0 (2022-07-04)](https://github.com/inspirum/coding-standard-php/compare/v1.0.1...v1.1.0)
### Changed
- Better support for PHP 8.1 (Update `slevomat/coding-standard` to `^8.0`)


## [v1.0.1 (2022-06-07)](https://github.com/inspirum/coding-standard-php/compare/v1.0.0...v1.0.1)
### Added
- Added support for PHP `^7.4`


## v1.0.0 (2022-05-20) 
### Added
- Added `InspirumCodingStandard` PHPCS standard
