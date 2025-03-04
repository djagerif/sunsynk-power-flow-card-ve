## [1.4.0]
### Added
 - Add auto_scale to AUX loads.
 
### Breaking Changed
 
### Changed
 
### Fixed
 
### Removed


## [1.3.0]
### Added
 
### Breaking Changed
 
### Changed
 - kWh display values rounded to 1 decimal place, if exist, otherwise to integer.
 - Remove <space> from battery SOC % display.

### Fixed
 
### Removed


## [Released]

## [1.2.0]
### Added
 - Added `environment_temp` sensor to main screen. (No Unit Scale due to space limitation).

### Breaking Changed
 
### Changed
 - Updated Battery Temperature locked to 1 decimal place.

### Fixed


### Removed

## [1.1.0]
### Added
 - Added auto_scale as per source distribution.

### Breaking Changed
 
### Changed

### Fixed
 - Moved a few icons for better visibility.

### Removed

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
