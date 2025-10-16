# FlatOut2 Swap Game Mode (xNya)

My Swap Game Mode mod, built for the xNya mod loader

Every 30 seconds, everybody switches cars

There's both a regular version, and online-friendly version

The online-friendly version makes the RNG completely deterministic, so that everybody in the lobby gets the same results and desyncs don't occur

<br>

## Installing

Just drag and drop the contents of the zip folder to the game's folder and you're done

<br>

## Using

The settings can be changed in `swapGameModeSettings.txt`

`switch_positions` can be true or false, true means when the switch occurs, everyone stays in the same place, just with a different car

`interval` is how often the switch occurs, measured in seconds. The default is 30 seconds

<br>

## Building

I used Visual Studio 2022 on Windows

You'll need Chloe's nya-common library, which can be cloned [here](https://github.com/gaycoderprincess/nya-common). Copy the nya-common folder to `source/SwapGameMode_xNya/SwapGameMode_xNya`, next to `dllmain.cpp`
