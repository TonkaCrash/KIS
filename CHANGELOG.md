# 1.26 (July 18th, 2020):
* [Change] Switch to `MiniAVC-V2`.
* [Enhancement] Add a new fun part: Snacks!
* [Enhancement] Add a new fun part: Fallen Kerbonaut. FYI, there is a real life prototype for this part.
* [Enhancement] Add storage lockers parts. They used to be a part of the defunc SEP mod.
* [Enhancement #360] Use fuel type from the config for the EVA fuel canister.
* [Fix #362] Tab Key in Map View crashes the game.
* [Fix #364] KSP 1.10: Carriable items cannot be equipped.

# 1.25 (April 25th, 2020):
* [Change] Stop complaining about KSP minor version change.
* [Change] Update ES-ES localization.

# 1.24 (December 6th, 2019):
* [Change] Add a workaround for #354 to not get GUI freezed.
* [Fix #352] Incorrect calculation of resources on the equipped items.

# 1.23 (October 23rd, 2019):
* [Change] `KSP 1.8` compatibility. __WARNING__: the mod won't work with version lower than `KSP 1.8`!
* [Change] Replace `Editor/partGrabModifiers` setting with `Editor/editorPartGrabAction`.
* [Enhancement] Allow dropping KIS items on the kerbal: [Dragging equipped items](https://youtu.be/udTj7_pO2hc). Thanks to [sleepyquelea](https://github.com/sleepyquelea)!
* [Fix #339] Inflatable habitat parts have unreasonable inventories.
* [Fix #341] AddPodInventories not called for initial crew capacity 0.
* [Fix #348] Volumes of some parts are too high to fit the KIS containers.

# 1.22 (May 30th, 2019):
* [Change] "Breaking ground" DLC support.
* [Change] Don't allow `KIS` to deploy or move the ground experiments.
* [Change] Allow the small cargo to be carried by kerbal.
* [Change] Disable the default remove helmet hotkey `J` as it conflicts with "Breaking ground" DLC.
* [Enhancement] Add medium portable cargo to carry 6 experiments.
* [Fix #333] Robotics part trigger physics when making a hover model.
* [Fix #334] Action icons are blurred.

# 1.21 (May 16th, 2019):
* [Fix #89] Portable containers revert to previous content when dropped. 
* [Fix #328] KIS fails on every new DLC or major patch that changes kerbal models.
* [Fix #330] KIS containers mass and volume physically realistic. __Read the issue description for details!__

# 1.20 (May 3rd, 2019):
* [Fix #326] Text formating in PAW menu.

# 1.19 (May 2nd, 2019):
* [Change] `KSP 1.7.*` compatibility.
* [Change] Update ES-ES localization.
* [Change] Make `CB-1` volume physical (no override) and allow carrying it on the kerbal's back.
* [Fix #305] Allow grab hints menu to be turned off in KIS `settings.cfg`.
* [Fix #311] Container item launchID incorrect at vessel launch.
* [Fix #313] Contained item's dry-mass is incorrect in tooltip. 
* [Fix #314] KIS.Container1 cannot be selected as root part.
* [Fix #315] When the target is too far, KIS says "too heavy".
* [Fix #317] Stock Parts not stacking in 1.6.1 with no other mods.
* [Fix #319] Restock part volumes is wrong when a skinned mesh is used.
* [Fix #320] Some parts refuse to get detached.
* [Fix #321] KIS Inventory and inflatable parts.
* [Fix #323] EVA fuel canister has infinite reserve.
* [Fix #324] Statically attachable parts don't attach.

# 1.18 (February 2nd, 2019):
* [Change] Add an optional (yet) patch file to make the legacy KIS containers physics complient. See file `kis_physical_containers.cfg.txt`.
* [Enhancement] Add French localization.
* [Enhancement] Improve English part descriptions.
* [Enhancement] Add IWC-4500 "Wyvern" part.
* [Fix #297] IMC-15K has wrong part volume.
* [Fix #301] "volumeOverride" is not working.
* [Fix #302] Structurel panel has wrong nodes.
* [Fix #303] Game's crashing on the new parts.

# 1.17 (January 28th, 2019):
* KSP 1.6 support. This mod's version is not compatible with the prior versions of KSP!
* [Enhancement] Add fun English part descriptions.
* [Enhancement] Add Portuguese (Brazil) localization.
* [Enhancement] Improve items&parts debug ability. See `partAlignToolKey` and `itemDebug` in the settings file.
* [Enhancement] Add new containers: `IMiC-1500`, `ImC-3K`, `IMC-22K`, and `IGC-45K`.
* [Enhancement] Big improvement in performance. Many inventories with items in one scene could slow down the game significantly (see #287 & #288).
* [Enhancement #281] Use the stock functionality from the KIS code and properly support custom helmets.
* [Enhancement #289] Take into account the container size when detecting its availability.
* [Fix #160] Cannot deatch broken solar panel.
* [Fix #163] Implement full support of TweakScale mod.
* [Fix #267] Review container mount mass.
* [Fix #273] Support part's variant when dealing with KIS container items.
* [Fix #293] Fun parts in are not equipping.

# 1.16 (October 29th, 2018):
* [Fix #275] No preview meshes shown.

# 1.15 (October 27th, 2018):
* [Change] KSP 1.5.* compatibility.
* [Fix #268] Wrong size detection on the MH expansion parts. READ #273!!!
* [Fix #269] Equip items and remove helmet actions don't work.
* [Fix #270] Command seats must not be allowed to have inventory.
* [Fix #271] In some languages the CCK tags are broken.

# 1.14 (July 18th, 2018):
* [Change] Migrate to KSPDev Utils 0.37.0. A stability fix.

# 1.13 (July 7th, 2018):
* [Change] Migrate to x64 profile. The 32-bit game mode is no more supported!
* [Change] Migrate to KSPDev Utils 0.36.0.
* [Enhancement] Add Italian localization (IT_it).

# 1.12 (May 6th, 2018):
* [Fix #257] Helmet doesn't remove on the female kerbal models.
* [Change] Upgrade to KSPDev Utils v0.33.

# 1.11 (March 26th, 2018):
* [Fix #248] Broken inventory for the new DLC suits.
* [Fix #252] Allow setting type of the inventory via config.
* [Fix #253] Kerbal preview is wrong for the expansion pack suites.
* [Fix #254] Remove helmet doesn't work on the expansion EVA suites.

# 1.10 (March 8th, 2018):
* KSP 1.4 support.
* [Change] Update the pods in the loading screens.
* [Enhancement] Add Espanol localization.

# 1.9 (December 28th, 2017):
* [Enhancement] Add Chinese localization.
* [Fix #235] Items equip state is not persisted.
* [Fix #218] Exception when moving part in the editor.

# 1.8 (December 14th, 2017):
* [Enhancement] Add Spanish localization.
* [Fix #181] Match the part's menu max distance to the inventory grab distance.
* [Fix #230] Equipped items don't destroy on kerbals pack.
* [Fix #233] Mounted parts are improperly aligned to the target.
* [Fix] Correct the localization string IDs that were conflicting with KAS.

# 1.7 (September 17th, 2017):
* [Fix #224] Exception when move&attach a static attach item.
* [Fix #225] Impossible to move items between the inventories.

# 1.6 (September 14th, 2017):
* [Enhancement] Improve the attach nodes of the KIS items (including the fun parts) to reduce the physics effects on drop.
* [Enhancement] Implement localization support.
* [Enhancement] Full localization for the Russian language ("ru" locale).
* [Fix #219] Inventory GUI spontaneously closes in the editor.
* [Fix #130] Crew transfer leaves ghost pod's inventory open.
* [Fix #220] Equipped parts trigger physics.
* [Fix #222] The equipped screwdriver can be attached to a part.
* [FIx #217] Align velocities on the dropped part.
* [FIx #207] Improve docked nodes detection in ReDock mode.

# 1.5.0 (May 25th, 2017)
* [Change] `OnKISAction` now accepts a dictionary parameter instead of the deprecated `BaseEventData`.
* KSP 1.3 support.

# 1.4.4 (May 1st, 2017)
* [Enhancement] Equip kerbal models on the start screen with sample KIS items. Can be adjusted/disabled via `settings.cfg`.
* [Enhancement] Allow the Experiment Storage Unit to be carried on a kerbal's back (Wyzard256).
* [Fix] Proper paths in the fun parts.

# 1.4.3 (February 22nd, 2017)
* [Fix #107] Moving a docked port causes physics effects.
* [Fix #158] NRE when transferring crew into a pod part without KIS inventories.
* [Fix #199] Wrong kerbal class in inventory window info when in command seat.
* [Fix #203] Some physicsless part trigger physics effect on move&attach.
* [Fix #206] Using of re-dock feature blocks "detach" hotkey.
* [Enhancement #200] Set decouple momentum on Cargo Mount to zero.
* [Enhancement #202] Make pod seat's inventory more clear.
* [Enhancement #204] Allow stacking KIS tools.

# 1.4.2 (January 28th, 2017)
* [Fix #197] Part is created on the kerbal instead of the target vessel.

# 1.4.1 (January 16th, 2017)
* [Fix #183] Equipped parts are not restored on scene load.
* [Fix #186] NRE when using container in the editor.
* [Fix #187] EVA equipped parts behave bad when sitting in the command seat.
* [Fix #189] Handle ESC key.
* [Fix #194] Remove helmet state is not persisted.
* [Fix #195] Eqipped parts collide with kerbal model.
* [Enhancement #184] Use KSP 1.2 feature to add inventories to kerbals.
* [Enhancement #191] Add bottom attachment node to container mount.
* [Enhancement #192] Disallow ILC-18k on container mount.
* [Enhancement #193] Add quadrant attachment nodes to stock 2x2 panel.

# 1.4.0 (December 4rd, 2016)
* [Enhancement] Add default items for the first seat into a lesser slots.
* [Fix #178] Full mass used for empty parts for purpose of removing from containers.
* [Fix #179] Put all KIS items into a real KSP categories.
* [Fix #180] Persist equipped state in EVA inventories.
* [Change] ModuleManager is now required mod.
* [Change] CommunityCategoryKit is now required mod.

# 1.3.1 (November 23rd, 2016)
* [Change] Stop using KSPDev obsolete logging methods.
* [Fix #175] EVA canister stopped working.
* [Fix #129] On initial load KIS_UISoundPlayer throws errors.
* [Fix #176] Use new KSP 1.2 categories to sort KIS parts.
* [Fix #152] Inventory reacts to flag writing.
* [Fix #157] MKS/OKS: NRE when adding MK-V Comm-Lab part.
* [Fix #135] NRE detaching and reattaching part with FAR.
* [Change] Exclude fun parts from the release.

# 1.3.0 (October 12th, 2016)
* [Enhancement] KSP 1.2 support

# 1.2.12 (June 21st, 2016)
* [Fix] #109: Sandbox mode = no repairskill for non-badass kerbals.
* [Fix] #161: KSP 1.1.3: Missing method exception.

# 1.2.11 (June 10th, 2016)
* [Fix] #138: NRE when switching to launch.
* [Fix] #151: NRE in editor when using Deadly Reenter mod.
* [Fix] #154: Items in free seats's inventory are not cleared and counted to the vessel mass.

# 1.2.10 (23 May 2016)
For proper part's volume calculation Module Manager is required. Though, without it the mod will still work.

* [Fix] #117: Fix duplication of the default items on flight revert.
* [Fix] #140: A part get created on drag in the editor.
* [Change] Always calculate part volume from its prefab. It's now consistent but may be not optimal in some cases. E.g. deployable parts that are deployed by default (in the mesh state) will take more space than they used to be. It may result in awkward behavior of containers that were loaded prior to the update.
* [Change] Add a ModuleManager patch to override stock drills volume since in prefab these parts are deployed and take too much space.
* [Fix] #141: Stop directly modifying inventory part mass.
* [Enhancement] #148: Dropped parts get weird names.
* [Fix] #147: Some parts don't give usable drag models from prefab.
* [Fix] #145: Carriable items show as "carried" in the inventory.
* [Fix] #142: Settings are always read from file.
* [Fix] #137: Volume of Drill-O-Matic calculated incorrectly.

# 1.2.9 (3 May 2016)
* [Change] Temporarily set surface attach node as the most preferable for default. It's a workaround until #134 is fixed.
* [Fix] #131: Kerbals can't pull items from Inventories.
* [Fix] #133: Concrete block doesn't attach.

# 1.2.8 (2 May 2016)
* [Change] Compatibility change for KSP 1.1.2.
* [Change] When attaching a part with stack nodes by default prefer "bottom" and "top" attach nodes as they are most used ones.
* [Change] Turn allowPartAttach and allowStaticAttach fields of KISItem into enums. Integers are still accepted but in the new parts using of enum names is encouraged.
* [Change] Temporarily increase breaking force of equipped items by x10 (up to 50). Old settings of 5 is too weak for such applications as eva chutes. Also see bug #128.
* [Enhancement] Show error message when "X" is pressed and no item is equipped.
* [Enhancement] #117: Auto add common items to the seats.
* [Fix] #116: Mass limit is not checked when grabbing from inventory.
* [Fix] #118: Detach of static attached part results in NPE.
* [Fix] #119: Adding an item into inventory in the editor shows KSP error in the logs.
* [Fix] #121: In node attach mode the connection points markers get overlapped by the part's mesh.
* [Fix] #122: For some parts attach point is wrongly detected.
* [Fix] #124: Parts with allowPartAttach = 1 still require a tool.

# 1.2.7 (21 April 2016)
* [Change] KSP 1.1 supported!
* [Change] Increase static attach strength on ground base to prevent joint breakage.
* [Enhancement] Add new setting in the config to specify key modifiers that
  activate dragging in editor category list. By default it's set to `None` which
  preserves same behavior as in 1.0.5.
* [Enhancement] Improved search tags and descriptions in parts.
* [Fix] Parts got replicated and attachment didn't work when surface attaching parts onto radial adapter.
* [Fix] React on joint break on static attached items.
* [Fix] Match rendering queue of KIS pointer to the part's highlight renderers to prevent overlapping issue.
* [Fix] Restore highlighting of the hovered part when deselecting a hierarchy.
* [Fix] Fix bottom attach node on ground base to make it more stable and prevent explosions on physics start.

# 1.2.6 (7 April 2016)
This version does NOT support KSP 1.1 yet! Version 1.2.7 will.
* [Fix]: #108: Parts with no attach nodes cannot be static attached.
* [Change]: Some cleanup to make code more compatible with pre-release of KSP 1.1.

# 1.2.5 (22 February 2016)
* [Feature] #101: Allow configuring EVA inventory hotkeys via a config file.
* [Fix] #103: Part (not seat) inventory overwritten by crew inventory when transferring crew into it.
* [Fix] #89: Portable containers revert to previous content when dropped. For now only restrict using of such inventories to not loose items. Which promotes this bug to enchancement.

# 1.2.4 (17 February 2016)
* [Feature] #96: Allow move/attach a group of parts. When grab mode is selected the whole hierarchy is highlited.
* [Feature]: New mode "Re-dock" (shortcut: "y"). Allows moving vessels docked to the station. No need to snipe the right part to deatch, the right docking port is found automatically. The port allowed for re-docking are highlighed with green color.
* [Enhancement] Added semi-black background when showing cursor status and hint text to improve visibility in light scenes.
* [Enhancement] Detect and fix wrong assemblies that could have created due to a bug in the KSP editor.
* [Enhancement] Don't allow (un)equipping when dragging/moving a part.
* [Enhancement] When stack attaching only consider nodes that don't allow collisions.
* [Fix] #87: Correctly handle "revert flight" action, and stop adding multiple callbacks that slow down editor UI.
* [Fix] #97: Accept names with dots when overriding part settings in config. E.g. "mumech_MJ2_AR202" is correctly tarnslated into "mumech.MJ2.AR202".
* [Fix] Don't equip items when loading non-eva kerbal. When vessel had multiple non-engineer kerbals, and there is one with an equipped screwdriwer an error "cannot quip" was showing on load.

# 1.2.3 (11 November 2015)
* Compatibility fix for KSP 1.0.5

# 1.2.2 (13 August 2015)
* [Fix] Fixed kerbal items not transfering to pod without internal model
* [Fix] Fixed missing command seat icon (thx to mongoose)
* [Fix] Fixed node attach not working for some radial part
* [Fix] Prevent playing static attach sound after load/warp 
* [Fix] Removed old ILC-18k container .mbm textures
* [Fix] Converted ISC-6K container textures to DDS
* [Fix] Fixed minor typo in sound error message (thx to Amorymeltzer)

# 1.2.1 (29 July 2015)
* [Enhancement] Added key (B/N) to move up or down a part in drop mode 
* [Enhancement] Added a dedicated key to put/remove helmet (J)
* [Enhancement] Added new stackable modules
* [Enhancement] Added max sound distance parameter for ModuleKISItemSoundPlayer 
* [Enhancement] Added new parameters in moduleKISItem : useExternalPartAttach &
useExternalStaticAttach (for KAS or others mods)
* [Change] Modified the organization of the text keys under cursor
* [Fix] Fixed editor part dragging
* [Fix] Removed some unused debug lines
* [Fix] Fixed eva speed not returning to the default value after moving a carried container to an inventory
* [Fix] Kerbal headlamp is disabled when helmet is removed 
* [Fix] Prevent helmet sound to play if it cannnot be removed

# 1.2.0 (11 July 2015)
* [New Part] ISC-6K inline container (6 000L)
* [Enhancement] Added a dedicated key to attach/detach (H)
* [Enhancement] Part can be detached from parent without grabbing
* [Enhancement] Explosives can be attached without a tool
* [Enhancement] Added a GUI to set the timer and radius of explosives
* [Enhancement] Added different color to attach and drop
* [Enhancement] Added an dedicated icon for detaching
* [Enhancement] Allow detaching & grabbing of part with one parent or children
* [Enhancement] Added colors to the target part and his parent on detach
* [Enhancement] Removed attach mass restriction for the wrench
* [Enhancement] Added a ModuleKISItem parameter : allowStaticAttach (0:false / 1:true / 2:Attach tool needed)
* [Enhancement] Added a ModuleKISItem parameter : allowPartAttach (0:false / 1:true / 2:Attach tool needed)
* [Enhancement] Added a ModuleKISItemAttachTool & ModuleKISPickup parameter to enable/disable part & static attach
* [Change] IMC-250 container renamed ILC-18k, max volume reduced from 22000 to 18000
* [Change] Moved ModuleKISPartStatic to ModuleKISItem
* [Change] Changed some part description
* [Change] Increased explosives maxTemp parameter
* [Change] Updated guide to 1.2
* [Fix] Compatibility fix for KSP 1.0.4
* [Fix] Fixed crash on x64 linux
* [Fix] Fixed wrong position of part attached from inventory 
* [Fix] Prevent part "cloning" when removing content of a carried container before
dropping it
* [Fix] Fix crash when dropping a part from a carried container 

# 1.1.5 (31 May, 2015)
* [Enhancement] Disable jetpack mouse input while dragging 
* [Enhancement] Converted parts textures to DDS 
* [Enhancement] AVC is now used for version check
* [Enhancement] Added a KAS version dependancy check 
* [Enhancement] Added more stackable module (KASModuleHarpoon, ModuleRecycleablePart, CollisionFX)
* [Fix] launchID is now correctly set for stored parts
* [Fix] Prevent removing the launch vessel flag of stored parts
* [Fix] Stored parts must now be recognized by contracts
* [Fix] Fix static part not attaching when dragged from an inventory
* [Fix] Prevent vessel switching while dragging an item 
* [Fix] Engineer report take into account the mass update 
* [Fix] OnKISAction method use BaseEventData (prevent KAS crash if KIS is missing)
* [Fix] Fix two typos in the user manual 
* [Fix] Fix wording for removing helmets. (thanks to iPeer)

# 1.1.4 (14 May, 2015)
* [Fix] fix delayed ship explosion after attaching parts from inventory in deep space 

# 1.1.3 (14 May, 2015)
* [Fix] fix explosion after moving/attaching a part (hopefully)
* [Fix] Prevent equipped part to explode after loading (when using equipmode = part)
* [Fix] Prevent item to be carried even if no slot is available
* [Fix] Explosive now show up in the left hand according to the equip slot
* [Fix] Prevent unequipping when dragging an item on another
* [Fix] Eva propellant will now remove resource from the equipped part (when using equipmode = part)
* [Change] Guide and wrench item moved to engineering101 tech node 
* [Change] Created a SendKISMessage method (to communicate with KAS or other mods)

# 1.1.2 (8 May, 2015)
* Compatibility fix for KSP 1.0.2
* [Feature] Add "mountedPartNode" parameter in module "ModuleKISPartMount" to set the part node used on mount
* [Feature] Allow mount to be set on a moving attach node (KAS compatibility)
* [Feature] Send messages on part drop/attach (KAS compatibility)
* [Fix] Fix velocity reset on part creation in space
* [Fix] Prevent part node to be changed on mount
* [Fix] Prevent KIS dll reference error after recompile
* [Fix] Ingame user guide updated to 1.1
* [Fix] Some spelling fixes
* [Change] Move KIS static item module to part module
* [Change] Allow carried container to be used 

# 1.1.1 (1 May, 2015)
* [Fix] Fixed (again) wrong mass calculation for part with resources
* [Fix] Fixed "Escape" not correctly spelled

# 1.1.0 (30 April, 2015)
* KSP 1.0 Compatibility
* [New Part] 2.5m inline container (20 000L)
* [New Part] Ground base (similar to KAS Pylon)
* [Feature] Part snapping on stack nodes (electric screwdriver only)
* [Feature] Containers snapping on mount (removed "item drag to mount" behaviour)
* [Feature] Small containers can now be carried on kerbal's back (but kerbal speed is limited on ground)
* [Feature] Allow part from editor scene to be dragged to inventory (for tweaking them before storing them)
* [Feature] Added multiple node support for PartMount module  
* [Feature] Added TweakScale compatibility
* [Feature] Added ability to name containers
* [Feature] Added a button in the kerbal inventory to put/remove helmet
* [Feature] Added ability to set equip to "model"(default), "part" or "physic" in ModuleKISItem
* [Feature] New item module to tweak some kerbal parameters when item is equipped (for modding)
* [Feature] Current attach node is now displayed on the cursor
* [Feature] Show science data of stored items
* [Feature] Settings.cfg file is now loaded as a confignode (allow module manager to add partModules to the Stackable list)
* [Feature] Show content resources, cost, mass and science data for stored containers
* [Change] Disabled surface attach for stack part nodes
* [Change] Disabled surface attach for part not allowing it
* [Change] Increased default grab range to 3 meters
* [Change] Part cost, mass and r&d updated for KSP 1.0
* [Change] Reduced the number of slots of the small container
* [Fix] "Open inventory" context menu max distance now use the grab distance from settings.cfg
* [Fix] Disabled editor set quantity item context menu when part is not stackable
* [Fix] Fixed a crash when trying to store a command pod from the editor
* [Fix] Fixed item icon not returning to default rotation 
* [Fix] Prevent a crash if an item is added in the same slot on loading 
* [Fix] Re-arrange inventories when size is changed
* [Fix] Removed a double when changing attach node
* [Fix] Prevent storing a container in itself
* [Fix] Prevent attaching a part on itself
* [Fix] Fixed incorrect checking of volume available when stacking in the same inventory

# 1.0.2 (5 April, 2015)
* Fix wrong mass calculation for part with resources 

# 1.0.1 (31 March, 2015)
* Change volume unit from M3 to L
* Check kerbal skill instead of trait name for tools
* Added default kerbal mass parameter in settings.cfg
* Disable drag for greyed parts in the editor to prevent storing them without bought them from research in hard mode
* Add decimals to maxVolume for the inventory module tooltip
* Prevent a part to be mounted on itself
* Fix grab not working in some specific situations
* Fix crash when dragging a container from a mount to another mount
* Fix crash when attaching a docking node
* Fix container mass calculation
* Fix inventory click-through not working correctly
* Fix framerate drops while hovering inventory in flight
* Fix debug menu not working
* Fix exception thrown on first time entering VAB
* Fix exception thrown after loading
* Fix exception thrown when using release on empty mount

# 1.0.0 (14 March, 2015)
* Initial release
