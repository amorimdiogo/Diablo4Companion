# Diablo IV Companion - The Inventory Manager 

A companion app for Diablo IV, to make life easier in finding the correct affixes.

```diff
+ Looking for system presets for the download manager, let me know when you want to share them. All different languages and resolutions are welcome.
```

<img src="./readme/readme-001.png" width="500">

If you like my work you can sponsor me on Ko-fi.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H1H5GCR)

## Table of Contents

- [Features](https://github.com/josdemmers/Diablo4Companion/tree/template-matching#features)
- [Installation](https://github.com/josdemmers/Diablo4Companion/tree/template-matching#installation)
- [Configuration](https://github.com/josdemmers/Diablo4Companion/tree/template-matching#configuration)
- [Usage](https://github.com/josdemmers/Diablo4Companion/tree/template-matching#Usage)
- [Troubleshooting](https://github.com/josdemmers/Diablo4Companion/tree/template-matching#Troubleshooting)

## Features

- Specify your prefered affixes for each gear slot and monitor them ingame.
  - Supports affixes, aspects, and sigils.
- Import builds from Maxroll.
- Import builds from D4Builds.gg
- Multi-language support. See [wiki](https://github.com/josdemmers/Diablo4Companion/wiki/How-to-create-translations) if you want to translate the app. 

## Installation

- Download the latest version from [Releases](https://github.com/josdemmers/Diablo4Companion/releases)
- Extract files and run D4Companion.exe
  - Go to settings and select the **System preset** matching your resolution.
    - Make sure to click the update / download button first to get the latest version.
    - Use the recommended app settings listed for each resolution.
  - Go to affixes and create a new **Gear Affix Preset**.
  - Select your prefered affixes for each item slot.
  - Read [Usage](https://github.com/josdemmers/Diablo4Companion/tree/template-matching#Usage) for more details on using the app.

## Configurations

Currently the following system presets are included:


| Preset           | Language                                        | Config                                                                      |  Progress                                  |
| ---------------- | ----------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------ |
| 1050p_SMF_en     | <img src="./D4Companion/Images/Flags/enUS.png"> | SDR (HDR off) with font set to medium for the English language              | ![Progress](https://progress-bar.dev/0/)   |
| 1080p_SMF_en     | <img src="./D4Companion/Images/Flags/enUS.png"> | SDR (HDR off) with font set to medium for the English language              | ![Progress](https://progress-bar.dev/67/)  |
| 1080p_SMF_es-US  | <img src="./D4Companion/Images/Flags/esES.png"> | SDR (HDR off) with font set to medium for the Spanish (LA) language         | ![Progress](https://progress-bar.dev/51/)  |
| 1080p_SSF_de     | <img src="./D4Companion/Images/Flags/deDE.png"> | SDR (HDR off) with font set to small for the German language                | ![Progress](https://progress-bar.dev/40/)  |
| 1080p_SSF_es-US  | <img src="./D4Companion/Images/Flags/esES.png"> | SDR (HDR off) with font set to small for the Spanish (LA) language          | ![Progress](https://progress-bar.dev/22/)  |
| 1440p_HSF_en     | <img src="./D4Companion/Images/Flags/enUS.png"> | HDR with font set to small for the English language                         | ![Progress](https://progress-bar.dev/2/)   |
| 1440p_SMF_en     | <img src="./D4Companion/Images/Flags/enUS.png"> | SDR (HDR off) with font set to medium for the English language              | ![Progress](https://progress-bar.dev/79/)  |
| 1600p_SMF_zh-CN  | <img src="./D4Companion/Images/Flags/zhCN.png"> | SDR (HDR off) with font set to medium for the Chinese (Simplified) language | ![Progress](https://progress-bar.dev/0/)   |
| 2160p_HSF_en     | <img src="./D4Companion/Images/Flags/enUS.png"> | HDR with font set to small for the English language.                        | ![Progress](https://progress-bar.dev/30/)  |

Each preset works for both normal and widescreen resolutions. e.g. for 2560x1440 and 3440x1440 use the 1440p preset.

Feel free to share you system presets with me so I can add them to the app.

See the following [wiki](https://github.com/josdemmers/Diablo4Companion/wiki/How-to-create-a-new-System-Preset) page to create your own.

## Usage

![Usage-1](./readme/readme-002.png)

1. Navigation menu. In the following order, Affixes, Logging, Debug, and Settings.
2. Change language for affixes.
3. Create, select, or delete affix presets. The import/export buttons can be used to share your builds, or to import builds from Maxroll. See [wiki](https://github.com/josdemmers/Diablo4Companion/wiki/How-to-import-and-export-builds) for more details.
4. Toggle the overlay on/off. Note: This is also possible using the ingame button in the top left corner.
5. Overview of selected affixes for each gear slot. Click to change color, or double click affix name to remove it.
6. Filter affixes.
7. Switch between affixes, aspects, and sigils.
8. This red warning icon means the image for the affix is missing.
9. Select which image(s) this affix should use.
10. Adds the affix to your preset so you can monitor it ingame.

![Usage-2](./readme/readme-003.png)

1. Set the width of the tooltip. Default for 1440p is 500. Recommended settings for other resolutions are listed when you download a system preset.
2. Threshold sliders for filtering out background noise. Defaults should be fine (60/255).
3. Similarity thresholds for matching images. A lower value means a closer match is required. Default of 0.05 is recommended.
4. Previous debug image.
5. Next debug image.

![Usage-3](./readme/readme-004.png)

1. Select the preset matching your resolution. See [wiki](https://github.com/josdemmers/Diablo4Companion/wiki/How-to-create-a-new-System-Preset) to create your own.
2. Reload the preset. Useful after adding new images without restarting the app.
3. The download manager can be used to download community created system presets. If your language or resolution is missing please send them to me and I'll add them to the list. Follow the recommended app settings in the description.
4. Hover your mouse over one of the info icons to get more detailed information about a setting.

## Troubleshooting

See [F.A.Q.](https://github.com/josdemmers/Diablo4Companion/wiki#frequently-asked-questions)

## Licensing

MIT

## Thirdparty packages

- [Emgu CV](https://www.emgu.com/wiki/index.php/Main_Page)
- [GameOverlay.Net](https://github.com/michel-pi/GameOverlay.Net)
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro)
- [NHotkey](https://github.com/thomaslevesque/NHotkey)
- [PInvoke](https://github.com/dotnet/pinvoke)
- [Prism](https://github.com/PrismLibrary/Prism)

## Community

### The Hidden Gaming Lair

- [Discord](https://th.gl/discord)
- [www](https://www.th.gl/)

## Mentions

- [d4data](https://github.com/blizzhackers/d4data)
- [maxroll.gg](https://maxroll.gg/d4/build-guides)
- [maxroll-d4-scraper](https://github.com/danparizher/maxroll-d4-scraper)

## Disclaimer

This app does not interact with Diablo IV, everything is done using image recognition. However use at your own risk.
