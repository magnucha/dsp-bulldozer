## Changelog

#### v1.1.10
Fix compatability with the DSP multithreading update (0.10.33.26934)

#### v1.1.9
Fix for new DSP release

#### v1.1.8
Bugfix: Fix button position when not in sandbox mode and for other tool categories

#### v1.1.7
* Update: Restore UI when sandbox tools are enabled. 'Reform Full Planet' button provided by game is hidden
* Update: GuideLinesOnly mode now supports Honest and HalfCheat foundation modes but does not yet consume soil pile

#### v1.1.6
Bugfix: Hide UI when sandbox tools are enabled
Update: Added some basic support for Bulldoze mode where only guidelines are added. Incomplete, use at your own risk

#### v1.1.5
Update: Make guidelines foundation type match FoundationDecorationMode setting (when it can be resolved to paint or decorate) (thanks PiggyWhiskey on GitHub)
Bugfix: Fix bug in factory teardown when factory has modded items on belts but mod that added item is no longer installed

#### v1.1.4
Update: updated guide marking algorithm to work better with GS2

#### v1.1.3
Bugfix: fix issue with regional painting after switching to a new planet (thanks, Tobias Pottgüter)

#### v1.1.2
Bugfix: fix issue with regional painting where reform index latitude calculations have not been done yet (thanks, Tobias Pottgüter)

#### v1.1.1
Update: Lowered the rate that pre-calculations are when the planet is first loaded (for the UPS)

#### v1.1.0
Feature: Selected Latitudes let you limit the bulldozed areas. Works for veins, foundation, factory teardown.

#### v1.0.32
Fix factory teardown issue and speedup raising/lowering veins

#### v1.0.31
Incorporated fast belt delete proposed by Raptor#4825. Factory teardown should be much quicker now.

#### v1.0.30
Added new setting to control how much time can be spent per update on factory teardown.

#### v1.0.29
Switch default mode for foundation consumption to Honest. Updated to sync with changes to game code.

#### v1.0.28
Added option to preserve plants trees and rocks on planet

#### v1.0.27
Added support for configuring separate colors by _region_, where a region is defined by min/max latitude & longitude. Edit regions from config (must enable property and add regions using Edit Regional Colors)

#### v1.0.26

Bugfix: resolved issue where veins were not being raised (thanks Valoneu)

#### v1.0.24

Skip over landing capsule when removing planet vegetation

#### v1.0.23

Added option for skipping logistics stations when destroying factory components

#### v1.0.22

Fix bug in veins alteration for planets where no foundation was placed

#### v1.0.21

Added ability to customize colors for all guide mark types

#### v1.0.20

Added option to paint poles

#### v1.0.19

Added support for minor meridian lines. Set MinorMeridianInterval > 0 in config window to add

#### v1.0.18

Added config window (thanks runeranger for very helpful feedback)
Improved predicated soil pile usage calculation

#### v1.0.17

Fix issue with config property being out of sync with UI

#### v1.0.16

Speed up operation when veins don't need to be altered

#### v1.0.15

Fixed tropic painting for non-default radius planets

#### v1.0.14

Add option to automatically delete items that would have been littered

#### v1.0.13

Add Universe Exploration 3 as a prerequisite, fix issue with meridian line being too thin at pole. Add tropic line painting

#### v1.0.12

Fix issue where checkbox wasn't being hidden

#### v1.0.11
Add confirmation prompt
Enable destruction of factory machines (assemblers, etc). By default will not do foundation when enabled

#### v1 - v1.0.10
Added support for BepInEx Configuration
Add config option for overriding raise/bury veins, defaults to using same settings as game ui
Add config option for overriding foundation decoration style, default is to follow game ui setting
Add config option to enable skipping equator or meridian painting (individually)
Add config option for number of update actions executed on each frame
Added better support for larger radius planets
Fix issue with hover text position
Add option to skip repaving already paved locations
Fix equator & meridian lines for planets with non-default diameter
Added hover text to action button and checkbox and added ability to cancel execution
Fixed issue where action button icon was showing in other categories
More points added to try and catch missed veins in raise/lower on subsequent executions