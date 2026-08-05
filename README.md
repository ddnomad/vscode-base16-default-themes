Base16 Default Themes for VS Code
=================================

[![VS Code Marketplace Version](https://vsmarketplacebadges.dev/version-short/ddnomad.vscode-base16-default-themes.svg?style=flat-square&logo=vscodium&logoColor=white&labelColor=0078d4&color=0078d4)](https://marketplace.visualstudio.com/items?itemName=ddnomad.vscode-base16-default-themes)
[![Open VSX Version](https://img.shields.io/open-vsx/v/ddnomad/vscode-base16-default-themes?style=flat-square&logo=eclipseide&logoColor=white&label=Open%20VSX&labelColor=555&color=ea7233)](https://open-vsx.org/extension/ddnomad/vscode-base16-default-themes)

An opinionated, more minimal take on Base16 Default Dark and Light themes for VS Code.

This extension provides the following themes:

- **Base16 Default Dark**
- **Base16 Default Light**

Development
-----------

Open this repository in VS Code and press `F5` to start an Extension Development Host. Then use **Preferences: Color Theme** to select either theme.

To create a VSIX package locally:

```sh
npx @vscode/vsce package
```

Release
-------

Releases are built automatically when a semver tag is pushed. The GitHub Actions workflow validates the tag, checks that it matches `package.json`, packages a `.vsix`, and attaches it to a GitHub Release.

1. Bump `version` in `package.json`.
2. Move entries from `[Unreleased]` to a new version section in `CHANGELOG.md`.
3. Commit and push to `main`.
4. Tag the release (the tag must match `package.json`, with a `v` prefix):

```sh
git tag v0.1.0
git push origin v0.1.0
```

The workflow runs on tags matching `v*.*.*` (for example `v0.1.0` or `v1.0.0-beta.1`). If the tag is not valid semver, or its version does not match `package.json`, the release fails.

To publish to the VS Code Marketplace:

```sh
vsce login ddnomad
vsce publish
```

Attribution
-----------

The source themes are derived from [`tinted-theming/tinted-vscode`](https://github.com/tinted-theming/tinted-vscode) at commit `9b2f6345e65e243b951ae01f8e6918dfd7163eae`:

- [`base16-default-dark.json`](https://github.com/tinted-theming/tinted-vscode/blob/9b2f6345e65e243b951ae01f8e6918dfd7163eae/themes/base16/base16-default-dark.json)
- [`base16-default-light.json`](https://github.com/tinted-theming/tinted-vscode/blob/9b2f6345e65e243b951ae01f8e6918dfd7163eae/themes/base16/base16-default-light.json)

The Base16 Default scheme is by Chris Kempson. Tinted VSCode is distributed under the MIT License; its copyright notices are retained in this repository's license.
