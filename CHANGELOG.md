# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2023-12-12
- Added PHP 8.2 and 8.3 support
- Dropped `heroku-18` support
- Dropped PHP 7.3, 7.4 and 8.0 support
- Upgraded Swoole to v5.1.1 for PHP 8.3
- Upgraded OpenSwoole to v22.1.0 for PHP 8.3
- Updated Swoole to v4.8.13
- Updated OpenSwoole to v4.12.1
- Updated [Relay](https://github.com/cachewerk) to v0.6.8
- Updated PhpRedis to v6.0.2
- Updated igbinary to v3.2.15
- Updated msgpack to v2.2.0

## [1.2.6] - 2022-10-11
- Added support for `heroku-22` stack
- Added [OpenSwoole](https://github.com/openswoole/swoole-src) v4.12.0
- Updated [Relay](https://github.com/cachewerk) to v0.4.6
- Updated PhpRedis to v5.3.7
- Updated Swoole to v4.8.12

## [1.2.5] - 2022-01-14
- Updated Swoole to v4.8.6
- Updated PhpRedis to v5.3.5
- Updated igbinary to v3.2.7

## [1.2.4] - 2021-12-10
- Added [PHP 8.1](https://devcenter.heroku.com/changelog-items/2304) builds
- Updated [Relay](https://relaycache.com) to v0.2.2
- Updated Swoole to v4.8.3

## [1.2.3] - 2021-10-26
- Updated [Relay](https://relaycache.com) to v0.2.0
- Updated igbinary to v3.2.6
- Updated Swoole to v4.8.0

## [1.2.2] - 2021-06-23
- Updated Relay to v0.1.1
- Updated igbinary to v3.2.3

## [1.2.1] - 2021-05-26
- Added Relay configuration file
- Enabled msgpack for PhpRedis
- Fixed `require` blocks for Relay and PhpRedis

## [1.2.0] - 2021-05-26
- Added [Relay](https://relaycache.com) v0.1.0
- Added [MessagePack](https://github.com/msgpack/msgpack-php) v2.1.2
- Updated Swoole to v4.6.7
- Updated PhpRedis to v5.3.4
- Updated igbinary to v3.2.2

## [1.1.1] - 2021-05-05
- Updated Swoole to v4.6.4
- Fixed demo app output for Swoole

## [1.1.0] - 2021-03-26
- Added [Swoole](https://github.com/swoole/swoole-src) v4.6.4
- Overhauled demo app
- Only build on push to `main` branch
- Make repos after successful build workflow
- Sync repos when a release is published
- Run builds for pull requests

## [1.0.0] - 2021-03-10
### Added
- Initial release

[Unreleased]: https://github.com/cachewerk/heroku-php-extensions/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.6...v2.0.0
[1.2.6]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.5...v1.2.6
[1.2.5]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.4...v1.2.5
[1.2.4]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.3...v1.2.4
[1.2.3]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.2...v1.2.3
[1.2.2]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.1...v1.2.2
[1.2.1]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.1.1...v1.2.0
[1.1.1]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/cachewerk/heroku-php-extensions/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/cachewerk/heroku-php-extensions/releases/tag/v1.0.0
