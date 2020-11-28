# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/). Legacy releases used an incrementing `R#` version scheme. Releases based on KP-Liberation v0.96.7a and greater adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and begin at v1.1.0 (as legacy releases would be v1.0).

## [Unreleased]

### Added

- Upstream changes in KP-Liberation [v0.96.7](https://github.com/KillahPotatoes/KP-Liberation/releases/tag/v0.96.7) and [v0.96.7a](https://github.com/KillahPotatoes/KP-Liberation/releases/tag/v0.96.7a).

## [r10] - 2020-11-27

### Added

- Two AAVP-7A1s added to each starting base.
- [A number of 3CB Factions uniforms](https://github.com/15thmeu/Liberation/issues/25) are now available, including:
  - Afghan Defense Ministry
  - Afghan Border Patrol
  - Afghan National Army
  - Afghan National Police
  - Takistan Police
  - Takistan Army
- VS Code settings for running common gulp tasks directly from the editor Tasks feature.
- Up-armored HMMWVs released in [RHS 0.5.3](http://www.rhsmods.org/mod/2#0.5.3) added to the build menu:
  - M1151 with M2, Mk19, and M240
  - M1152 and resupply vehicle (RSV) variant
  - M1165
- Laser designator batteries added to the arsenal.

### Changed

- Updated static map markers with current TeamSpeak URL: ts3.15thmeu.net.
- Changed mission description tagline: "Fight alongside members of the 15th MEU Realism Unit as you work together to Capture The Island."
- Updated the recruitment and rules billboards—thanks to [H. Taylor](https://15thmeu.net/index.php?/profile/169-1stlt-h-taylor/) for the graphics).

### Removed

- M998 and M1232 removed from the Takistan starting base.
- Old string translations that did not correspond to the changed strings.
- Build menu M1025s replaced by the up-armored M1151s.

## [r9] - 2020-10-09

### Added

- A selection of 3CB Factions weapons and accessories added to the arsenal, notably:
  - G3 variants
  - HK33K variants
  - MG3 variants
  - PSG1A1
- AAVP-7A1 added to the vehicle build menu.

### Changed

- Various project and Github files were updated for the 15th MEU Realism Unit.
  - The previous version of this fork last maintained by T. Caron (@Zul976) was rebased on KP-Liberation v0.96.6 with the assistance of J. Lane (@jmlane).
- Starting base vehicle spawn positions were adjusted.
- Liberation menu loadout features now default to the ACE Arsenal implementation and use the 15th MEU Public Server armory preset.
  - Arsenal can be accessed from the Liberation (deployment) menu, or from the action menu near the starting base, FOBs, respawn vehicles, or purchased arsenal crates.
  - ACE interaction menu will no longer show the arsenal option on arsenal boxes.

### Fixed

- Fixed reversed camo on the M998, M1045, and M1078A1R SOV in both desert and woodland presets.
- Fixed texture locality issue on recruitment billboards.
- Fixed various SQF issues with the custom OPFOR faction presets.

### Removed

- Arsenal crates and supply crate at starting bases have been removed with the arsenal changes.

[r9]: https://github.com/15thmeu/Liberation/compare/v0.96.6...r9
[r10]: https://github.com/15thmeu/Liberation/compare/r9...r10
[Unreleased]: https://github.com/15thmeu/Liberation/compare/r10...HEAD
