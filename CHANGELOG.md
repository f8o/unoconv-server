# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.2.7]

### Fixed

* Set UTF8 encoding when converting documents to txt.

## [0.2.5] - 2018-01-03

### Fixed

* Error in response `Content-Disposition` header in none-ascii filename.

## [0.2.4] - 2017-12-28

### Changed

* Export `createApp` as a function, for getting instance later.
* Update documentation and fix usage.

## [0.2.0] - 2017-12-28

### Added

* RAW upload support.

### Changed

* Format error response with JSON.

## [0.1.0] - 2017-12-27

### Added

* Basic `multipart/form-data` upload and convert support.
