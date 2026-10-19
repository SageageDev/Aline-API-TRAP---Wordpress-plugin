# Changelog

## [0.1.4.5] - 2026-07-29

### Fixed
- `class-gfapitrap.php`: Fixed PHP Warning "Trying to access array offset on null" by casting `$existingIndividuals` to array before iterating, guarding against null responses from `json_decode`.

### Changed
- `form_scripts/utmparameters.js`: Removed `Internet` as a market source. UTM-tagged traffic that doesn't match a known pattern (social, organic, display) now falls through to `WEB - Company Website`.

## [0.1.4.4] - 2026-06-29

### Fixed
- `form_scripts/utmparameters.js`: Fixed fallback value for market source.

### Changed
- `form_scripts/utmparameters.js`: Added referral tracking support.
- `form_scripts/utmparameters.js`: Removed individual Google paid search as a distinct market source.
