# Neutral Dark (WIP)

`Disclaimer`: Neutral dark is WIP <span style="color: #fe5970"> Themes may be broken or incomplete </span>, extensive testing has not been performed. If you find a bug please fix it and submit a pull request.

## About

Neutral Dark is design guideline and theme library. It provides a sleek appearance with a card based layout, neutral background and vibrant colors.

## Preview

TODO: Add preview

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

| Color              | Hex                                                                                                      | Usage                                                             |
| ------------------ | -------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Text               |
| `Text`             | <div style="color: white; background-color: #111111; padding: 15px; border-radius: 6px ">#ffffff</div>   | Basic text, Headers                                               |
| `Subtext`          | <div style="color: #aaaaaa; background-color: #111111; padding: 15px; border-radius: 6px ">#aaaaaa</div> | Subtext, Placeholder, Comments                                    |
| `Hidden`           | <div style="color: #606060; background-color: #111111; padding: 15px; border-radius: 6px ">#606060</div> | Disabled, Hidden                                                  |
| Backgrounds        |
| `base`             | <div style="color: white; background-color: #000000; padding: 15px; border-radius: 6px ">#000000</div>   | Window backgrounds                                                |
| `section`          | <div style="color: white; background-color: #111111; padding: 15px; border-radius: 6px ">#111111</div>   | Major Section, Content Only Window                                |
| `card`             | <div style="color: white; background-color: #181818; padding: 15px; border-radius: 6px ">#181818</div>   | Card, Input, Semihighlighted button                               |
| `overlay`          | <div style="color: white; background-color: #222222; padding: 15px; border-radius: 6px ">#222222</div>   | Search Overlay,                                                   |
| Customizations     |
| `accent`           | <div style="color: white; background-color: #a386ff; padding: 15px; border-radius: 6px ">#a386ff</div>   | Custamizable Primary Accent                                       |
| `accent-secondary` | <div style="color: white; background-color: #83bbff; padding: 15px; border-radius: 6px ">#83bbff</div>   | Customization Secondary Accent                                    |
| `accent-tertiary`  | <div style="color: black; background-color: #fefb77; padding: 15px; border-radius: 6px ">#fefb77</div>   | Customization Tertiary Accent                                     |
| Colors             |
| `Red`              | <div style="color: white; background-color: #fe5970; padding: 15px; border-radius: 6px ">#fe5970</div>   | Error, Remove, Close, Delete, Tags (HTML/XML), Annotations        |
| `Orange`           | <div style="color: white; background-color: #ffa062; padding: 15px; border-radius: 6px ">#ffa062</div>   | Warning, Numbers                                                  |
| `Yellow`           | <div style="color: black; background-color: #fefb77; padding: 15px; border-radius: 6px ">#fefb77</div>   | Info, Help                                                        |
| `Green`            | <div style="color: black; background-color: #99ff82; padding: 15px; border-radius: 6px ">#99ff82</div>   | Strings                                                           |
| `Teal`             | <div style="color: black; background-color: #80ffc1; padding: 15px; border-radius: 6px ">#80ffc1</div>   | Success, New, Add,                                                |
| `Cyan`             | <div style="color: black; background-color: #7ef8fe; padding: 15px; border-radius: 6px ">#7ef8fe</div>   | Attributes, Properties (HTML/CSS/JSX)                             |
| `Blue`             | <div style="color: white; background-color: #83bbff; padding: 15px; border-radius: 6px ">#83bbff</div>   | Neutral, Function Names, Declarations                             |
| `Purple`           | <div style="color: white; background-color: #a386ff; padding: 15px; border-radius: 6px ">#a386ff</div>   | Modified, Change, Edit, Keywords, Reserved Words, Important Terms |
| `Pink`             | <div style="color: black; background-color: #fe99fe; padding: 15px; border-radius: 6px ">#fe99fe</div>   | Operators (+, -, \*, etc.)                                        |
| `White`            | <div style="color: black; background-color: #ffffff; padding: 15px; border-radius: 6px ">#ffffff</div>   |                                                                   |
| `Black`            | <div style="color: white; background-color: #000000; padding: 15px; border-radius: 6px ">#000000</div>   |                                                                   |

### Additional Options

Some themes may have additional options such as layout changes, colors, etc. If a theme has additonal option they will be listed in the theme's `README.md` file.

## Usage

Search the themes folder for your desired application or website. Once you have found it follow the instilation instructions in the README.md file. If your application is not list consider making a theme and submitting a pull request.

### NixOS

If your using nixos check out my [nix configs](https://github.com/RiaruAzaki/nix-configs) which comes with application themed with neutral dark.
