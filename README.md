# VRC Fusion 360 Library

## Contents

- [Installation](#installation)
- [FAQ](#faq)
- [Changes](#changes)
- [VEX CAD Discord](#vex-cad-discord)
- [Tutorial Series](#tutorial-series)
- [Contributors](#fusion-360-library-contributors)

---

## [Latest Release](https://github.com/VEX-CAD/VEX-CAD-Fusion-360-Library/releases/latest)

This parts library features every VRC legal part currently available, and will continue to be updated as new parts get released. This library is the second iteration of the original Fusion 360 Library.

### Installation

Follow instructions below to use the [Fusion Batch Import](https://github.com/zeulewan/fusion-batch-import) script to import all parts at once:

1. Download this library's [zip file from the latest release](https://github.com/VEX-CAD/VEX-CAD-Fusion-360-Library/releases/latest)
2. Unzip the downloaded file
3. Install [GitHubToFusion360](https://apps.autodesk.com/FUSION/en/Detail/Index?id=789800822168335025) from Autodesk App Store
4. In Fusion 360, press `Shift+S` → run **GitHubToFusion360**
5. Paste: `https://github.com/zeulewan/fusion-batch-import` → Install
6. Run **FusionBatchImport** (`Shift+S`) and select the unzipped folder. Takes ~7 minutes.
7. All parts import with folder structure preserved!

### FAQ 
Click [here](https://github.com/vindou/VEX-CAD-Fusion-360-Library/wiki) to see frequently asked questions about the library.

### Changes
Most notably, the [Fusion 360 Add-In](https://github.com/vexcad/fusion-library/releases/download/v1.0.0/fusion_addin_1_0_0.zip) is *no longer supported*, however there are plans to re-implement the add-in in the future. 

There are now files for *every length* of structure, similar to the [Inventor library](https://github.com/VEX-CAD/VEX-CAD-Inventor/releases/tag/v1.4.0), and all motion pieces that support inserts now have individual files for every type of insert, including no insert.

Shafts also come in every length: `Motion/LS Shaft/` covers 0.5" to 12.0" and `Motion/HS Shaft/` covers 0.5" to 24.0", both in 0.5" increments. If you need a length that isn't listed, open `Motion/LS Shaft.f3d` or `Motion/HS Shaft.f3d`, go to **Modify > Change Parameters**, and set `shaft_length` (valid up to 12.1", the length of the stock bar in those files).

Additionally, every available length for spacers, screws, and standoffs are now available. 

[You can view the full changelog here](https://github.com/VEX-CAD/VEX-CAD-Fusion-360-Library/blob/main/changelog.md)


## VEX CAD Discord
If you need more help, or would like assistance from experienced users, please ask in our [Discord server](https://discord.gg/BKV3DJm)!



## Tutorial Series
[Stratford Robotics](https://www.youtube.com/@StratfordRobotics29295) has put out some great tutorials for Fusion 360, so please be sure to watch them!



## Fusion 360 Library Contributors
### Current Contributors
Currently, no one is working on updating the library. If you would like to contribute, join the [Discord server](https://discord.gg/BKV3DJm), and message the server leadership.

### Past Contributors
- Aidan - BUFF
- George - BUFF
- Flis - EZER
- Jess - EZ
- Justin - 3018E
- Yuanyang - 1721G
- [Chang](https://github.com/vindou) - 5327K, BLRS
- [Ali](https://github.com/aliuahma) - 1353V, 80001B
- [Zeul](https://github.com/zeulewan/) - [Fusion Batch Import](https://github.com/zeulewan/fusion-batch-import)
- [Ryu](https://github.com/reerooryu) - 4139D
- Ryan - 355Z
