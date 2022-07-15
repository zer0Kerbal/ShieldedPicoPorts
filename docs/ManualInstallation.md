---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Shielded PicoPorts (SPP)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Shielded PicoPorts (SPP)

[Home](./index.md)

Adds shielded PicoPorts to Kerbal Space Program. Requires ***PicoPorts*** part addon.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KGEx` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KGEx/ShieldedPicoPorts`
* Extract the package's `KGEx/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KGEx` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/ShieldedPicoPorts`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KGEx/ShieldedPicoPorts`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KGEx/ShieldedPicoPorts`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KGEx]
      + [ShieldedPicoPorts]
        + [Compatibility]
          ...
        + [Localization]
          ...
        + [Configs]
          ...
        * #.#.#.#.htm
        * changelog.md
        * CC-BY-NC-SA-4.0.txt
        * readme.htm
        * ShieldedPicoPorts.version
      ...
    ...
    * [Module Manager][mm] or [Module Manager /L][mml]
  * KSP.log
  ...
```

### Dependencies

* [PicoPort][pp]
* *either*
  * [Module Manager][mm]
  * [Module Manager /L][mml]

[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
[pp]: https://forum.kerbalspaceprogram.com/index.php?/topic/190319-*/ "PicoPort"
