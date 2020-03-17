*********************************
Coatl Aerospace ProbesPlus! BETA
*********************************

============
Known Issues:
============
- KSP may throw texture errors. This seems to be be due to my heavy use of texture swapping modules. As far as I know, texture are loading fine despite the error  
- Reloading the database from the cheat/debug menu may cause some parts and vessel using them to fail to load. I cannot figure out why. Restarting KSP is the safest way to re-load the assets
- The Huygens heatshield, aeroshell and the Surveyor SRM are better off jettisoned from the right-click menu, rather than staging it. I will continue to test and hopefully solve 

Please note that the mod is still in development and there will be constant changes and updates. If you encounter any issues, please report them on the Github page or the forums!

https://github.com/raveloda/Coatl-Aerospace
https://forum.kerbalspaceprogram.com/index.php?/topic/131145-wip-coatl-aerospace-probesplus-dev-thread-v016-beta-282018-13141/

============
Changelog:
============
Beta 0.17

New Parts:  
  
* 'Barca' Parts (Bus), inspired by SSL-1300 satellite bus  
  
==Mariner Parts==  
* 'Argo Mk2' Parts (Bus, Solar panels, HGA, Magnetometer mast, camera), inspired by Mariner 4  
* 'Argo Mk3' Parts (Bus, Solar panels, HGA), inspired by Mariner 5  
* 'Argo Mk4' Parts (Bus, Solar panels, HGA, mast, imaging platform), inspired by Mariner 6 and 7  
  
Updates/Fixes:

* Tweaked for KSP version 1.9
* Added PlumeParty particles FX  
* Moved the original Mariner-style solar panels up to 'Electrics' in the tech tree  
* Decreased the old Mariner panel's solar vane reaction wheel power  
* Added new version of the CA-MV04 MP engine with a 'Control from here' point  
* Tweaked ScienceDef files  
* Reduced 'Barquetta' monopropellant capacity to 7  
* Reworked Landvermesser textures to improve speculars, add normal maps, and TU support

============
Credits:
============

Huge thanks to my Patreon supporters for helping me continue to work on the mod!!

-DMagic: For his ScienceAnimate plug-in and his work on DMagic Orbital Science
-Beale: For donating Fomalhaut and the Vorona dish for me to modify and use
-CobaltWolf: For Huygen's texture, BDB ScienceDef, and all sorts of other help and shenanigans
-Gordon-Dry: Many config tweaks and fixes, RemoteTech configs
-Pistachio_Moustache: ScienceDef assitance
-masTerTorch: KDEX experiment and definitons, redistributed under his CC BY-NC-SA license
-Jso: Great feedback, Tweakscale configs, and fixing the Ground Plane animation!
-Rakol: RemoteTech configs
-Rasta013: AntennaRange configs
-komodo: DMagic contract fixes, part CFGs, Magnetometer Node fix, RemoteTech configs
-Stone Blue: Bug finding, suggestions and testing
-JadeOfMaar: PlumeParty FX and configs
-TheDevHole crew: Dank memes

Thanks to everyone who supports and provides feedback and ecouragement on the Forums! Thanks to my wife and family for putting up with me through long hours of mod work

Also, thank you for downloading and playtesting! I look forward to your feedback! -Akron

============
License:
============
ProbesPlus! is distributed under a CC-BY-NC-SA 4.0 license. Please let me know if you release anything based on my work
Firespitter and DMagicScienceAnimate are re-distributed under their respective licenses


----------------------------------Older Change Logs:----------------------------------
Beta 0.16.1

New Parts:  

==IUE Parts==  
* 'Explorer' Telescope Probe  
* IUE Solar Panels  
* 'Stella 24C' Solid Rocket Motor  
  
==Surveyor B Parts==
* New probe core  
* Solar Panel  
* Planar-array HGA  
  
Updates/Fixes:

* Tweaked for KSP version 1.4.x 
* Updated the included DMagicScienceAnimate to version 0.20  
* Updated the included FirespitterPlugin to version 7.90  
* Added ResearchBodies and Tarsier Space Technologies compatibility (For the new IUE part)  
* Added some MKS module support. Thanks to LouisCyfer
* Changed all parts with RCS nozzles to use the new RCS module  
* Changed all engines to use new engine module  
* Reduced 'Lahar' engine ISP to 305 @ vacuum  and thrust to 6 kN  
* Reduced 'Linkor' engine ISP to 325 @ vacuum  
* Reduced 'Trident' engine thrust to 9 kN  
* Added upgrade options to the 'Landvermesser' vernier engine  
* Tweaked some RCS stats for blance  
* Fixed issue with the Parachute texture  
* TexturesUnlimited configurations were updated to use new synthax  
* Tweaked a few of the TexturesUnlimited Shader settings  
* Removed some texture replacement referencing from some parts to prevent part loader errors 

Beta 0.16
  
New Parts:  
  
==Cassini-Huygens Parts==  
* 'Meridiani' Probe core  
* 'Draco' Lander Core  
* Draco's heashield, aeroshell, and parachutes  
* HGA Antenna  
* Fuel Tank Assembly  
* Reaction Wheel Assembly (LEU)  
* CA-MER-R4D 'Dominique' Main Engine  
* Magnetometer Boom  
* Payload adapter/decoupler  
* Draco decoupler ring  
* Remote Sensing Pallet  

==Probe Cores==  
* CA-100B 'Landvermesser' B Core (Inspired by Surveyor B)  
* CA-Q20-M 'Xihe' Probe Core (Inspired by STEREO)  
* CA-602 'Hera' Probe Core (Inspired by Juno)  
* CA-v601 'Aegis' Probe Core and science container (Juno)  
  
==Antenna==  
* CA-A20-B HGA Antenna (Inspired by Surveyor B)  
* CA-D02 HGA Dish (STEREO)  
* CA-A190 HGA Dish (Juno)  
  
==Electrical==  
* CA-ET120 Solar Array (Inspired by Surveyor B)  
* CA-E140 Solar Array (STEREO)  
* CA-E12 Solar Array and magnetometer (Juno)  
  
==Science==  
* CA-RPWS-S Compact RPW System (STEREO)  
  
Updates/Fixes: 
  
* Corrected and added more Science results for GroundOps experiments  
* Added Science experiment result support for Outer Planets Mod  
* Removed Dmagic Orbital Science as a dependency (For simplicity, I still recommend DMagic's Mod)  
* Updated some solar panel textures  
* Added PBR configs for Shadowmage's TexturesUnlimited mod  
* Added new set of textures for texture toggle  
* Reduced mass but increased cost of the Torekka Dish to bring it closer to the stock equivalent  
* Reduced mass of the Tatsujin dish  
* Reduced Lahar Engine thrust to begin engine balance to more realistic values. More nerfs coming!  
* Reduced Trident Engine thrust to begin engine balance to more realistic values. More nerfs coming!  
* Updated SCANsat support for the new version 18.0  
* Updated the RTG8200 model to more closely match Cassini's. The old model will be retired in the next release  
* Fixed a symmetry issue in the Landvermesser lander core 
* Fixed attachment node issue on Landvermesser lander core   
* Fixed attachment node issue on Landvermesser omni antenna  
* Fixed attachment node on the GRS  
* Fixed a texture load error for all the normal maps (Thanks to Gordon Dry for the fix)  
* Fixed Node orientation on the Landvermesser HGA  
* Fixed Node and fairing issue on the Landvermesser core  
* Disabled antenna power upgrades!!!! To prevent a potential CommNet bug. Verify the DSN range to any active distant probes before upgrading to this version!!!  
* Retired the old cone antenna  
* Added Optional Near Future Electrical RTG decay configs (Thanks to notJebKerman)  
* Updated RealPlume configs  
* Updated Tweakscale configs (Thanks to JSO)  
* Updated RemoteTech configs (Thanks to Jimbodiah)  
* Updated MechJeb and EngineerRedux support  
* Updated included dependencies of Firespitter (Version 7.6.0) and DMagicScienceAnimate (Version 0.19)  

Beta 0.15

New Parts!
*Many new parts inspired by Venera/Vega and Surveyor

	==Probe Cores==
	*CAE-L165 Fomalhaut Lander (Inspired by the Venera Lander)  
	*CAE-200 'Vorona' Probe core (Inspired by Vega)  
	*CA-L100 'Landvermesser' Lander (Inspired by Surveyor)   
	
	==Antenna==
	*CAE-A03 Communication Array  
	*CAE-102 Vorona Dish Antenna  
	*CA-AE20 HGA Antenna and Solar Panel  
	*CA-A07 Landvermesser Omni Antenna  
	*CA-KPS GPS-styled KerbNet antenna  
        *New toggle options for the cone antenna  
	
	==Electrical==
	*CAE-E1200 Vorona Solar-Thermal System  
	*CAE-E175 Fomalhaut Solar Panel
	*CA-55i Landvermesser Battery  

	==Propulsion==
	*CAE-LT98 Vorona Liquid Fuel Tank  
	*CAE-MT12 Radial Monopropellant Tank
	*CAE-LV175A "Kurt" Vorona Liquid Fuel Engine (Based on the Russian KTDU-425A engine)  
	*New 2-way Medium RCS
	*CA-SB15 Landvermesser Solid Rocket Retromotor  
	*CA-LV03 Landvermesser Vernier Engine  
	*Torekka/Voyager Propulsion Module and adapter truss  

	==Science==
	*CAE-MG03 Magnetometer 
	*CA-CAM-S1 Landing Site Survey Camera (New experiment!)  
	*CA-SC28-L Topsoil Scoop (New experiment!)  
	*CAE-SC-VIS Vorona Imaging System (Based on Vega 1 & 2)
  
	==SCANsat==  
	*CA-HOLA Laser Altimeter (Based on Mars Surveyor)  
	*CA-H2RS High-Res Radar Altimeter (Based on MetOp)  
	*CA-TRIXIE Multispectral Imager (Based on New Horizons)
	*CAE-SAR15 Vorona Radar Antenna (Based on Venera 15/16)

	==Thermal==
	*CAE-HS100 Fomalhaut Heat Shield 

	==Utility and Control==1
	*CAE-D13-F Stack Decoupler 
	*CAE-P16 Fomalhaut Parachute 
	*CAE-PD7 Fomalhaut Drogue Parachute  
	*CA-ESM2 Quetzal Stack-mounted Service Module  

*New science experiment definitions for new parts  

Update/Fixes:  

-Updated the included Firespitter and DMagicScienceAnimate DLLs to latest versions  
-Fixed a deprecated texture reference in the ESM part  
-Changed Tatsujin Dish to use FS mesh switching instead of a fairing  
-Fixed thrust offset on the "Lahar" Engine
-Update textures to reduce or eliminate the original foil for better compatibility with stock and other mods  
-Updated paneling textures of parts with texture toggle  
-Added 2 new optional textures toggles: Thermal blanketing, Alternate Gold foil  
-Redesigned the "Stock Grey" texture to better match Squad parts  
-Added texture toggle to Quetzal parts
-Updated BDB compatibility config (Thanks to Aelfhe1m)  
-Updated MM compatibilty patches to include new parts  
-Updated the Barometer experiment to use stock science module intead of DMagic's module to reduce issues
-Removed references to impactTolerance to prevent errors (Thanks KineticSloth)  
-Removed old A200 Antenna model and texture (WARNING: May break old crafts)  
-Tweaked the location of the sunCatcher mesh on the CA-E100 and CA-E100-SPV solar panels to help them receive sunlight under more conditions  

Balancing:

-Reduced Barquetta Monopropellant capacity to 10 units

-NOTE: Old Cone Omni Antenna will be retired on the next release, please use the new toggle version on all new crafts

Beta 0.14.2

Updates:

- Fixed issue with standalone SAS units (Thanks puetzk)
- Fixed texture reference issue with the CA-AD1-R antenna (Thanks puetzk)
- Fixed DM module reference in the GRS experiment
- Change root folder structure to reduce conflicts with multiple Coatl Aerospace mods (upcoming)
- Removed unecessary Firespitter files
- Disable weight reduction upgrades temporarily to fix a KSP bug or syntax error
- Tweaked Physics, drag and thermal settings of several parts

Beta 0.14.1

New Parts!
	==Antenna==
	*CA-AD1-R Small Folding Relay Antenna (Early Tech Relay)

	==Propulsion==
	*CA-MV04 MonoProp Engine (Inspired by Mariner)
	
	==Thermal==
	*CA-TCL4/CA-TCL4-B/CA-TCL8 Three Thermal Louver sizes (Inspired by Mariner and Voyager)

Updates:

- Updated Modules for appropiate parts to match 1.2 stock
- Added KerbNET access to applicable parts
- Added 13 Part Upgrade nodes and setup several parts to be upgradeable
- Updated antenna stats for the new antenna system
	* Some weight reductions done
- Updated part categories
- Moved Thermometer and Barometer to earlier tech nodes to match stock changes
- Fixed issue in Propulsion specular texture
- Fixed some RCS FX offset
- Removed AntennaRange support (Mod no longer updating)
- Monopropellant bottle research cost reduced and moved to General Rocketry
- Corrected some spelling errors in part text

-Updated the included Firespitter and DMagicScienceAnimate DLLs to latest versions
-Added config Support for EngineerRedux and MechJeb2

Beta 0.14

New Parts!
	==Probe Cores==
	*CA-Q04-M 'Tatsujin' Advanced QBE (Inspired by MAVEN and Venus Express)

	==Antenna==
	*CA-A200 Quetzal Dish (Inspired by Pioneer 10, re-design)
	*CA-A500 Tatsujin Dish (Inspired by MAVEN)

	==Electrical==
	*CA-E400MG 1x2 Solar Panels (Inspired by MAVEN)
	*CA-E320/340 Solar Panels (Inspired by Venus/Mars Express)

	==Propulsion parts==
	*3 Small RCS systems (RS01, RS04, RST)
	*3 Medium RCS system (RM01, RM03, RM04)
	*CAE-LV35 "Linkor" Service Module (Inspired by Fregat)
	*CA-LV10 "Lahar" LF Engine (Inspired by Akatsuki)
	*CA-MV15 "Trident" MP Engine (Inspired by MAVEN)
	*CA-MT170 Monopropellant Tank (Inspired by MAVEN)
	*CA-LT80 Liquid Fuel tank
	*CA-MT10 Small Radial MP Tank
	
	==Utility and Control==
	*CA-RW2 Dual Reaction Wheels

Updated Texture and/or models:
	*All previous probe cores
	*Quetzal ESM
	*All electrical parts (Solar panels, rtgs, batteries)
	*All Antenna (some received VERY minor changes)
	*All Reaction wheels, and Stability Systems

Updates:

-Added Firespitter as a dependency (included)
-NEW: Firespitter texture switching for all probe cores and the Quetzal Service Module
-Removed Legacy support for the original magnetometer
-Moved the "RS" RCS to Specialized Ctrl
-Moved the "Startrack" to Specialized Ctrl
-Increased RW1 torque to 1, tweaked stats
-Increased RW1a torque to 1.4, tweaked stats
-Increased RW3 torque to 4, tweaked stats
-Increased AACS SAS level to 3, cost and weight
-Balanced Solar panel stats
-Added Small Reaction Wheels to the E100-SPV Solar Panels to simulate active Solar Pressure Vanes 
-Fixed attachment node on the CA-ROTFL telescope
-Fixed the jumpy animation on the Torekka RTG
-Fixed attachment node angle on the Torekka RTG. NOTE: You need to attach it from the side for it to work (Thanks komodo!)
-Fixed DMagic contract support (Thanks komodo!)
-Added part search tags for the real-life inspiration mission to some parts
-Updated ScienceDefs (Micrometeoroid experiement added, spelling errors corrected)

-CA-A200 Antenna weight slightly reduced and cost slightly increased to balance new functionality (Added RCS)
-Original CA-A200 Antenna is being removed. Currently in as legacy support. It will return redesigned on a later update

-Updated RP, RT and AR configs
-Added Coatl Aerokosmicheskogo Vostok flag

Beta 0.13.1

- Fixed colliders on the 100i battery so it can be selected in the VAB again

Beta 0.13

New parts!
	==Science parts==
	*CA-ELIX Electrostatic and Ionization Experiment (Ranger)
	*CA-KLIR Infra-Red Spec (2001 Mars Odyssey)
	*CA-ROTFL Orbital Telescope (Mars Recon Orbiter)
	*CA-SWIS Solar Wind Analyzer (MAVEN)
	*CA-RPWS Radio Wave Science (Cassini)
	*CA-LUV Ultraviolet Spectrometer (MAVEN)
	*CA-SCGRS Gamma Ray Spec (2001 Mars Odyssey)
	*CA-SCB01 Torekka Science Boom (Voyager)
	*CA-DUST-C Dust collector (Stardust)
	*CA-DUST-X Dust Experiment (Cassini)
	==Other parts added==
	*E200B Solar Panel
	*CA-ESM - Quetzal's Extended Service Module (Pioneer 10/11)

Updated old parts:
	*Improved models and textures of stock replacements
	*New model and texture of the MG100 Magnetometer (Pioneer 10/11)

ATTENTION!: New Magnetometer is of slightly different size. Old model is included but is being deprecated on patch 0.14. 
Recover your vessels!!!

Updates:

-Added specular maps to probes cores and many parts
-Improved older textures
	*Improved weathering and reduced harsh contrast where possible
	*Improved edges to prepare for future specular maps overhaul
	*Darkened the Photovoltaic cells on the E200 series and made them less purple
-Converted textures to DDS
-Changed Ground-plane antenna to use ModuleAnimateGeneric
-Added new ScienceDefs for the new experiments, update existing ones
-Added some Tweakscale Compatibility. Configs by jsolson
-Added Remote Tech Compatibility. Configs by rakol
-Added AntennaRange Compatibility. Configs by rasta013
-Updated part descriptions
-Added part tags
-Reduced A100 mass to 0.35
-Improved Torekka torque to 0.4
-Revised antenna dishes transmission rate for the stock system

Beta 0.12
-DMagicScienceAnimate is now a pre-requisite, but is included
-Added new parts!
	*CA-Q02-M 'Barquetta' probe body
	*CA-A100 Small Dish Antenna (Ulysses)
	*CA-A10 Small folding antenna (Based on ARSAT-1)
	*CA-A01 Ground-plane "TV" antenna
	*CA-A02 Cone antenna
	*CA-A06 Stick antenna for quetzal (Pioneer)
	*CA-E100 and CA-E100-SV Mariner solar panels
	*CA-E200 Odyssey solar panels
	*CA-RW1a Xsmall reaction wheel (Same model as RW1)
	*CA-SC103 Accelerometer (Stock science, based on Maven)
	*CA-ACS 'Startrack' (Startrackers)
-Corrected attachment node orientation on the R8200 RTG
-Improved the torque of the CA-RW3 to 1.7 on all axis
-Moved CA-AACS to the Electronics tech tree node
-Improved CA-AACS to SAS lvl 2
-Fixed CA-SC102 Barometer animation by using DMagicScienceAnimate
-Added several new descriptions to parts that lacked them
-Texture tweaks

Beta 0.11
-Fixed animation and added Voyager RTG
-Textured and added the CA06 'Quetzal' probe bus
-Swapped the Pioneer and Voyager RTGs in terms of power generation and techtree unlock node
	*Pioneer RTG is now the CA-R2000
	*Voyager RTG is now the CA-R3900
-Increased ElectricCharge generation of the CA-R3900 RTG from 0.35 to 0.39
-Decreased mass of the CA-R3900 from 1 to 0.1
-Minor Texture tweaks

Beta 0.1
-Initial release!
