---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Drop Tanks III (DTIII)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Drop Tanks III (DTIII)

[Home](./index.md)

Stockalike curved wraparound DropTanksIII with an integrated decoupler for Kerbal Space Program

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KerbalHacks` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KerbalHacks/DropTanksIII`
* Extract the package's `KerbalHacks` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KerbalHacks` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KerbalHacks/DropTanksIII`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KerbalHacks/DropTanksIII`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KerbalHacks/DropTanksIII`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KerbalHacks]
      + [KerbalHacksLtd]
        ...
      + [DropTanksIII]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
          ManualInstallation.htm
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-NC-SA-4.0.txt
        * changelog.md
        * DropTanksIII.version
        * readme.htm
        ...
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Kerbal Hacks Ltd. (KHL)][KHL]

[KHL]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-*/ "Kerbal Hacks Ltd. (KH/L)"