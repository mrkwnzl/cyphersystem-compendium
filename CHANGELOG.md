# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.3.0] - 2022-10-31
### Added
- Compendium for basic creatures and NPCs.
- Compendium for vehicles.
- Compendium for starships.
- Compendium for descriptor characteristics.
- Compendium for inabilities.
- Compendium for post-apocalyptic armor.
- Compendium for post-apocalyptic equipment.
- Compendium for post-apocalyptic weapons.
- Compendium for crafting skills.
- Compendium for expanded skill list (mainly with skills from descriptors).
- Compendium for CSRD Journals, containing the complete Cypher SRD as a journal with linked items, so that you can create your character with a few drag & drop actions.
- Roll tables for type background connections.

### Changed
- Compatiblity with Cyhper system v2.0.0 and Foundry V10. Earlier versions are not supported.

### Removed
- Removed the cost of equipment from the item descriptions, since the equipment tables are now part of the CSRD Journal, which have the items sorted by cost.

## [3.2.0] - 2022-08-09
### Added
- Compendium for basic skills.
- Compendium for cypher roll tables.

### Changed
- The abilities now contain links to other abilities mentioned. **Note:** I think I messed it up a bit and the item IDs might have changed.

## [3.1.0] - 2022-07-30
### Added
- Compendia for creatures, NPCs, and supervillains.

### Fixed
- Cyphers now should have deferred inline roll buttons for all rolls mentioned in the description (except for the level, as that’s rolled on the PC sheet).

## [3.0.1] - 2022-07-29
### Changed
- The module is now compatible with Foundry VTT v9.

## [3.0.0] - 2022-07-28
### Changed
- Changed the module to be the Cypher SRD Compendium. It now includes all abilities, cyphers, artifacty, and equipment from the CSRD.

### Removed
- Anything not in the CSRD has been removed with two exceptions of two compendia: (1) Meeples, and (2) Scenes. If you want to keep anything, you need to import that into your world.

## [2.3.3] - 2022-06-05
### Fixed
- Fixed a typo in the Cypher compendium:
  - "Rejunivator" -> "Rejuvenator"
- Fixed some typos in the Cypher (Ptolus) compendium:
  - "Potion of rejunivation || Rejunivator" -> "Potion of rejuvenation || Rejuvenator"
  - "Potion of greater rejunivation || Rejunivator" -> "Potion of greater rejuvenation || Rejuvenator"
  - "Potion of superior rejunivation || Rejunivator" -> "Potion of superior rejuvenation || Rejuvenator"

## [2.3.2] - 2022-06-04
### Fixed
- Fixed some typos in the Cypher (Ptolus) compendium:
  - "Potion of egale eye || Eagleseye" -> "Potion of egale eye || Eagleseye"
  - "Potion of mage hands || Manipulation beam" -> "Potion of mage hand || Manipulation beam"

## [2.3.1] - 2022-05-16
### Fixed
- Fixed missing Nightmare and Death Touch abilities.
- Deleted duplicate Flex Skill ability and corrected source.

## [2.3.0] - 2022-05-02
### Added
- Added cypher and artifact compendia for The Origin and The Banewarrens.

## [2.2.1] - 2022-04-13
### Fixed
- Fixed some typos in the Cyphers (Ptolus) compendium.

## [2.2.0] - 2022-04-07
### Added
- Compendium for power shifts.

### Fixed
- Armor from Ptolus now has the correct reference.

## [2.1.0] - 2022-04-07
### Added
- New Ptolus cypher compendium, which duplicates the regular cypher compendium, but with both the Ptolus and regular names. Cyphers that come with a specific level range have this level range in the level field, but the description still gives the general cypher level range. For example, the potion of rejunivation has a level range of 3–4, so it has a level of 1d2+2, while the rejuvinator cypher has a level of 1d6+2. Both are included in the item.

### Fixed
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