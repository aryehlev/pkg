# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [5.15.0] - 2023-03-05
### Added
- New Mutex2 and RWMutex2 which corrects the original Mutex's design issues.
- Deprecation warning for original Mutex usage.

## [5.14.0] - 2023-02-25
### Added
- Added `timext.NanoTime` for fast low level monotonic time with nanosecond precision.

[Unreleased]: https://github.com/go-playground/pkg/compare/v5.15.0...HEAD
[5.15.0]: https://github.com/go-playground/pkg/compare/v5.14.0...v5.15.0
[5.14.0]: https://github.com/go-playground/pkg/commit/v5.14.0