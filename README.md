# msfs-fix-atmosphere-parameters


# NO LONGER MAINTAINED

I do not have time to keep searching the hex values and release a patch on this program every time Asobo updates their exes (nor can fetch them for either Steam and MS Store :/) so I've decided I am not going to be updating this program. 
Please use this instead: https://github.com/jet2code/arpc-injector


![Build](https://github.com/auroraisluna/msfs-fix-atmosphere-parameters/actions/workflows/release-build.yml/badge.svg) ![Discord](https://discord.com/api/guilds/933058285140078653/widget.png?style=shield)

**⚠️ 1.31.3 STEAM VERSION ONLY**

This tool modifies the atmosphere parameters on the FlightSimulator.exe to improve visuals. 

This tool is based on the coefficients found here: https://forums.flightsimulator.com/t/replace-the-atmosphere-parameters-with-more-accurate-ones-from-arpc/607603

The JavaScript code is based on the C++ work of maya_biology on the "Hot Start" Discord. [Link to C++](https://discord.com/channels/397379810067742721/745783644936994887/1150846297797042267)

## How to use

1. Download the latest release from the [releases page](https://github.com/auroraisluna/msfs-fix-atmosphere-parameters/releases/latest)

Make sure you download the `fix-msfs-atmosphere.exe` file not the source code!

2. Extract the `fix-msfs-atmosphere.exe` file in a folder
   
3. Copy the FlightSimulator.exe from the game files.
   
🔎 You can find your FlightSimulator.exe via: Open Steam, right click on Microsoft Flight Simulator, click on Properties, click on Local Files, click on Browse Local Files. 
  
4. Paste the FlightSimulator.exe in the folder you created in step 2
   
5. Run `fix-msfs-atmosphere.exe`
   
6. Wait for the process to finish

7. Copy the newly made FlightSimulator_Modified.exe to the game folder (from step 3) and rename it to FlightSimulator.exe. Make sure to rename the "FlightSimulator.exe" to something like "FlightSimulator.exe.backup" to revert the mod. You can also move this to another folder.  
  
⚠️ Note: Do not delete "FlightSimulator.exe" from the folder that contains this tool, as if you want to revert this change, you will need this original file and this might be the only place you have it in 😉

8. Enjoy!

## How to revert

You have one option: 

Copy the original FlightSimulator.exe
Since you have copied the original FlightSimulator.exe in step 3 of the [How to use](#how-to-use) section, you can just copy it back to the folder you found in step 3 and rename it to FlightSimulator.exe

Option B: Steam Integrity Check (Has a 50% chance to work)
**🚨 Not recommended for standard installations - may delete your entire game files or community folder)**
1. Open Steam, right click on Microsoft Flight Simulator, click on Properties, click on Local Files, click on Verify Integrity of Game Files
2. Wait for the process to finish
3. Hope Steam didn't delete your entire game files
4. Enjoy


## Errors / Issues

Common errors:
- "Error: FlightSimulator.exe does not exist.": Make sure you have copied the FlightSimulator.exe as described in the [How to use](#how-to-use) section.
  
If you get a different error than this one, please open an issue and attach a screenshot of the error message.

## Need help?

Join my Discord: https://discord.gg/5MeXEJzubC or open an issue.

## Build from Source / Development

### Requirements

- Node.js v16 or higher
- npm 

### Installation

1. Clone the repository
2. Run `npm install`
3. Run `npm run build` to build the executable

## Contributing

Pull requests & issues are welcome. If you have the MS Store version of MSFS, do share your Hex findings so we can modify this app to do both. 
