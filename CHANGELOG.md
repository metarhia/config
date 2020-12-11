# Changelog

## [Unreleased][unreleased]

To be released in 2.0.0

- Use `metavm` instead of `vm`
- Return promise with sections from constructor
- Move `names` to `options` argument
- Use Github Actions instead of Travis CI

## [1.x][] - 2020-09-06

- Remove `options.priority`
- Tests implemented (metatests)
- Load just specified sections (constructor argument `names`)

## [0.x][] - 2019-12-23

- Load configuration in vm sandbox
- Support configuration files order: `options.priority`
- Support mode (log files second ext): `options.mode`
- Support passing custom sandbox: `options.sandbox`

[unreleased]: https://github.com/metarhia/config/compare/v1.x...HEAD
[1.x]: https://github.com/metarhia/config/compare/v0.x...v1.x
[0.x]: https://github.com/metarhia/config/releases/tag/v0.x
