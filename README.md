# GridGogger
A patch to convert Race Driver Grid exe file from Steam to a LAA-patched Gog one, that will work with Special-K and DXVK, so the game will be able to use vulkan an HDR properly. The script will also apply the [GridMTFix](https://github.com/xatornet/GridMTFix) for resolution fixes and multithreading fixes. 

I've made it this way, because I could not upload the GOG exe file entirely, for obvious reasons. 

IMPORTANT NOTE: As the exe file would be completely transformed to a GOG one, Steam services (not that the game uses them for gameplay or anything) won't work. ~~So other players won't be able to see you playing the game, and I don't know if Steam will track the time you've been playing the game~~ (this apparently works fine). Take this into consideration in case you really need those things.

## What exactly does this fix?
This script patches Steam Race Driver Grid exe file to transform it to GOG's release exe file. It also applies a Large Aware Adress memory patch to it. This way, you get a fully drm-less file that also works properly with DXVK and Special-K, to be able to enable HDR and other stuff. It will also, apply the GridMTFix over all of this.

### * GOG Release / DRMless releases
This is not for you. Use [GridMTFix](https://github.com/xatornet/GridMTFix) for your release.

### * Steam Release
Just download the script, and let it work. NOTE: As the exe is completely changed, Usethe v0.2 release now, be sure to select de Steam exe, it will automatically patch the exe to remove DRM and apply the MTFix.

If you don't want the exe file to be converted, just head back to my [GridMTFix](https://github.com/xatornet/GridMTFix).

## How to apply the fix
If you already have the requirements above done, the fix is easy to apply.

### 1-Download the fix 
You can download the fix as is, but in order for Windows to be able to execute powershell scripts, you have to enable it through the admin powershell console. And it's tedious. That's why I've compiled with PS2exe the script into an EXE file. 

Download the file "GridGoggerMTFix.exe" and paste it on the main Race Driver Grid folder, just near the grid.exe file.
[Releases](https://github.com/xatornet/GridGogger/releases/)

### 2-Execute GridGoggerMTFix.exe
Let it do its things

### 3-Run the game and reconfigure it.
Your settings should be gone. Set them up again.

### If everything works, you can now play Race Driver: Grid making the most out of your hardware.

### * Strong Recommendation
I really encourage you to pair this fix with [DXVK from Doitsujin](https://github.com/doitsujin/dxvk) if your GPU is Vulkan capable. And if you have HDR, you can use it paired with [Special-K mod](https://www.special-k.info/).
