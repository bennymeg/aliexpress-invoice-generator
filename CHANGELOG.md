# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog] and this project adheres to [Semantic Versioning].

## [Unreleased]

- Nothing at the moment

## [2.0.0] - 2019-12-12

### Added

- Page action as a secondary way to create the PDF

### Changed

- Generate PDFs directly inside the extension without relying on the print interface

### Removed

- Article icon in line item

## [1.0.0] - 2019-09-24

### Changed

- Prevent page margin hacks and let the user configure the margin via print preview (#1)

### Fixed

- Add support for buyer addresses with 2 lines (#2)
- Only show discount when available

## [0.1.0] - 2019-08-31

### Added

- Support for order discounts
- Disclaimer about inaccuracies due to currency conversions

### Fixed

- Use payment date as a fallback for the order date if the latter isn't available

## [0.0.1] - 2019-08-16

Initial release

[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html
[Unreleased]: https://nosuchdomain.mooo.com/git/doc/aliexpress-invoice-generator/compare/2.0.0...master
[2.0.0]: https://nosuchdomain.mooo.com/git/doc/aliexpress-invoice-generator/compare/1.0.0...2.0.0
[1.0.0]: https://nosuchdomain.mooo.com/git/doc/aliexpress-invoice-generator/compare/0.1.0...1.0.0
[0.1.0]: https://nosuchdomain.mooo.com/git/doc/aliexpress-invoice-generator/compare/0.0.1...0.1.0
[0.0.1]: https://nosuchdomain.mooo.com/git/doc/aliexpress-invoice-generator/src/tag/0.0.1