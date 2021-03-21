# ModShot-steamshim-parent
Steamshim parent executable, compiled for [ModShot](https://github.com/Astrabit-ST/ModShot-Core). It's the equivalent of `steamshim.exe` / `steamshim` from vanilla OneShot.

## Usage

1. Add a `icon.ico` for your mod's icon (only required for windows).
2. Acquire a copy of the Steamworks SDK, then extract it into this repo.
3. Compile this using cmake (should be fairly easy on linux. If you are on windows, good luck setting up your toolchain)
4. Place the executable, `steam_api64.so/dll`, and a `steam_appid.txt` containing your steam mod appid into the game's base folder.
5. Enjoy.

## License
This repo uses a zlib license, since that's what the original steamshim uses.

This repo also incorporates changes made by Eliza and KockaAdmiralac over at the [mkxp-oneshot](https://github.com/elizagamedev/mkxp-oneshot/tree/master/steamshim_parent) repo.

Note that Steamworks itself is distributed separately and has a separate proprietary license.
