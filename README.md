# Dofoerix' Prompt Theme

[Oh My Posh](https://github.com/JanDeDobbeleer/oh-my-posh) theme that was created to make prompt more beautiful and convenient

## Usage

1. Install Oh My Posh for your system ([Windows](https://ohmyposh.dev/docs/installation/windows), [macOS](https://ohmyposh.dev/docs/installation/macos), [Linux](https://ohmyposh.dev/docs/installation/macos))
2. Clone this repository or download one of configuration file to any folder
3. Set theme using [this guide](https://ohmyposh.dev/docs/installation/customize#config-syntax)

   Replace `~/jandedobbeleer.omp.json` in the command with path to any variant of this theme (for example: `~/any-folder/Dfrx-Prompt-Theme/gray/full_no_tr.omp.json`)

   Also you can use a URL to raw file on GitHub instead of path (for example: `https://raw.githubusercontent.com/Dofoerix/Dfrx-Prompt-Theme/main/gray/full_no_tr.omp.json`)

## Variations

### According to the colors

Name of the folder with configuration files

#### Gray

![gray](./screenshots/gray.png)

### According to the segments

`full`/`standard`/`light` in the name of the config file

#### Full

![full](./screenshots/full.png)

- Current user
- Current folder 
- Git (shown when in a git repo)
- Execution Time
- Exit (broken heart if exit code != 0)
- Root (shown if current user is root)
- Time

#### Standard

![standard](./screenshots/standard.png)

- Current folder 
- Git (shown when in a git repo)
- Execution Time
- Exit (broken heart if exit code != 0)
- Root (shown if current user is root)
- Time (minutes and seconds if prompt is transient)

#### Light

![light](./screenshots/light.png)

- Current folder
- Execution Time
- Exit (broken heart if exit code != 0)
- Root (shown if current user is root)
- Time (minutes and seconds if prompt is transient)

### According to transient prompt

`no_tr` in the name of the config file means this feature disabled in this variant

More about transient prompt can be found [here](https://ohmyposh.dev/docs/configuration/transient)
