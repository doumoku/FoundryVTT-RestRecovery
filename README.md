# Rest Recovery 5e

![Latest Release Download Count](https://img.shields.io/github/downloads/fantasycalendar/FoundryVTT-RestRecovery/latest/module.zip?color=2b82fc&label=DOWNLOADS&style=for-the-badge) [![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Frest-recovery&colorB=006400&style=for-the-badge)](https://forge-vtt.com/bazaar#package=rest-recovery) ![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fgithub.com%2Ffantasycalendar%2FFoundryVTT-RestRecovery%2Freleases%2Flatest%2Fdownload%2Fmodule.json&label=Foundry%20Version&query=$.compatibility.verified&colorB=orange&style=for-the-badge) ![Latest Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fgithub.com%2Ffantasycalendar%2FFoundryVTT-RestRecovery%2Freleases%2Flatest%2Fdownload%2Fmodule.json&label=Latest%20Release&prefix=v&query=$.version&colorB=red&style=for-the-badge)

---

<img src="https://app.fantasy-calendar.com/resources/computerworks-logo-full.png" alt="Fantasy Computerworks Logo" style="width:250px;"/>

A module made by [Fantasy Computerworks](http://fantasycomputer.works/). (Now maintained by Michael).

Other works by them:

- [Fantasy Calendar](https://app.fantasy-calendar.com) - The best calendar creator and management app on the internet
- [Sequencer](https://foundryvtt.com/packages/sequencer) - Wow your players by playing visual effects on the canvas
- [Item Piles](https://foundryvtt.com/packages/item-piles) - Drag & drop items into the scene to drop item piles that you can then easily pick up
- [Tagger](https://foundryvtt.com/packages/tagger) - Tag objects in the scene and retrieve them with a powerful API
- [Token Ease](https://foundryvtt.com/packages/token-ease) - Make your tokens _feel good_ to move around on the board

Like what they've done? Buy them a coffee!

<a href='https://ko-fi.com/H2H2LCCQ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

Like what _I've_ done? Buy me a coffee too!

<a href='https://ko-fi.com/T6T8XKCII' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

---

# What is Rest Recovery?

This module is a wholesale package that covers any and all mechanics relating to long and short rests, including (but not limited to);

* Class features, such as regaining spell slots through the Wizard's Arcane Recovery and automatic handling of Bard's Song of Rest
* HP Regaining through the Chef feat, and handling of the Tough feat and magic items such as the Periapt of Wound Closure
* Fully featured long rest settings with a multitude of **completely optional** features:
  * Rolling hit dice instead of regaining hit points
  * Partial recovery of spell slots, class features, and/or resources
  * Exhaustion automation
  * Food & water handling, tracking the sated status and starvation over time

The module continues to grow, and will expand further and further.

# Installation
Use this manifest URL to install the module:

`https://github.com/fantasycalendar/FoundryVTT-RestRecovery/releases/latest/download/module.json`

# Full list of features & documentation:

## You can read more about the module on the [wiki](https://github.com/fantasycalendar/FoundryVTT-RestRecovery/wiki).

![Image of the Rest Recovery 5e long rest settings](docs/rest-rules.png)


# Changelog

You can find the [changelog here](changelog.md).


# Contributing

In order to contribute to the module, you will need to do the follwing:

1. Pull this repository and either place it in your Foundry's module folder, or symlink it to that location - remember that the module folder's name needs to be `rest-recovery`
2. Run `npm install` within the repository
3. Run `npm run build`
4. The module is now ready to be used, if you want to develop in real time, you can run `npm run dev` to launch a watcher that will refresh Foundry if it detects changes in the code. This will only be done on the same IP address as your Foundry client, but on port `29999`
