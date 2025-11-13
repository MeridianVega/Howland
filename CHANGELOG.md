# Changelog

All notable changes to Howland will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [mobile-v0.1.1] - 2025-11-13

### Changes
- Fixed: properly configure iOS manual signing per research
- Fixed: configure manual signing in iOS project settings
- New: add app store targets, improve naming, and add release documentation
- New: add version sync verification and enable ProGuard
- Fixed: correct workflow secrets context and add app store assets
- New: add mobile release pipeline (Android ready, iOS pending DUNS)
- New: add Electron desktop and Capacitor mobile apps with production features



## [desktop-v0.1.0] - 2025-11-06

### Changes
- New: initial desktop release v0.1.0
- New: bump electron to v0.0.1 and add build cache cleanup to deploy workflow
- Fixed: update workflow to use RELEASES_PAT and set electron to v0.1.0 beta
- Fixed: restore package-lock.json to working state before electron changes
- Fixed: remove electron and mobile from workspaces to prevent Docker build conflicts
- New: add version-based auto-release workflow and remove loading states
- New: add Electron desktop and Capacitor mobile apps with production features

**Note**: This changelog is automatically updated with each release.
