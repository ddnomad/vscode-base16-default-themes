# Base16 Default Themes

Two restrained, readable VS Code themes based on Tinted Theming's Base16 Default themes:

- **Base16 Default Dark**
- **Base16 Default Light**

The themes keep the original Base16 syntax palette while refining the workbench UI with quieter surfaces, clearer secondary text, consistent blue focus outlines, neutral selections, cleaner tabs, and matching structural separators.

## Development

Open this repository in VS Code and press `F5` to start an Extension Development Host. Then use **Preferences: Color Theme** to select either theme.

To create a VSIX package:

```sh
npx @vscode/vsce package
```

## Attribution

The source themes are derived from [`tinted-theming/tinted-vscode`](https://github.com/tinted-theming/tinted-vscode) at commit `9b2f6345e65e243b951ae01f8e6918dfd7163eae`:

- [`base16-default-dark.json`](https://github.com/tinted-theming/tinted-vscode/blob/9b2f6345e65e243b951ae01f8e6918dfd7163eae/themes/base16/base16-default-dark.json)
- [`base16-default-light.json`](https://github.com/tinted-theming/tinted-vscode/blob/9b2f6345e65e243b951ae01f8e6918dfd7163eae/themes/base16/base16-default-light.json)

The Base16 Default scheme is by Chris Kempson. Tinted VSCode is distributed under the MIT License; its copyright notices are retained in this repository's license.
