# Changelog

All notable changes to NK Bot Service Manager will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/),
and this project follows Semantic Versioning.

## [Unreleased]

### Planned
- Further UI and usability improvements
- Expanded bot monitoring and management features
- Additional community translations
- Linux agent support
- Web-based management interface

## [0.1.0-alpha.1] - 2026-10-04

### Added
- Initial public Alpha release
- Central Windows service for bot process management
- Add, edit and remove managed bots
- Support for Batch/CMD, executables, Python and Node.js bots
- Start, stop and restart bot processes
- Automatic restart after bot crashes
- Configurable restart delay
- Per-bot working directory and command-line arguments
- Custom runtime executable support
- Live bot console
- Sending console commands to supported bots
- Colored INFO, SYSTEM, ERROR and INPUT messages
- Console search and level filtering
- Session-based logging
- Current session stored as `BotName_latest.log`
- Automatic GZIP compression of previous sessions
- Bot → Session log navigation
- Configurable log retention and maximum log storage
- Main NKBSM system tray icon
- Optional individual system tray icons for bots
- Custom bot tray icons
- Numbered NKBSM fallback icons
- Start, stop, restart, console, logs and edit actions from the tray
- Automatic light/dark tray context menu
- Close-to-tray support
- Optional minimized startup
- English and German localization
- Community-extensible JSON language files
- Crowdin-compatible localization structure
- Configurable time zone and 12/24-hour time format
- GitHub Releases based update checking
- Automatic and manual update checks
- Update changelog display
- Windows x64 self-contained installer
- Automatic Windows service installation and configuration

### Known Limitations
- Alpha software; bugs and breaking changes may occur
- Windows x64 only
- Linux support is not yet available
- Web management is not yet available

[0.1.0-alpha.1]: https://github.com/NiceKype/NK-Bot-Service-Manager/releases/tag/v0.1.0-alpha.1
