<p align="center">
  <img src="images/icon.png" alt="Office Viewer" width="96" />
</p>

<h1 align="center">Office Viewer</h1>

<p align="center">
  Office document viewer extension for VS Code with high-fidelity local rendering for <code>.docx</code>, <code>.xlsx</code>, and <code>.pptx</code> files. Modern, fast, fully local.
</p>

<p align="center">
  <img src="images/hero.png" alt="Office Viewer" style="max-width: 960px;" />
</p>

## Highlights

- **Fully offline and private.** Documents are rendered locally inside a sandboxed webview. Nothing is uploaded.
- **High-fidelity rendering.** Faithful reproduction of fonts, layouts, shapes, charts, and effects so documents look the way their authors intended.
- **Selectable text and clickable links.** Copy text out like on a web page, follow external hyperlinks, and jump between sheets in Excel.
- **Full-text search.** Case-sensitive and whole-word options across all pages. In Excel, search matches displayed values or underlying formulas, with cell addresses in results.
- **Multi-pane support.** Open the same file in split panes to compare different pages side by side.

## Supported formats

### Word

<p align="center">
  <img src="images/docx.png" alt="Word document open in VS Code" />
</p>

Headers and footers, comments, footnotes, endnotes, tracked changes, bookmarks, hyperlinks, table of contents, and math equations.

### PowerPoint

<p align="center">
  <img src="images/pptx.png" alt="PowerPoint deck open in VS Code" />
</p>

Shapes, SmartArt diagrams, charts, tables, and speaker notes. Continuous scroll or single-slide mode, plus a slide sorter grid view.

### Excel

<p align="center">
  <img src="images/xlsx.png" alt="Excel workbook open in VS Code" />
</p>

Merged cells, frozen panes, conditional formatting (data bars, color scales, icon sets), sparklines, formulas, cell comments, and built-in table styles.

## Smooth navigation

<p align="center">
  <img src="images/sidebar-outline.png" alt="Sidebar with page thumbnails and heading outline" />
</p>

- Toolbar with page navigation, jump-to-page, zoom in and out, and zoom presets (fit page, fit width, actual size, 50% to 400%).
- Sidebar with page thumbnails and a clickable heading outline.
- Keyboard and touch: arrow keys to flip pages, Ctrl/Cmd+F to search, swipe to navigate slides.

## Search anywhere

<p align="center">
  <img src="images/search.png" alt="Full-text search panel" />
</p>

Find text across every page or sheet with case-sensitive and whole-word options. Excel search can match either the displayed value or the underlying formula, and results include the cell address.

## Rendering details

- Embedded fonts and CJK fallbacks for correct Chinese, Japanese, and Korean text on any platform.
- Visual effects like gradients, shadows, glow, dashed strokes, and patterned fills.
- Page-on-demand rendering keeps large documents responsive while you scroll and zoom.
