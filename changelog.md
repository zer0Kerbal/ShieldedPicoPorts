# Changelog  
  
| modName    | Shielded PicoPorts (SPP)                                           |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | zer0Kerbal                                                        |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/192187-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/ShieldedPicoPort)       |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/ShieldedPicoPort)     |
| spacedock  | (https://spacedock.info/mod/2245)                                 |
| ckan       | ShieldedPicoPort                                                  |

## Version 1.0.2.0-release -  `<EDITION>` edition

* 13 Jul 2022
* Released for KSP 1.12.3

### Status

Squad/Parts/Utility/dockingPortShielded/model
 Squad/Parts/Utility/dockingPortShielded/MODELdockingPortShielded

### Compatibility

* Update
  * [ConnectedLivingSpace.cfg] v1.2.0.0
    * simplifyed @PART[ShieldedPicoPort?]
    * added ConnectedLivingSpace to :NEEDS
  * [ReStock.cfg] v1.1.1.0
    * updated :NEEDS
    * added :AFTER[ReStock]
  * [ShieldedPicoPorts.restockwhitelist] v1.0.1.1
    * renamed file
  * [StackInlineLights.cfg] v1.1.0.
    * simplifyed @PART[ShieldedPicoPort?]
    * :FOR[StackInlineLights] to :FOR[ShieldedPicoPorts]
    * Rename
      * from [StackInlineLighting.cfg] to [StackInlineLights.cfg]
    * needs to be localized after SIL/SILP is localized
  * [TweakScale.cfg] v1.1.0.0
    * simplifyed @PART[ShieldedPicoPort?]

### Config

* [ShieldedPicoPorts.cfg] v1.0.0.0
  * purpose is to simplify the translation process by limiting the number of strings to translate
  * scraps/mines as much as possible from Squad's [dictionary.cfg]
* Create a new file called [ghostparts.cfg] v1.3.0.0 in the [Config] folder.
  * will be going away in the future.

### Parts

* :FOR[ShieldedPicoPort] to :FOR[ShieldedPicoPort]

* Rename
  * from [ShieldedPicoPortBasic.cfg] to [ShieldedPicoPortB.cfg] v2.0.0.0
  * from [PicoPortShieldedF.cfg] to [ShieldedPicoPortF.cfg] v2.0.0.0
  * from [PicoPortShieldedM.cfg] to [ShieldedPicoPortM.cfg] v2.0.0.0
  * from [PicoPortShieldedP.cfg] to [ShieldedPicoPortP.cfg] v2.0.0.0

### docs/

* Add
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
  * [404.md] v1.0.3.1
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [Part-Catelog.md] v1.1.4.0
  * [Why.md] v1.1.0.0
  * [_config.yml]
* closes #14 - docs/

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Updates #15 - Localization Master
* Closes #16 - Localization - English <en-us.cfg>

* [ShieldedPicoPort.version]
  * remove [KSP_VERSION_MIN]

  * closes #33 - Part Localization
  * closes #8 - [Bug 🐞]: Need Better titles/descriptions
  * closes #9 - Update License

* thorough linting of configs
* minor corrections to readme and changelog
* backend automations
* Added
  * Inflatable PicoPort Basic
  * all parts to ConnectedLivingSpaces and TweakScale patches

### Status

* Issues
  * closes #10 - Shielded PicoPort 1.0.2.0-release `<En Garde!>`
  * closes #11 - 1.0.2.0 Verify Legal Mumbo Jumbo
  * closes #12 - 1.0.2.0 Update Documentation
  * closes #13 - 1.0.2.0 Update Social Media
* Pull Requests
  * #3 - pull master changes - contributed by zer0Kerbal
  * #4 - add images :imp: - contributed by zer0Kerbal
  * #5 - [ImgBot] Optimize images - contributed by imgbot[bot]

---

## Version 1.0.1.1-release -  `<>>-- Reminiaturized - for KSP 1.8.1 --<<` edition

* 07 Mar 2020
* Released for KSP 1.12.3

* #1 - Couple of fixes - contributed by AmberCronin
* #2 - Fix version file problems - contributed by HebaruSan

---

## Version 1.0.1.0-release -  `<>>-- Reminiaturized --<<>` edition

* corrected changelog
* added localization code
* removed extraneous scale =
* removed localization code since it just doesn't work this way. :(
* updated to new KERBALCHANGELOG format!
* added three new models!
  * Basic
  * Now has Female
  * Now has Male
  * Now has and Plus

---

## Version 1.0.0.2-release -  `<Needy little things>` edition

* [D][BUG 1.0.0.2a] part isn't loading
* [D][BUG 1.0.0.2a] change in folder structure was not reflected in patches :NEEDS statement which in turn caused th*not load.
* remove errors in Changelog.cfg

---

## Version 1.0.0.1-release -  `<ReStocked and Flush>` edition

* added PicoPortShielded.restockwhitelist
* added ReStock patch (so PicoPortShielded will show up with ReStock installed)
* turned off PicoPortShielded.restockwhitelist
* adjusted placement of model so will no longer sink into part attached to
* moved TweakScale and ConnectedLivingSpaces patches into separate files

---

## Version 1.0.0.0-release -  `<Phalanx those Ports!>` edition

* >>-- creation by zer0Kerbal --<<

---

<!-- CC BY-NC-ND 3.0 Unported zer0Kerbal -->
