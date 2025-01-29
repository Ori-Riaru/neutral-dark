# Neutral Dark (WIP)

`Disclaimer`: Neutral dark is WIP <span style="color: #fe5970"> Themes may be broken or incomplete </span>, extensive testing has not been performed. If you find a bug please fix it and submit a pull request.

## About

Neutral Dark is design guideline and theme library. It provides a sleek appearance with a card based layout, neutral background and vibrant colors.

## Preview

TODO: Update vscode preview to reflect syntax highlighting
![vscode-preview](./.github/preview.png)

## Specifications

Some themes may not implement all specifications either because the theme is incomplete or the application does not support advanced customizations.

### Fonts

| Type      | Font                                               |
| --------- | -------------------------------------------------- |
| UI        | [Inter](https://fonts.google.com/specimen/Inter)   |
| Monospace | [JetBrainMono](https://www.jetbrains.com/lp/mono/) |

### Spacing and layout

| Property | Value | Description                |
| -------- | ----- | -------------------------- |
| `gap`    | 5px   | Gap Between Major Sections |
| `radius` | 8px   | Radius of Cards            |

### Color Palette

| Color              | Hex                                                                                                      | Swatch                                                       | Usage                                                             |
| ------------------ | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------- |
| Text               |
| `Text`             | <div style="color: white; background-color: #111111; padding: 15px; border-radius: 6px ">#ffffff</div>   | ![Text](./.github/swatches/text.png)                         | Basic text, Headers                                               |
| `Subtext`          | <div style="color: #aaaaaa; background-color: #111111; padding: 15px; border-radius: 6px ">#aaaaaa</div> | ![Subtext](./.github/swatches/subtext.png)                   | Subtext, Placeholder, Comments                                    |
| `Hidden`           | <div style="color: #606060; background-color: #111111; padding: 15px; border-radius: 6px ">#606060</div> | ![Hidden](./.github/swatches/hidden.png)                     | Disabled, Hidden                                                  |
| Backgrounds        |
| `base`             | <div style="color: white; background-color: #000000; padding: 15px; border-radius: 6px ">#000000</div>   | ![Base](./.github/swatches/base.png)                         | Window backgrounds                                                |
| `section`          | <div style="color: white; background-color: #111111; padding: 15px; border-radius: 6px ">#111111</div>   | ![Section](./.github/swatches/section.png)                   | Major Section, Content Only Window                                |
| `card`             | <div style="color: white; background-color: #181818; padding: 15px; border-radius: 6px ">#181818</div>   | ![Card](.github/swatches/card.png)                           | Card, Input, Semihighlighted button                               |
| `overlay`          | <div style="color: white; background-color: #222222; padding: 15px; border-radius: 6px ">#222222</div>   | ![Overlay](./.github/swatches/overlay.png)                   | Search Overlay,                                                   |
| Customizations     |
| `accent`           | <div style="color: white; background-color: #a386ff; padding: 15px; border-radius: 6px ">#a386ff</div>   | ![Accent](./.github/swatches/accent.png)                     | Custamizable Primary Accent                                       |
| `accent-secondary` | <div style="color: white; background-color: #83bbff; padding: 15px; border-radius: 6px ">#83bbff</div>   | ![Accent-Secondary](./.github/swatches/accent-secondary.png) | Customization Secondary Accent                                    |
| `accent-tertiary`  | <div style="color: black; background-color: #fefb77; padding: 15px; border-radius: 6px ">#fefb77</div>   | ![Accent-Tertiary](./.github/swatches/accent-tertiary.png)   | Customization Tertiary Accent                                     |
| Colors             |
| `Red`              | <div style="color: white; background-color: #fe5970; padding: 15px; border-radius: 6px ">#fe5970</div>   | ![Red](./.github/swatches/red.png)                           | Error, Remove, Close, Delete, Tags (HTML/XML), Annotations        |
| `Orange`           | <div style="color: white; background-color: #ffa062; padding: 15px; border-radius: 6px ">#ffa062</div>   | ![Orange](./.github/swatches/orange.png)                     | Warning, Numbers                                                  |
| `Yellow`           | <div style="color: black; background-color: #fefb77; padding: 15px; border-radius: 6px ">#fefb77</div>   | ![Yellow](./.github/swatches/yellow.png)                     | Info, Help                                                        |
| `Green`            | <div style="color: black; background-color: #99ff82; padding: 15px; border-radius: 6px ">#99ff82</div>   | ![Green](./.github/swatches/green.png)                       | Strings                                                           |
| `Teal`             | <div style="color: black; background-color: #80ffc1; padding: 15px; border-radius: 6px ">#80ffc1</div>   | ![Teal](./.github/swatches/teal.png)                         | Success, New, Add,                                                |
| `Cyan`             | <div style="color: black; background-color: #7ef8fe; padding: 15px; border-radius: 6px ">#7ef8fe</div>   | ![Cyan](./.github/swatches/cyan.png)                         | Attributes, Properties (HTML/CSS/JSX)                             |
| `Blue`             | <div style="color: white; background-color: #83bbff; padding: 15px; border-radius: 6px ">#83bbff</div>   | ![Blue](./.github/swatches/blue.png)                         | Neutral, Function Names, Declarations                             |
| `Purple`           | <div style="color: white; background-color: #a386ff; padding: 15px; border-radius: 6px ">#a386ff</div>   | ![Purple](./.github/swatches/purple.png)                     | Modified, Change, Edit, Keywords, Reserved Words, Important Terms |
| `Pink`             | <div style="color: black; background-color: #fe99fe; padding: 15px; border-radius: 6px ">#fe99fe</div>   | ![Pink](./.github/swatches/pink.png)                         | Operators (+, -, \*, etc.)                                        |
| `White`            | <div style="color: black; background-color: #ffffff; padding: 15px; border-radius: 6px ">#ffffff</div>   | ![White](./.github/swatches/white.png)                       |                                                                   |
| `Black`            | <div style="color: white; background-color: #000000; padding: 15px; border-radius: 6px ">#000000</div>   | ![Black](./.github/swatches/black.png)                       |                                                                   |

### Additional Options

Some themes may have additional options such as layout changes, colors, etc. If a theme has additonal option they will be listed in the theme's `README.md` file.

## Usage

Search the themes folder for your desired application or website. Once you have found it follow the instilation instructions in the README.md file. If your application is not list consider making a theme and submitting a pull request.

### NixOS

If your using nixos check out my [nix configs](https://github.com/RiaruAzaki/nix-configs) which comes with application themed with neutral dark.
