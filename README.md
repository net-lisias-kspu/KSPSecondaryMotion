# KSP Secondary Motion

KSP Secondary Motion is a Kerbal Space Program mod that adds secondary motion to the game, such as the spring physics of antennas or solar panels.

This mod is currently working in progress, this is an Unofficial fork by Lisias.

## In a Hurry

* [Latest Release](https://github.com/net-lisias-kspu/SecondaryMotion/releases)
	+ [Binaries](https://github.com/net-lisias-kspu/<SecondaryMotion/tree/Archive)
* [Source](https://github.com/net-lisias-kspu/SecondaryMotion)
* Documentation
	+ [Project's README](https://github.com/net-lisias-kspu/SecondaryMotion/blob/master/README.md)
	+ [Install Instructions](https://github.com/net-lisias-kspu/SecondaryMotion/blob/master/INSTALL.md)
	+ [Change Log](./CHANGE_LOG.md)
	+ [TODO](./TODO.md) list


## Description

KSP Secondary Motion adds secondary physics motion to some stock antennas and solar panels, it also added some brand new parts to the game.

This mod is still working in progress, the APIs are subject to change.

![Antenna](./Media/Honeycam 2020-07-15 00-53-19.gif)
![Solar Panels](./Media/Honeycam 2020-07-15 01-04-07.gif)


### Features:

* Wobbling antennas and solar panels
* Real-world used ground antennas
* CREW Duke Anti-IED system (BDArmory support, works as a jammer)
* TweakScale support
* A plunger
* Wacky Waving Inflatable Arm Flailing Tubemen
* Pickle Rick!

### How to Use:

Generally, there is no need for the user to adjust settings, but if you don’t like the wiggliness of a certain part, you can adjust the Damper Ratio and the Spring Ratio in the right-click menu of that part. 
The current version of the mod also has a Failsafe Activate Range slide bar in the right-click menu, if you find that the part behaves abnormally during the flight (such as flashing), you can increase the value to reduce or eliminate the effect. I am currently trying to fix this behavior, it is related to KSP's Floating Origin and Krakensbane, this option will not in the v1.0 release if the problem is addressed. Help and suggestions for fixing this problem are welcome.

### Part List: 

* Stock:
	+ Gigantor XL Solar Array
	+ Communotron 16
	+ (I am having difficulties with adding secondary motion to other stock antennas, solar panels, and radiators. That may change before the 1.0 version.)
* New:
	+ APX-50 HF Mobile Whip Antenna (4 sections, 5m)
	+ APX-50 HF Mobile Whip Antenna (2 sections, 2.6m)
	+ APX-50 HF Mobile Whip Antenna (4 sections, 5m, Tied Down)
	+ AN/VLQ-12 CREW Duke
	+ AN/VLQ-12 CREW Duke Front Antenna
	+ CREW Duke Right Angle Adapter
	+ CREW Duke Structural Beam (1.6m, 1.25m, 0.63m, 0.37m)
	+ UHF727VM Multi-Band LTE Antenna
	+ VHF3088T Tunable Low Profile VHF Antenna
	+ VHF100512SLP VHF/UHF Low Profile Broadband Antenna
	+ Wacky Waving Inflatable Arm Flailing Tubemen
	+ The Plunger Antenna

### Modding:

If you are a mod creator and looking for adding secondary motion effects to your mod, the documentation is coming soon. It will be simple as adding two additional transforms to your part. The mod even allowed you to reconstruct the existing part hierarchy from a Module Manager script without re-exporting the part from unity (That's how I add the effect to stock parts). Note that the mod is still working in progress, the APIs are subject to change.


## Installation

Detailed installation instructions are now on its own file (see the [In a Hurry](#in-a-hurry) section) and on the distribution file.

## License:

This work is licensed under the [MIT](./LICENSE).

Please note the copyrights and trademarks in [NOTICE](./NOTICE).


## UPSTREAM

* [Icecovery](https://forum.kerbalspaceprogram.com/index.php?/profile/168058-icecovery/) ROOT
	+ [Forum](https://forum.kerbalspaceprogram.com/index.php?/topic/195625-*/)
	+ [SpaceDock](https://spacedock.info/mod/2477/)
	+ [Github](https://github.com/Icecovery/KSPSecondaryMotion/)
