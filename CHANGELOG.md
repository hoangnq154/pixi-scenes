# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.0] - 2019-09-16
### Added
- Tracking if the scene ran using 'hasRun' property
- Destroy function in scenes, called at removing a scene that ran
### Changed
- Init is now called at first run instead of after adding to manager

## [1.3.0] - 2019-09-12
### Added
- Stopping scenes
- Removing scenes
- Getting active scene name
- Retrieving a list of scene names
- Some code docs

## [1.2.0] - 2019-09-03
### Added
- Seperate build output for ESM to support usage as module
### Changed
- Library now accessible from under the PIXI namespace to be consistent with other plugins

## [1.1.0] - 2019-07-19
### Changed
- Rename from states to scenes
### Fixed
- Corrected deltatime in update

## [1.0.0] - 2019-07-10
### Added
- Basic setup of the plugin to be used as a seperate module
