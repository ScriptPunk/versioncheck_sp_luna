# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.2] - 2023-02-28

### Fixed
- Fix for config value ConfigData.IgnoredInvisibilityObjects not working in some scenarios.

## [1.0.1] - 2023-02-27

### Added
- Added Config.EsxVersion to `editable\config\shared.lua` to support both new and old versions of ESX
- Added ESX initialization logic to `editable\scripts\shared.lua` for additional configuration if you have changed the core ESX getSharedObject() method name.
- Added the `sp_luna_debug` command for the server terminal and the in-game console to help with debugging installation issues.
- Added automatic version checks
