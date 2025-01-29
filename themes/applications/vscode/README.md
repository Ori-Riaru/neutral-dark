# VSCode/VSCodium Theme

## Preview

TODO: Add preview

## Installation

1. Copy the contents from `settings.json` to into your VSCode/VSCodium settings

```json
{
  // ...
  // Your previous settings

  // Copied from settings.json
  "vscode_custom_css.imports": [
    "file:///C:/Users/MyUserName/Documents/custom.css"
  ]

  "workbench.colorCustomizations": {
    "activityBar.foreground": "#ffffff",
    "activityBarBadge.background": "#a386ff",
  // Remainder copied settings
  // ...
}
```
2. install the vscode extension [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)

3. Download `custom.css` and place it at any location

4. Modify `"vscode_custom_css.imports"` in your settings.json to point to the location you placed `custom.css`

## Notes

Currently this theme uses vscode settings to set the colors. In the future it would be better to create a proper theme or do everything using `custom.css`
