﻿## Bulldozer

Flatten an entire planet. Adds foundation to each location in seconds.

Coming soon, support for non-cheaty mode where foundation & soil pile from player's inventory are used (see 'Cheatiness' config properties).

Checkbox next to the action button controls whether guide lines will be added. Config controls types painted (equator, meridian, tropic)

Raising/lowering veins is now a separate operation that takes around a minute to complete. It can be enabled using the checkbox under the guide lines control

Now supports destruction of factory machines. Use DeleteFactoryTrash config property to automatically delete items that would be littered

Example of a planet with all veins lowered

![Example1](https://github.com/mattsemar/dsp-bulldozer/blob/master/Examples/example1.png?raw=true)

Check the "Environment Modification" menu to find the action button
![Example2](https://github.com/mattsemar/dsp-bulldozer/blob/master/Examples/example2.png?raw=true)

Non-cheaty options are not quite complete. For now, foundation is deducted properly but soil pile is consumed at too high a rate.
![Example3](https://github.com/mattsemar/dsp-bulldozer/blob/master/Examples/example3.png?raw=true)

## How to install

This mod requires BepInEx to function, download and install it
first: [link](https://bepinex.github.io/bepinex_docs/master/articles/user_guide/installation/index.html?tabs=tabid-win)

#### Manually

Extract the archive file and drag `Bulldozer.dll` into the `BepInEx/plugins` directory.

#### Mod manager

Click the `Install with Mod Manager` link above.

## Changelog

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
* Add confirmation prompt
* Enable destruction of factory machines (assemblers, etc). By default will not do foundation when enabled

#### v1.0.10
Correct version

#### v1.0.9
Make hidden feature execution independent of foundation adding

#### v1.0.8
* Added support for BepInEx Configuration
* Add config option for overriding raise/bury veins, defaults to using same settings as game ui
* Add config option for overriding foundation decoration style, default is to follow game ui setting
* Add config option to enable skipping equator or meridian painting (individually)
* Add config option for number of update actions executed on each frame
* Added better support for larger radius planets

#### v1.0.7
Fix issue with hover text position
Add option to skip repaving already paved locations
Fix equator & meridian lines for planets with non-default diameter

#### v1.0.6
Added hover text to action button and checkbox and added ability to cancel execution

#### v1.0.5
Handle exception in vegetation removal

#### v1.0.4
Fixed issue where action button icon was showing in other categories
More points added to try and catch missed veins in raise/lower on subsequent executions

#### v1.0.3
Fixed issue where action was not invoked on button press

#### v1.0.2
First version


## Contact
Bugs? Contact me on discord: mattersnot#1983 or create an issue in the github repository.

Icons made by [Freepik](https://www.freepik.com)