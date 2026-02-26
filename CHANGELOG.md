# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.0.0] - 2026-02-26

### Updated

-   Updated to ardrive-core-js@4.0.0
-   Changed remaining hardcoded arweave.net references to ardrive.net

## [3.1.0] - 2025-10-22

### Updated 

-   Updated to ardrive-core-js@3.1.0

## [3.0.5] - 2025-10-16

### Fixed

-   Fixed contentType handling to use logical OR operator instead of nullish coalescing to properly fallback to MIME type detection from file extension

## [3.0.4] - 2025-10-13

### Fixed

-   Correctly use seconds for Unix-Time Tag on ArFS Entities

## [3.0.3] - 2025-08-01

### Fixed

-   Fixes manifest lastModifiedDate timestamp to be milliseconds instead of seconds

## [3.0.2] - 2025-06-25

### Changed

-   Upload using turbo-sdk
-   Use @ardrive/ardrive-promise-cache over Core implementation
-   Updates several deps

## [3.0.1] - 2025-06-20

### Changed

- Updated ardrive-core-js dependency to version 3.0.1 to allow for empty App-Version tags

## [3.0.0] - 2025-06-16

### Added

-   Implemented support for ArFS v0.15 (Drive Privacy Updates)
