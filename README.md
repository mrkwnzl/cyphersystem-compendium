# Cypher System Compendium

![GitHub Latest Release](https://img.shields.io/github/release/mrkwnzl/cyphersystem-compendium?style=flat-square)
![GitHub Downloads Latest](https://img.shields.io/github/downloads/mrkwnzl/cyphersystem-compendium/latest/total?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/mrkwnzl/cyphersystem-compendium/total?style=flat-square)
![License](https://img.shields.io/github/license/mrkwnzl/cyphersystem-compendium?style=flat-square)

This is a module for use in conjunction with the [Cypher System game system for Foundry VTT](https://foundryvtt.com/packages/cyphersystem/). The Cypher System Compendium expands the Cypher System game system with compendia with pre-made items, actors, and scenes. The following compendia are included:

- **Abilities**, including the Pool point cost.
- **Ammo**.
- **Armor**, sorted by genre and including the Armor value and Speed point cost.
- **Artifacts**, sorted by genre and including the levels and depletion of the artifcats.
- **Cyphers**, sorted by genre, including the levels of the cyphers.
- **Equipment**, sorted by genre.
- **Meeples**, generic NPC tokens, in five colors for levels 1 through 10 with the corresponding default values, which you can use if you quickly need more NPCs on your map.
- **Scenes** with home scenes that can be used in theater-of-the-mind style games. There are different areas to sort your tokens on the scene.
- **Weapons**, sorted by genre and including damage, weapon type, and keywords for properties (such as *rapid-fire weapon*).

No descriptive text or rules for the items is included, only game terms and associated numerical values. All items from the MCG published books come with page references, which turn into clickable links if the corresponding PDF is created as a journal entry within Foundry using [PDFoundry](https://foundryvtt.com/packages/pdfoundry/).

Note that the compendia, especially the one with abilities, contain a large number of items. It’s not advised to import everything into a world, as that will hit performance and might even lead to crashes of Foundry. Only import what you really need. For most cases, no import is needed at all.

## Setting up Clickable References in Items

There’s no setup needed to use the module, but if you want the references to be clickable links, make sure that [PDFoundry](https://foundryvtt.com/packages/pdfoundry/) is installed and enabled in the module settings. Then, create the PDFs as journal entries. Two things are important: 

1. Make sure that you name the journal entry *exactly* as shown in the table below. The title is case sensitive.

2. Almost all MCG PDFs need a page offset of 2. See the table for details:

| Title                  | Page Offset |
| ---------------------- | :---------: |
| Claim the Sky          | 2           |
| Cypher System Rulebook | 2           |
| First Responders       | 2           |
| Godforsaken            | 2           |
| Ptolus                 | 2           |
| Stay Alive             | 2           |
| The Banewarrens        | 0           |
| The Origin             | 2           |
| The Stars Are Fire     | 2           |
| We Are All Mad Here    | 2           |

## Customizing Scenes

The scenes are all ready to go, but at the same time, can’t be customized. The one exception is `Home Scene [Template]`, which has the overlay set up as a tile, so that you can use your own custom backgrounds. For this to work, your background image must have a size of 4000×2250 px.

## Support and Community

The [Cypher FVTT Dev Discord](https://discord.gg/C5zGgtyhwa) is where the development of the system and this module is coordinated and their futures discussed, but anyone is welcome to join and share best practices, ask questions on how to use the system, and share self-created resources for your games.

You can also reach me on the [official Foundry Discord](https://discord.gg/foundryvtt) or via Discord DM: @mrkwnzl#7407.

## Buy Me A Coffee

If the Cypher System for Foundry VTT makes your games more accessible and fun, I’m grateful for a coffee:

<a href="https://www.buymeacoffee.com/mrkwnzl" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" height="40"></a>

## Licenses

Cypher System game terms and any material owned by Monte Cook Games is used in accordance with the Fan Use Policy.

Images present under the `icons/` directory are distributed under the CC BY 3.0 license.

The software component of this system is distributed under the MIT license.

## Fan Use Policy

*The Monte Cook Games logo, Numenera, the Cypher System, No Thank You, Evil!, Invisible Sun, and their respective logos are are trademarks of Monte Cook Games, LLC in the U.S.A. and other countries. All Monte Cook Games characters and character names, and the distinctive likenesses thereof, are trademarks of Monte Cook Games, LLC. Content on this site or associated files derived from Monte Cook Games publications is © 2013-2021 Monte Cook Games, LLC. Monte Cook Games permits web sites and similar fan-created publications for their games, subject to the policy given at [https://www.montecookgames.com/fan-use-policy/](). The contents of this site are for personal, non-commercial use only. Monte Cook Games is not responsible for this site or any of the content, that did not originate directly from Monte Cook Games, on or in it. Use of Monte Cook Games’s trademarks and copyrighted materials anywhere on this site and its associated files should not be construed as a challenge to those trademarks or copyrights. Materials on this site may not be reproduced or distributed except with the permission of the site owner and in compliance with Monte Cook Games policy given at [https://www.montecookgames.com/fan-use-policy/]().*

## Credits

### Graphics

All graphics under `icons/` are taken from [game-icons.net](https://game-icons.net).

- [Delapouite](https://delapouite.com/)
- [Lorc](https://lorcblog.blogspot.com/)
- [sbed](http://opengameart.org/content/95-game-icons)
- [Skoll](https://game-icons.net/)

Images under `img/scenes/` are taken from [Pixabay](https://pixabay.com). 

- [12019](https://pixabay.com/users/12019-12019/)
- [AlexAntropov86](https://pixabay.com/users/alexantropov86-2691829/)
- [ArtTower](https://pixabay.com/users/arttower-5337/)
- [cocoparisienne](https://pixabay.com/users/cocoparisienne-127419/)
- [jplenio](https://pixabay.com/users/jplenio-7645255/)
- [kinkate](https://pixabay.com/users/kinkate-4384506/)
- [Lenalensen](https://pixabay.com/users/lenalensen-2819406/)
- [MartinStr](https://pixabay.com/users/martinstr-108372/)
- [OpenClipart-Vectors](https://pixabay.com/users/openclipart-vectors-30363/)
- [Pexels](https://pixabay.com/users/pexels-2286921/)
- [prettysleepy1](https://pixabay.com/users/prettysleepy1-2855492/)
- [Schmid-Reportagen](https://pixabay.com/users/schmid-reportagen-646138/)

`img/overlays/smaug18_home-scene_overlay.png` by smaug18#2066.
