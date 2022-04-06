# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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