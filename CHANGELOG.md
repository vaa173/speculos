# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.7] - 2023-06-30

### Fixed
- Seproxyhal: Fix SeProxyHal emulation

## [0.2.6] - 2023-06-26

### Fixed
- Seproxyhal: Fix SeProxyHal issue when on LNSP / LNX and HAVE_PRINTF is enabled

## [0.2.5] - 2023-06-21

### Added
- API: Add a ticker/ endpoint to allow control of the ticks sent to the app

### Fixed
- OCR: Fix OCR on NanoX and NanoSP based on API_LEVEL_5 and upper
- Seproxyhal: Fix SeProxyHal emulation to match real devices behavior

## [0.2.4] - 2023-06-13

### Changed
- OCR: Lazy evaluation of screenshot content, performance improvement on Stax

### Fixed
- OCR: screenshot publish is no longer desynchronized with event publish

## [0.2.3] - 2023-06-05

### Fixed
- svc: Fixed emulation of os_lib_call for latest SDK API levels

## [0.2.2] - 2023-06-01

### Changed
- docker: Add blst library to the docker image
- launcher: If Speculos is able to determine the location of the SVC_Call and SVC_cx_call symbols in
            the application elf, it will only try to patch `svc 1` inside the functions.

## [0.2.1] - 2023-05-30

### Fixed
- deployment: re-ordering pypi.org package automatic push in order to avoid incomplete deployments

## [0.2.0] - 2023-05-30

### Changed
- package: Version is not longer customly incremented, but inferred from tag then bundled into the
           package thanks to `setuptools_scm`

## [0.1.265] - 2023-05-12

## [0.1.0] - 2021-07-21

- First release of Speculos on PyPi
