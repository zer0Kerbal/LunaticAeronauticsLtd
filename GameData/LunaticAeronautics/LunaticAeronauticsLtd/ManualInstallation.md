---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Lunatic Aeronautics Ltd (LA/L)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Lunatic Aeronautics Ltd (LA/L)

[Home](./index.md)

> And an other new release from your Lunatic scientists:
>
> Theeeee Rover gravity manipulator!
>
> A module to manipulate the gravity affecting your rover
>
> You can choose which planet or moon settings you want to apply, turn it on and flyyyyyyyyyy.
>
> Sadly our scientist were not able to solve the problem of conflicting with engine electronics.

* Lunatic Aeronautics
  * [Lunatic Aeronautics Ltd (LA/L)][LAL]
  * [Lunatic Aeronautics Anti Grav Room (LAAGR)][LAAGR]
  * [Lunatic Aeronautics K-Mas (KMAS)][KMAS]
  * [Lunatic Aeronautics Ltd (LA/L)][LAL]

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `LunaticAeronautics` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/LunaticAeronautics/LunaticAeronauticsLtd`
* Extract the package's `LunaticAeronautics` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/LunaticAeronautics` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/LunaticAeronautics/LunaticAeronauticsLtd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/LunaticAeronautics/LunaticAeronauticsLtd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/LunaticAeronautics/GameData/LunaticAeronauticsLtd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [LunaticAeronautics]
      + [LunaticAeronauticsLtd]
        + [Agencies]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Compatibility]
          ...
        * #.#.#.#.htm
        * changelog.md
        * CC-BY-NC-SA-4.0.txt
        * readme.htm
        * LunaticAeronauticsLtd.version
        ...
    ...
  * KSP.log
  ...
```

### Dependencies

* none

[LAL]: https://forum.kerbalspaceprogram.com/index.php?/topic/208613-*/ "Lunatic Aeronautics Ltd (LA/L)"
[KMAS]: https://github.com/zer0Kerbal/KMAS "Lunatic Aeronautics K-MAS"
[RAGS]: https://forum.kerbalspaceprogram.com/index.php?/topic/208483-*/ "Rover Anti Gravity System"
[LAAGR]: https://forum.kerbalspaceprogram.com/index.php?/topic/208502-*/  "Anti Grav Room"
