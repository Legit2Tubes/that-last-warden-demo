# The Last Warden

**Four roads. One last stand.**

A dark-fantasy arcade survival game about quick decisions. Hold the center of a
torchlit courtyard, turn toward approaching enemies, and keep the watch alive.
Your knight attacks automatically. A single unshielded mistake ends the run.

![The Last Warden in play](screenshots/gameplay.png)

## Windows demo v0.1.0

Download **TheLastWarden-Windows-v0.1.0.zip** from this repository's **Releases**,
extract the entire archive, and launch **TheLastWarden.exe**. Keep its `.pck` file
beside it. Godot, an account, and an internet connection are not required to play.
Compare the download with the SHA-256 listed in the release notes.

**Release staging notice:** this demo is prepared for review. Public distribution
awaits confirmation of the supplied art and music licenses; see [credits](CREDITS.md).
No download has been published by this staging document.

## Controls

| Action | Keyboard |
| --- | --- |
| Face north / west / south / east | W / A / S / D, or arrow keys |
| Use held item | Space |
| Activate focused menu button | Enter |
| Pause / resume / back | Escape |
| Restart from pause or game over | R |
| Fullscreen / windowed | F11 or Alt+Enter |

Menus also support the mouse. Controller mappings are D-pad/left stick to face,
A to use an item or confirm, Start to pause, and B to go back. Physical controller
testing is still pending. On-screen direction and item controls are available.

## Know your enemies

| Enemy | How to survive |
| --- | --- |
| Goblin (Hollow) | Face its incoming lane. |
| Mage (Trickster) | It teleports across the courtyard. Face the lane where it finally arrives. |
| Skeleton (Gazer) | Look in any direction **except** its incoming lane. |
| Courier | Face it to collect its visible reward. Missing it causes no damage. |

The Courier fills your single inventory slot. If it is already occupied, collect
the Courier for **10 gold** instead. Items wait for you to press Space:

- **Shield:** protects against one otherwise fatal hit.
- **Clock:** slows approaching enemies for five seconds.
- **Nova:** destroys active hostile enemies. Nova clears award no kill points.

Goblin kills start at **100 points**; Mage and Skeleton kills start at **150**.
Every ten consecutive kills increase the multiplier, up to **5x**. Couriers do
not award kill points. Encounters become faster and more varied as you survive.
Gold, your best score, and volume settings persist between sessions.

## System requirements

- Windows PC with an **x86_64** processor and an **OpenGL 3.3** capable graphics driver.
- Extract both game files to a writable folder; saves use your Windows account.
- A keyboard or mouse. Sound output is optional.

The local release was exercised on Windows build **26200 (25H2)** with an
NVIDIA GeForce RTX 2080 using the OpenGL compatibility renderer. Minimum CPU,
RAM, older Windows versions and other GPUs have not been benchmarked. The tested
GPU is a compatibility reference, not a minimum hardware requirement.

## Demo limits and feedback

This release is a single endless arena with local progression. It has no online
leaderboard or multiplayer. Android, iOS, physical touch/controller devices and
audible sound balance have not been verified for this release. The Windows
executable is unsigned. Asset licensing records remain a publication blocker.

Use this repository's **Issues** to report bugs after publication. Include the
demo version, Windows version, GPU, resolution/window size, control method,
expected and actual behavior, and steps to reproduce. Screenshots help; avoid
posting personal data from your computer.

See [release notes](release-notes.md) and [credits and license status](CREDITS.md).
Godot and bundled third-party license notices are included with the download.
