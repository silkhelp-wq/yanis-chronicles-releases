# Yanis Chronicles — playtest builds

Downloadable playtest builds of Yanis Chronicles, a tactical RPG built in Unreal Engine 5.
The source lives in a private repository; this repo only hosts the packaged builds.

## Get the game

Open the [Releases](../../releases) page and download the zip for your system. You only need
to do this once: the launcher inside keeps the game up to date.

## Windows

1. Unzip the file anywhere (for example your Desktop).
2. Open the unzipped folder and run `YanisLauncher.exe`. It checks for a newer build, installs
   it over the folder if there is one, then starts the game.
3. If Windows warns about an unknown publisher, pick *More info*, then *Run anyway*.
4. If it asks to install the Visual C++ runtime, say yes. It is included and only happens once.
5. The first launch compiles shaders and can take a minute. Later launches are quick.

`YanisChronicles.exe` starts the game without the update check.

## Linux

1. Unzip the file anywhere.
2. Run `./YanisLauncher` from the unzipped folder (or `./YanisChronicles.sh` to skip the update check).
3. Needs Vulkan drivers; any recent desktop works.

## Reporting problems

Say what you were doing, what happened, and attach the log from
`YanisChronicles/Saved/Logs/YanisChronicles.log` inside the unzipped folder.
