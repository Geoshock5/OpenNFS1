## OpenNFS1
OpenNFS1 is a ground-up remake of the original EA Need for Speed 1. The code is all written from scratch without reverse engineering executables, and it uses the original data files that were on the CD back in 1995! The format of the various binary data files was worked out by Ian Brown, Denis Auroux and myself.

## My fork (Geoshock5)
The original codebase did not build on modern systems (error messages creating OpenGL display).  The main aim of the fork was to bring the code up to date using the latest Monogame (3.8 at time of writing).
Planned additional / improved features including bug fixes, expanded use of original sound / physics files and a physics rewrite, ideally with collisions, are planned to bring it into line with the original game.

## Main features
  * Written in C# and XNA. (Now converted to Monogame)
  * 16 tracks with scenery, animations, tunnels
  * 9 drivable cars with animated dashboards
  * Can drive tracks backwards (not allowed in the original)
  * Can drive past the finish signs on open road stages to see the real end of the track (probably never seen by anyone except by the original developers!)

## Requires
  * OpenAL
  * Monogame >= 3.8.0
  * .NET 4

### Build from source
```
git clone https://github.com/jeff-1amstudios/OpenNFS1.git
```
Open OpenNFS1.sln in Visual Studio

### Installer
You can also install the last stable binary from the [Releases page](https://github.com/jeff-1amstudios/OpenNFS1/releases)

## Legal:
Models, textures, tracks, cars by Pioneer Productions / EA Seattle (C) 1995.
OpenNFS1 is not affiated in any way with EA or Pioneer Productions
