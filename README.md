# Sonic Falcon

Sonic 1 for the Atari Falcon 030. 
First public alpha :)

Requires a Falcon 030 at 16 MHz, with 4 MB of RAM.
The game runs at 320 x 224 with background parallax and DMA sound.

Only Green Hill Zone Act 1 is included for now.

[Download alpha 0.1](./Sonic-Falcon-0.1-alpha.zip)

Unzip and run `SONIC.TOS` from the `SONICF01` folder. Please keep the data files and subfolders alongside it.

## Controls

- Left/right arrows: move
- Up/down arrows: look up / crouch
- Space: jump or start the game
- Joystick: directions and fire work too
- R: restart
- Esc: quit

Background parallax is enabled. The P and M options from the STE version do not apply to this version.
The [STE / Mega STE version](https://github.com/guybrush-atari/Sonic-STE) is available separately.

## This alpha

Frame rate varies with the scene; optimisation is ongoing.

## Credits

Original game by SEGA / Sonic Team. This is a free, unofficial fan project.

Based on Sonic Retro's [s1disasm](https://github.com/sonicretro/s1disasm). Thanks to its contributors. Uses flamewing's [mdcomp](https://github.com/flamewing/mdcomp) to decompress the Mega Drive data.

Tools: [Hatari](https://www.hatari-emu.org), [EmuTOS](https://emutos.sourceforge.io), GCC m68k-atari-mint ([FreeMiNT](https://freemint.github.io)), [Unicorn Engine](https://www.unicorn-engine.org).

Some useful references:

- Douglas Little: [AGT](https://bitbucket.org/d_m_l/agtools)
- Jeffrey Young: [Hardware Phase Scrolling](https://github.com/jayoung99/Atari-STE-Hardware-Phase-Scrolling)
- Leonard / Arnaud Carré: [Graphics Tricks from Boomers](https://arnaud-carre.github.io/2024-09-08-4ktribute/)
- The Paranoid / Paradox: [The Atari ST(E) BLiTTER in brief](https://www.atari-wiki.com/index.php?title=The_Atari_ST(E)_BLiTTER_in_brief_by_The_Paranoid_of_Paradox_2012)
- Zeme: [Sync scrolling](https://blog.subspace.nl/2026/03/18/sync-scrolling.html)
- Condense: [Sonic GX](https://www.pouet.net/prod.php?which=105245) for Amstrad Plus / GX4000
