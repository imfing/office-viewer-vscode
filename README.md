# Office Viewer for VS Code

Office document viewer extension for VS Code with high-fidelity local rendering for `.docx`, `.xlsx`, and `.pptx` files. Modern, fast, fully local.

This repository hosts releases and issue tracking for the extension. The extension's source code is closed.

## Install

Install from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=imfing.office-viewer), or with the command line:

```sh
code --install-extension imfing.office-viewer
```

A signed `.vsix` is also attached to each [GitHub Release](https://github.com/imfing/office-viewer-vscode/releases) for offline or air-gapped installation:

```sh
code --install-extension office-viewer-X.Y.Z.vsix
```

## Highlights

- **Fully offline and private.** Documents are rendered locally inside a sandboxed webview. Nothing is uploaded.
- **High-fidelity rendering.** Faithful reproduction of fonts, layouts, shapes, charts, and effects so documents look the way their authors intended.
- **Selectable text and clickable links.** Copy text out like on a web page, follow external hyperlinks, and jump between sheets in Excel.
- **Full-text search.** Case-sensitive and whole-word options across all pages. In Excel, search matches displayed values or underlying formulas, with cell addresses in results.
- **Multi-pane support.** Open the same file in split panes to compare different pages side by side.

See the [Marketplace listing](https://marketplace.visualstudio.com/items?itemName=imfing.office-viewer) for the full feature list and screenshots.

## Reporting issues

Found a bug or a rendering glitch? Please [open an issue](https://github.com/imfing/office-viewer-vscode/issues/new/choose) with:

- The file format (`.docx` / `.pptx` / `.xlsx`)
- A minimal sample file if possible
- Your VS Code version and operating system
- A screenshot or short clip of the problem

Feature requests and questions are welcome too.

## License

See [LICENSE](./LICENSE). Free for personal and non-commercial use; commercial use requires a separate agreement.
