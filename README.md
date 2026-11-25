# Gal Pani X for Wii

Gal Pani X (D5, 2004, Windows), ported to the Nintendo Wii by [WiiRevs](https://wiirevs.com).

This is a native port, not an emulator: the game's own program runs as native Wii code.

## Download

Get `galpanix.zip` from [Releases](../../releases/latest).

## Bring your own game files

The game isn't included. D5 offers the final edition as a free download from its own site: http://mapleford.net/d5-dot/gpx/download.html

You need these files from it: `gpx.exe`, `graphic.gp`, `music.gp`, `portrait.gp`, `system.gp` and `inst.dat`.

## Install

1. You need a Wii with the [Homebrew Channel](https://wiibrew.org/wiki/Homebrew_Channel) and a FAT32 SD card. [Wii Hacks Guide](https://wii.hacks.guide) explains how.
2. Unzip `galpanix.zip` to the root of the SD card. That gives you `apps/gpx/`, and the music's soundfont in `wiirevs/gpx/`.
3. Copy your game files into `sd:/wiirevs/gpx/`.
4. Start Gal Pani X from the Homebrew Channel.

No room on the card? The game's folder can go on a USB drive instead, as `usb1:/wiirevs/gpx/` (the app stays on the SD card). When both have it, the SD card's is used.

The game checks its files when it starts and lists any that are missing or wrong.

## Music

The game's MIDI music plays through [TimGM6mb](https://sourceforge.net/p/mscore/code/HEAD/tree/trunk/mscore/share/sound/) by Tim Brechbill (GPL-2), included as `wiirevs/gpx/TimGM6mb.sf2`. Without it the game plays its sound effects but no music.

## Feedback

Found a problem or have a question? Use [Issues](../../issues) or [Discussions](../../discussions).

## More

All the games: [wiirevs.com](https://wiirevs.com)

Gal Pani X is a trademark of D5. Nintendo and Wii are trademarks of Nintendo. WiiRevs isn't affiliated with or endorsed by either.
