*********************************
Coatl Aerospace ProbesPlus! BETA
*********************************

Thank you for downloading and playtesting! I look forward to your feedback! -Akron

============
Known Issues:
============
- Not enough feedback on the Dev thread! Your feedback will help make the mod better!

Please note that the mod is still in BETA and there will be constant changes and updates. If you encounter any issues, please report them on the Github page or the forums!

https://github.com/raveloda/Coatl-Aerospace
http://forum.kerbalspaceprogram.com/index.php?/topic/131145-wip-coatl-aerospace-probesplus-dev-thread-v012-beta-32716/

============
Changelog:
============
Beta 0.14RC

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

-Updated RT and AR configs
-Added Coatl Aerokosmicheskogo Vostok flag

============
Credits:
============

-DMagic: For his ScienceAnimate plug-in and his work on DMagic Orbital Science
-CobaltWolf: For all the encouragement, help and inspiration, BDB ScienceDef
-masTerTorch: KDEX experiment and definitons, redistributed under his CC BY-NC-SA license
-Jso: Feedback, Tweakscale configs, and fixing the Ground Plane animation!
-Rakol: RemoteTech configs
-Rasta013: AntennaRange configs
-komodo: DMagic contract fixes, part CFGs, Magnetometer Node fix, RemoteTech configs
-TheDevHole crew: Dank memes

Thanks to everyone who supports and provides feedback and ecouragement on the Forums!

============
License:
============
ProbesPlus! is distributed under a CC-BY-NC-SA 4.0 license. Please let me know if you release anything based on my work
Firespitter and DMagicScienceAnimate are re-distributed under their respective licenses


----------------------------------Older Change Logs:----------------------------------
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

