# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.3.1] - 2022-05-16
## Fixed
- Fixed missing Nightmare and Death Touch abilities.
- Deleted duplicate Flex Skill ability and corrected source.

## [2.3.0] - 2022-05-02
## Added
- Added cypher and artifact compendia for The Origin and The Banewarrens.

## [2.2.1] - 2022-04-13
## Fixed
- Fixed some typos in the Cyphers (Ptolus) compendium.

## [2.2.0] - 2022-04-07
## Added
- Compendium for power shifts.

## Fixed
- Armor from Ptolus now has the correct reference.

## [2.1.0] - 2022-04-07
## Added
- New Ptolus cypher compendium, which duplicates the regular cypher compendium, but with both the Ptolus and regular names. Cyphers that come with a specific level range have this level range in the level field, but the description still gives the general cypher level range. For example, the potion of rejunivation has a level range of 3–4, so it has a level of 1d2+2, while the rejuvinator cypher has a level of 1d6+2. Both are included in the item.

## Fixed
- Added missing force screen projector cypher.

## [2.0.3] - 2022-04-06
### Fixed
- References for weapons from Ptolus are now correctly labeled.

## [2.0.2] - 2022-04-06
### Fixed
- The Cypher (power boost) compendium was empty. It now contains the cyphers.

## [2.0.1] - 2022-04-05
### Fixed
- Onslaught had some `<hr>` too many.

## [2.0.0] - 2022-04-05
### Added
- Added compendia for abilities, ammo, armor, cyphers, equipment, and weapons for fantasy, modern, and sci-fi games. Sources are Cypher System Rulebook, Claim the Sky, First Responders, Godforsaken, Ptolus, Stay Alive, The Stars Are Fire, and We Are All Mad Here. Each item includes a page reference, which will be a workable link to the PDF if the PDFs are setup correctly with PDFoundry. No descriptive text is included.
- Added Home Scenes done by smaug18#2066, including a template scene for which you can use your own background image.

### Changed
- PDFoundry is now a dependency for this module, as the items contain document links to the source PDFs, if the PDF is present. PDFoundry is needed even if no PDF is present, so that the document link becomes an easily readable reference.

### Removed
- Removed the compendia with conversions of d20 material released under the SRD.

## [1.0.0] - 2021-11-05
### Added
- Added compendia for fantasy equipment, fantasy armor, fantasy weapons, fantasy ammo, modern equipment, modern armor, modern weapons, modern ammo, and meeples in five colors.