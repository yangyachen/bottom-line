All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.6.3] - 2019-08-29
### Fixed
- dev deps audit issues

## [0.6.2] - 2019-06-06
### Fixed
- deps audit issue, related to development (eslint), not the code (0.6.2 is not released to npm as a result)

## [0.6.1] - 2019-06-05
### Fixed
- deps audit issue, related to docs generating, not the code (0.6.1 is not released to npm as a result)

## [0.6.0] - 2019-05-12
### Added
- `pick` and `omit` methods
### Changed
- babel config for `dist` transpiled code upgraded, to transpile less features

## [0.5.0] - 2019-04-09
### Added
- `coalesce` method

## [0.4.1] - 2019-01-31
### Fixed
- `setImmutable` not allowing number as path and allowing other incorrect/unexpected values as paths

## [0.4.0] - 2019-01-30
### Added
- `insertSeparator` method

## [0.3.1] - 2018-12-09
### Fixed
- added missing export of `setImmutable` to index

## [0.3.0] - 2018-12-09
### Fixed
- missing labels in `set` tests
- disabled removing unused labels in tests
### Changed
- improved one `set` test
### Added
- `setImmutable` method

## [0.2.0] 2018-12-09
### Added
- `set` function
- @todo for get/set methods, that should test and support correctly Sets, Maps, etc.
- dev stuff: linter, editorconfig

### Changed
- upgraded library template
- switched code to es modules
- linted code

## [0.1.2] - 2018-11-09
### Fixed
- fixed `mapValues` calling the method twice

## [0.1.1] - 2018-05-31
### Changed
- README update

## [0.1.0] - 2018-05-31
### Added
- `get` function 
- `getMultiple` function 
- `isEmpty` function 
- `last` function 
- `mapValues` function 
