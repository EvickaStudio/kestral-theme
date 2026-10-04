# Kestral Theme

A pair of Visual Studio Code themes with salmon-pink and lavender accents, neutral backgrounds, and the familiar syntax colors of Dark+ and Light+.

![Kestral Dark and Kestral Light in VS Code, separated by a diagonal salmon-pink slash](https://raw.githubusercontent.com/EvickaStudio/kestral-theme/v0.0.4/assets/kestral-preview.webp)

## Features

- Dark and light variants that retain Kestral's original Dark+ / Light+ foundations
- Salmon-pink accents: `#d99aa5` in Dark and a deeper `#a34f68` in Light
- Lavender selections, focus indicators, and links
- Coordinated tabs, completion menus, search matches, Git decorations, and diagnostics
- Existing syntax and semantic highlighting inherited from the bundled Plus themes

## Installation

1. Open **Extensions** sidebar in VS Code (`Ctrl+Shift+X` or `Cmd+Shift+X`)
2. Search for `Kestral Theme`
3. Click **Install**
4. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
5. Select **Preferences: Color Theme** and choose either **Kestral Dark** or **Kestral Light**

You can also install directly from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=evickastudio.kestral).

## Screenshots

The combined preview above uses real VS Code screenshots. Open either full-size image for a closer look:

- [Kestral Dark](https://raw.githubusercontent.com/EvickaStudio/kestral-theme/v0.0.4/assets/kestral-dark.webp)
- [Kestral Light](https://raw.githubusercontent.com/EvickaStudio/kestral-theme/v0.0.4/assets/kestral-light.webp)

## Development

The workbench colors live in the two Kestral theme files. Syntax highlighting is inherited from the bundled `dark_plus.json` and `light_plus.json` files, based on the [VS Code default themes](https://github.com/microsoft/vscode/tree/main/extensions/theme-defaults/themes).

If you want to contribute:

1. Clone the repository
2. Make your changes to `themes/kestral-dark-color-theme.json` or `themes/kestral-light-color-theme.json`
3. Press `F5` to open a new window with your extension loaded
4. Open the Color Theme picker with `File > Preferences > Theme > Color Theme`
5. Test your changes and submit a pull request

## Feedback and Issues

If you find any issues or have suggestions for improvements, please [open an issue](https://github.com/EvickaStudio/kestral-theme/issues) on GitHub.

## License

This theme is released under the [MIT License](LICENSE).
