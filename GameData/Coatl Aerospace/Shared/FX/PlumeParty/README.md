# PlumeParty

Fancy KSP particle pack for mod makers

The "Plume Party" is a collection of engine particles for parts in KSP, made for mod makers to use. Plume Party uses the stock methods for plumes and stands in the gap between the stock library and RealPlume. Rocket engine plumes are provided with variants for sea level and vacuum. Plume Party aims to provide for many popular sorts of engines: 
* [x] RCS thrusters
* [x] Jet engines
  * [x] Turbofan
  * [x] Turbojet
  * [x] Nuclear
  * [ ] Scramjet (Edge cases/ on demand)
* [ ] Rockets (liquid)
  * [x] Kerolox, Hydrolox, Methalox (**Raptor/Tundra**)
  * [x] Kerolox, Hydrolox, Methalox (**Blue Origin**)
  * [x] Kerolox (**Generic**, Hydrolox and Methalox later)
  * [x] Nuclear
  * [x] Hypergolic (partiality to BDB)
  * [x] Toroidal/annular aerospikes (pending possible revision)
* [x] Rockets (solid)
  * [x] Standard
  * [x] Alternate (**Virgin Galactic**; no configs yet)
* [ ] Generic Trailing Smoke (Once made, these should only be used with SL engines. They behave weird at orbital speeds)
* [ ] Ion engines (Xenon blue only)
  * [x] Standard
  * [x] Hall Effect (no configs yet)
  * [x] Pulsed Plasma (no configs yet)
* [ ] Vapor Vent
  * [x] Launchpad (pending revision/new textures)
  * [x] Transonic vapor cone (pending revision/new textures)
  * [x] Wingtip trails
  * [ ] Stunt plane colored smoke ("ROYGBIV" rainbow palette)

Many of the provided plumes are actually sets of 2 or more, designed to blend seamlessly and create an even more visually appealing composite plume. The included configs "cfg_xyz.txt" should not be allowed to persist as ".cfg" files in GameData. They, and the active files for the stock engines, ending in ".cfg" are for you to use as source to add to part configs in other mods. You, the mod maker, are welcome to bundle the plumes you use into your own mod. This pack is currently not to be treated as a dependency and currently will not be released on the KSP forum, SpaceDock, CurseForge or other such places. This may change at some point, once it reaches a level of completeness.

The intricate work is already done. You just need to do the following:

* Copy and paste.
* Change any `transform` keys' values when necessary.
* Add `localScale = 1, 1, 1` and `localPosition = 0, 0, 0` (default values shown) within `MODEL_MULTI_PARTICLE {}` and change their values when necessary to fit a plume to the desired part. Plume pairs will behave as long as they receive identical settings.
* Remove the ModuleManager PASS codes `@whatever` and `@PART[]` and so on.

Have fun and fly safe™

## Warning
Be aware that faults have been confirmed in the `localScale` function. Plume scaling breaks in any engine with more than one nozzle and at the 6th effect transform on an RCS thruster.
Plume Party has known incompatibilities with ReStock and will, where possible, avoid activation on engines made or remodeled by Nertea.

