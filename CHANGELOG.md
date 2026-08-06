Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[Unreleased]
------------

### Added

- Aligned [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) current-query highlighting with both theme palettes.

### Changed

- Reorganised both theme definitions into matching, documented sections and aligned their supported workbench colour keys.

### Fixed

- Balanced dark-theme insertion and deletion backgrounds so changes remain equally prominent without obscuring muted syntax such as comments.

[v0.1.1] - 2026-08-06
--------------------

### Added

- Shield badges in the README linking to the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=ddnomad.vscode-base16-default-themes) and [Open VSX](https://open-vsx.org/extension/ddnomad/vscode-base16-default-themes) extension listings.
- Local packaging and installation commands for test-driving unpublished builds in Cursor or VS Code, alongside the live Extension Development Host preview workflow.
- Palette-aligned colours for [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) diagnostics and status bar indicators in both themes.

### Changed

- Refreshed the extension icon with a transparent background and a Base16 spectrum keyline.

### Fixed

- Reduced the visual prominence of inline type hints, parameter hints, and CodeLens annotations in both themes.
- Improved workspace section header contrast in both themes.
- Improved inactive editor tab contrast in the dark theme, particularly in Cursor.

[v0.1.0] - 2026-08-04
--------------------

Initial release.

[Unreleased]: https://github.com/ddnomad/vscode-base16-default-themes/compare/v0.1.1...HEAD
[v0.1.1]: https://github.com/ddnomad/vscode-base16-default-themes/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/ddnomad/vscode-base16-default-themes/releases/tag/v0.1.0
