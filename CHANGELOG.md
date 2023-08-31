# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.10.0] - 2023-08-31
### Changed
- For performance reasons, the Cypher System Rulebook has been divided into several journals, one per chapter. The old Cypher System Rulebook journal has been changed to an index that links to the corresponding chapter journal, so that links you have set to this journal aren’t useless. But you still might want to update your links.

### Removed
- Images for scenes, meeplesn, and icons have been removed. If you are using any scene or meeple from earlier versions of the CSRD Compendium, you must do two things, and you can do these things now:

  (1) Install the Cypher System Community Content Module, and either

  (2a) remove the scenes or meeples and import them anew from the Cypher System Communty Content module or

  (2b) update the path of any missing asset. 

  For meeples, that’s from  
  `/modules/cyphersystem-compendium/icons/` to 
  `/modules/cyphersystem-community-module/img/meeples/`.

  For scenes, that’s from  
  `/modules/cyphersystem-compendium/img/scenes/` to 
  `/modules/cyphersystem-community-module/img/smaug18/scenes/`. 

  For the overlay, that’s from  
  `/modules/cyphersystem-compendium/img/overlays/` to
  `/modules/cyphersystem-community-module/img/smaug18/overlays/`. 

## [3.9.0] - 2023-07-30
### Added
- Creatures/NPCs and vehicles now come with pre-made token images based on their type (meaning that not each one has an individual icon; for example orc and goblins have the same token all goblinoids got, and all magical beasts have the same one as well).

### Deprecated
- This will be the last version which comes with the images from scenes, meeples, and icons. They will be removed in v3.10.0. If you have scenes or icons from earlier versions of the CSRD compendium, please install the [Cypher System Community Content module](https://foundryvtt.com/packages/cyphersystem-community-module) and replace the scenes and meeples from the ones in there! If you still have old items (equipment) from v1 or v2 of the CSRD Compendium, please also replace those with ones from a v3 release. This is needed to slim down the module in file size.

## [3.8.0] - 2023-06-28
### Added
- The compendia are now sorted into folders.

### Changed
- The CSRD Compendium is now only compatible with Foundry V11 or higher.
- The CSRD Compendium requires the Cypher System v2.7.0 or higher.

### Fixed
- The descriptions of Predictive Model and Premonition are now correct.

## [3.7.0] - 2023-05-24
### Added
- New rulebooks for the superhero, horror, and fairy tale genres. This includes a number of new creatures, NPCs, cyphers & artifacts, and equipment.

### Removed
- The Technofantasy Ruleset is now part of the Cypher System Community Module.
- The Meeples are now part of the Cypher System Community Module.
- The pre-made scenes are now part of the Cypher System Community Module.

### Fixed
- The ability Driving on the Edge now has the correct description.
- Typo in the name of the Silicon Parasite has been fixed.
- The Vampire creature now has the correct level.
- Some typos in the Cypher System Rulebook have been corrected.

## [3.6.0] - 2023-02-24
### Added
- The additions to the CSRD from 2023-02-10 have been added. This now includes the Science Fiction Rulebook, the Fantasy Rulebook, and the Cypher Shorts Rulebook. All new the equipment, cyphers, artifacts, vehicles, abilities, etc. are sorted into the appropriate compendia.

### Changed
- The CSRD Compendium now requires Cypher System v2.4.0.
- The Cypher System Rulebook has been updated with crossreferences to the new Rulebooks.
- The CSS classes of the editor’s notes has been changed.

### Deprecated
- The Meeple and Scenes compendia will be removed in the next update. They will be moved to a separate Community Module.

## [3.5.1] - 2023-01-12
### Fixed
- The CSRD Rulebook hasn’t been updated with the correct file in v3.5.0. This has been corrected:
  - The CSRD Rulebook now *really* includes some notes with errata, clarifications, addenda, and Foundry VTT usage tips. Those are unintrusively put behind a details tag. This way, the comments are clearly separated from the original SRD content.
  - The CSRD Rulebook now *really* includes lists with linked items for all cyphers, creatures, and NPCs at the appropriate places.

## [3.5.0] - 2023-01-05
### Added
- The CSRD Rulebook now includes some notes with errata, clarifications, addenda, and Foundry VTT usage tips. Those are unintrusively put behind a details tag. This way, the comments are clearly separated from the original SRD content.
- The CSRD Rulebook now includes lists with linked items for all cyphers, creatures, and NPCs at the appropriate places.
- The Technofantasy Ruleset has been expanded by some more appropriate foci and descriptors. There’s also a new custom type: the Leader (based on the Speaker).

### Changed
- The CSRD Compendium now requires v2.1.2 of the Cypher system.
- Added the Cypher System Open License to LICENSE.md.

## [3.4.0] - 2022-12-09
### Added
- Technofantasy Ruleset (journal) to play in your favorite technofantasy setting. Includes three custom types (Blade, Techno-Wizard, and All-Rounder), and a selection of foci and descriptors most suitable for technofantasy settings. Everything is based on material from the CSRD.
- A table with jumping distances has been added to the CSRD Rulebook.
- Pre-made attack skills have been added to the Skill (Expanded) compendium.

### Fixed
- Some typos have been fixed.

## [3.3.1] - 2022-10-31
## Fixed
- The manifest URL should now be working.

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