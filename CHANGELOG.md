# Berglas Changelog

All notable changes to Berglas will be documented in this file. This file is maintained by humans and is therefore subject to error.

## [0.1.4] Unreleased
### Changed

## [0.1.3] 2019-06-18
### Changed
- cli: also allow `berglas://` prefixes
- core: properly convert to seconds for KMS rotation period during bootstrap
- core: support multiple containers being returned from the v1alpha API
- doc: update to match auto-generated KMS keyring

## [0.1.2] 2019-05-17
### Changed
- core: update dependencies to latest version
- dist: mark published binaries as executable
- pkg/auto: Panic on error. The former behavior of logging but not throwing an
  error can be restored by setting the environment variable
  `BERGLAS_CONTINUE_ON_ERROR` to `true`.

## [0.1.1] 2019-04-25
### Added
- pkg/auto: Retry transient errors
- pkg/retry: Add package for handling retries

## [0.1.0] - 2019-04-22
### Added
- Initial release
