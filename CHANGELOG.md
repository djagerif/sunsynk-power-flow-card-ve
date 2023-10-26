
# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased] - Development

## [1.1.0]
### Added
 - Added auto_scale as per source distribution.

### Breaking Changed
 
### Changed

### Fixed
 - Moved a few icons for better visibility.

### Removed


## [Released]

## [1.0.1]
### Added
- Added Battery `warn_colour` variable to the battery section. Allows colour change when SOC drops below Shutdown SOC
- Added Battery `tail_current` variable to specify current(in A) that indicates Float. Default `2`

### Breaking Changed

### Changed
- `empty_capacity` minimum value raised from 50% to 80% to better support Lead Acid batteries
- Updated `Float` algorythm to use new battery `tail_current` variable.

### Fixed
- Replaced missing font CSS Style entry for font-size 10
- Removed duplicate Inverter status indicator

### Removed


## [Released]

## [1.0.0] 20230815
- Initial Release
