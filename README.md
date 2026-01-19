# Atari800 Core

This core emulates Atari 8-bit computers (400, 800, XL, XE) and the 5200 console.

## BIOS Files

Put these in your `BIOS/A800` folder:

- `ATARIOSA.ROM` - OS A for early 400/800 games
- `ATARIOSB.ROM` - OS B for most 400/800 games
- `ATARIXL.ROM` - XL/XE OS
- `ATARIBAS.ROM` - Atari BASIC
- `5200.ROM` - 5200 console BIOS

## ROM Files

Put those in your `Roms/(A800)` folder.

## Controls

| Button | Action |
| --- | --- |
| D-Pad | Movement |
| B | Fire |
| A | Fire 2 |
| Start | Start |
| Select | Select |
| L1 | Option |
| R1 | Atari800 Menu |

## Common Issues I've Encountered

**Game boots to "Memo Pad" or BASIC prompt:**
-  Try turning off "Internal BASIC" in core options. Most disk games won't boot with BASIC enabled.
-  It's also possible that the extension is not working properly. In that case, please let me know.

**5200 games don't work:**
- Set "Atari System" to `5200` in core options.
- Alternatively, just use the already existing, mature 5200 core.

**Flob slaps:**
- I know.



## More Information

https://docs.libretro.com/library/atari800/
