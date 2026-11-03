# ShaguDPS Opacity

Companion addon for [ShaguDPS](https://github.com/shagu/ShaguDPS) (WoW 1.12) that adds
an **OOC Opacity** setting. Out of combat all ShaguDPS windows are shown at that opacity; in
combat, and while the mouse is over a window, they're fully opaque.

## Usage

Open ShaguDPS's settings window. The new **OOC Opacity** row is at the bottom of the
"Window" section: `<` / `>` step from 10% to 100% in steps of 10%. 100% means no fading.
Windows you add later with the "+" button get the same opacity.

The setting is saved with ShaguDPS's other settings. ShaguDPS's own files aren't changed, so
its folder stays a clean git clone.

## Install

- **With a launcher or git:** add `https://github.com/daev-code/ShaguDPSOpacity` as an addon, or
  `git clone` it into `Interface\AddOns`. Keep the `.git` folder: launchers that install
  from git use it to fetch updates.
- **By hand:** copy this folder to `Interface\AddOns\ShaguDPSOpacity`. Updates are then manual too.
