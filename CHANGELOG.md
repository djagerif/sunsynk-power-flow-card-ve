
# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased] - Development

## [1.0.1]
### Added
- Added Battery `warn_colour` variable to the battery section. Allows colour change when SOC drops below Shutdown SOC
- For Victron systems only. Added battery.tail_current variable to specify current(in A) that indicates Float. Default `2`

### Breaking Changed

### Changed
- `empty_capacity` minimum value raised from 50% to 80% to better support Lead Acid batteries
- Updated `Float` algorythm to use new `battery.tail_current` when `use_victron` flag is set

### Fixed
- Replaced missing font CSS Style entry for font-size 10.

### Removed


## [Released]

## [1.0.0] 20230815
- Initial Release