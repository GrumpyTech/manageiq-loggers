# Changelog

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [0.4.2] - 2020-01-14
### Fixed
- Revert "Change CloudWatch log_group to be the namespace if it exists" [(#16)](https://github.com/ManageIQ/manageiq-loggers/pull/16)

## [0.4.1] - 2020-01-06
### Fixed
- Change CloudWatch logger log_group and log_stream values for easier debugging and unique identifiers [(#15)](https://github.com/ManageIQ/manageiq-loggers/pull/15)
- Enhancements to the journald logger to allow for easier debugging [(#11)](https://github.com/ManageIQ/manageiq-loggers/pull/11)

## [0.4.0] - 2019-08-15
### Changed
- The Cloud Watch logger will now also broadcast its log messages to the container logger [(#10)](https://github.com/ManageIQ/manageiq-loggers/pull/10)

## [0.3.0] - 2019-05-30
### Added
- Add a Journald Logger [(#5)](https://github.com/ManageIQ/manageiq-loggers/pull/5)
- Add a cloud watch logger [(#9)](https://github.com/ManageIQ/manageiq-loggers/pull/9)

## [0.2.0] - 2019-05-03
### Added
- Log the request id in the container logger if present [(#7)](https://github.com/ManageIQ/manageiq-loggers/pull/7)

## [0.1.1] - 2019-02-27
### Fixed
- Always sync container STDOUT logs [(#4)](https://github.com/ManageIQ/manageiq-loggers/pull/4)

## [0.1.0] - 2019-01-08

[Unreleased]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.4.2...master
[0.4.2]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/ManageIQ/manageiq-loggers/compare/v0.1.0...v0.1.1
