# Changelog

All notable changes, aerodynamic simulation enhancements, and version history for GeoFS-V3.9 Realism Pack are documented in this file.

---

## [3.9.0] - Unified Metadata

### Changed

- Standardize the userscript metadata and version across the V3.9 ecosystem.
- Match only the GeoFS main site and activate only when it reports V3.9.

---

## [Unreleased]

### Changed

- **HUD Tab Label**: Renamed registered HUD tab to `REALISM`.
- **Theme Alignment**: Updated physics and systems toggles, G-meter readouts, and visual indicators to neutral `#dddddd` and green `#4caf50`.
- **Audio Source**: Updated Boeing 737 SFX audio script source to raw.githack.com repository.
- **Favicon Metadata**: Switched userscript icon reference to the official GeoFS favicon.

---

## [2.0.7] - GeoFS V3.9 Compatibility

### Changed

- Start only after GeoFS reports V3.9; remain inactive on other or unrecognized versions.
- Update compatibility documentation and version metadata.

---

## [2.0.2] - Ground Handling And Aerodynamic Damping

### Added

- **Multi-Surface Friction Models**: Differentiated tire friction coefficients across tarmac, concrete, grass, and unimproved dirt strips.
- **Dynamic Wind Shear**: Procedural boundary-layer gusts based on altitude above ground level (AGL).

### Fixed

- **Camera Shake Damping**: Balanced high-G cockpit camera vibration during transonic flight to maintain instrument legibility.
- **Audio Clipping Prevention**: Fixed audio buffer overlap during rapid throttle bursts.

---

## [2.0.0] - Immersive Physics Engine Overhaul

### Added

- **Dynamic G-Force Simulation**: High-G blackout and negative-G redout visual feedback algorithms.
- **Cockpit Audio Synthesis**: Engine spool acoustics, wind noise generation, and structural creaking sounds.

---

## [1.0.0] - Initial Production Release

Initial release of the environmental aerodynamics and cockpit realism framework for GeoFS.
