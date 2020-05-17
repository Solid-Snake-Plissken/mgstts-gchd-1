# Metal Gear Solid: The Twin Snakes "HD Texture Pack"

Higher quality assets for Metal Gear Solid: The Twin Snakes for Nintendo GameCube. The goal is to maximize the quality of assets that would be reasonable to run. I'd like to put something here. Excuse me, Hirano-san.

## Getting Started

### Installing

Ensure you have a backup in order to revert.

Extract the ZIP somewhere comfortable and follow below steps.
 
    .Dolphin                     # Dolphin's Profile Folder
    ├── Cache                    # Dolphin's Cache Folder
    ├── Config                   # Dolphin's Config Folder
    ├── Dump                     # Dolphin's Dump Folder
    ├── GameSettings             # Dolphin's GameSettings Folder
    ├── GC                       # Dolphin's GC Folder
    ├── Load                     # Dolphin's Load Folder
    │   └── Textures                 # Dolphin's Textures Folder
    │       └── GGSEA4                   # MGSTTS Disc 1 Folder
    │           ├── Item Description         # Item Description Textures
    │           ├── Splash Screens           # Splash Screen Textures
    │           ├── Subtitles                # Subtitle Textures
    │           └── Text                     # Text Textures
    ├── Logs                     # Dolphin's Logs Folder
    ├── Maps                     # Dolphin's Maps Folder
    ├── ResourcePacks            # Dolphin's ResourcePacks Folder
    ├── ScreenShots              # Dolphin's ScreenShots Folder
    ├── Shaders                  # Dolphin's Shaders Folder
    ├── StateSaves               # Dolphin's SaveStates Folder
    ├── Styles                   # Dolphin's Styles Folder
    ├── Themes                   # Dolphin's Themes Folder
    └── Wii                      # Dolphin's Wii Folder

Drag and drop the GGSEA4 folder from your download over to the install path's Dolphin\Load\Textures\ folder.

### Uninstalling

Just delete the GGSEA4 folder

## Methodology

The idea here is to try to get as crisp and clean of assets as we can. Either by cleaning up existing textures, upscaling/downscaling FMVs with cleanup, recapturing FMVs, ripping from the HD/PS2 versions, etc.

### Text

Text was upscaled 4x using nearest neighbor. This is to get the box font to look extra crisp. From there, manual pixel interpolation was done to ensure a consistent and crisp look. As for other text, they have been recreated with a matching font (see [MISC.md](https://github.com/UltimateNova1203/mgstts-gchd/blob/master/MISC.md)).

### Textures

Textures are ripped from the HD Editions of MGS2/3, originals upscaled by hand or upscaled using waifu2x. If there is any color banding, it was manually touched up by hand to fix it as best as possible.

The upscaling takes the original resolution and upscales it by 4x, so a 256x256 texture will become 1024x1024, 1024x1024 will become 4096x4096, etc. 

## Authors

* **Sam/Vega** [UltimateNova1203](https://github.com/UltimateNova1203)

Any [contributors](https://github.com/UltimateNova1203/mgstts-gchd/contributors) can be found here.

## Acknowledgments

* Dolphin team, for the emulator
* Hideo Kojima, for the experience.
* Nintendo, for the hardware.
* Silicon Knights, for the game.
