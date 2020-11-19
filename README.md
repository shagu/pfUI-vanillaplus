# pfUI Vanilla Plus

An extension for [pfUI](https://github.com/shagu/pfUI) which adds support for the [Vanilla+ Server](https://vanillaplus.org/).
The latest version of pfUI is required and only enUS-Gameclients are supported at the time.
The modifications are based on the research of [@Heroclastus09](https://github.com/Heroclastus09/) and [@hawaiisa](https://github.com/hawaiisa/).

## Note

I don't play on this realm and therefore won't maintain this addon. So this is just an example how things could be done
while keeping it in sync with the official pfUI. If you're eager to continue here, feel free to fork and [hit me up](https://github.com/shagu/)
if you need anything particular on the main pfUI to be changed in order to continue.
Once you took over maintanance, please remove this part from the README.md and add yourself to the LICENSE.

## Installation

1. Download **[Latest Version](https://github.com/shagu/pfUI-vanillaplus/archive/master.zip)**
2. Unpack the Zip file
3. Rename the folder "pfUI-vanillaplus-master" to "pfUI-vanillaplus"
4. Copy "pfUI-vanillaplus" into Wow-Directory\Interface\AddOns
5. Restart Wow

## Features

Vanilla+ is providing a custom client with spells, debuffs and other features that differ from the original game.
This pfUI module updates the pfUI core components to make them aware of those changes. Basically, this is on par
with the features provided by the vanilla+ pfUI fork of [@Heroclastus09](https://github.com/Heroclastus09/pfUI),
with the advantage of being able to always use the latest version of pfUI instead of relying on a outdated version.
In general, those vanilla+ custom changes are:

- Updated debuff durations
- Updated cast durations
- Updated talent based calculations (for debuffs and cast times)
- Updated duration of totems and custom totems
