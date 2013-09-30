# Casual OpenJK Modification #
IRC: irc.quakenet.org #Terminative3

This is just a minor modification based on the OpenJK codebase. This mod will have adjustments made to make it more appealing to the casual saber-only community. Duel fixes, flip kick, emotes, etc, will be added. Many people want to have the improvements of OpenJK, but do not want to lose the features of other mods.

As it stands, it will be serverside-only. A client might be made.

## Installation ##

First, install Jedi Academy. If you don't already own the game you can buy it from online stores such as [Steam](http://store.steampowered.com/app/6020/), [Amazon](http://www.amazon.com/Star-Wars-Jedi-Knight-Academy-Pc/dp/B0000A2MCN) or [Play](http://www.play.com/Games/PC/4-/127805/Star-Wars-Jedi-Knight-Jedi-Academy/Product.html?searchstring=jedi+academy&searchsource=0&searchtype=allproducts&urlrefer=search). Then unpack the OpenJK zip file to your Jedi Academy GameData folder.

## Maintainers (in alphabetical order) ##

* Kaldor

## Dedicated Server ##

In order to run dedicated server, you must use the openjkded binary, running dedicated from the main executable is currently not allowed because it is broken with the addition of modular renderer.

## Developer Notes ##

CasualOJK is licensed under GPLv2 as free software. You are free to use, modify and redistribute OpenJK following the terms in LICENSE.txt.

Please be aware of the implications of the GPLv2 licence. In short, be prepared to share your code.

### If you wish to contribute to OpenJK, please do the following ###
* [Fork](https://github.com/JACoders/OpenJK/fork) the project on Github
* Create a new branch and make your changes
* Send a [pull request](https://help.github.com/articles/creating-a-pull-request) to upstream (Razish/OpenJK)

### If you wish to base your work off OpenJK (mod or engine) ###
* [Fork](https://github.com/JACoders/OpenJK/fork) the project on Github
* Change the GAMEVERSION define in codemp/game/g_local.h from "OpenJK" to your project name
* If you make a nice change, please consider backporting to upstream via pull request as described above. This is so everyone benefits without having to reinvent the wheel for every project.
