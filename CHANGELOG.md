# Changelog

All notable changes to Laravel Rules to Schema are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2026-02-13

Initial release — convert Laravel validation rules into JSON Schema Draft 2020-12
definitions.

### Added

- Conversion of 25+ built-in Laravel validation rules to JSON Schema.
- Handling of nested objects, arrays, and wildcard (`*`) rules.
- Support for conditional rules (`required_if`, `required_with`, and similar).
- Extensible rule-parser system — register custom parsers via config.
- Auto-registered Laravel service provider.

[Unreleased]: https://github.com/specdocular/laravel-rules-to-schema/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/specdocular/laravel-rules-to-schema/releases/tag/v0.1.0
