<p align="center">
  <img src="images/icon.png" alt="Office Viewer" width="96" />
</p>

<h1 align="center">Office Viewer</h1>

<p align="center">
  Office document viewer extension for VS Code with high-fidelity local rendering for <code>.docx</code>, <code>.xlsx</code>, and <code>.pptx</code> files. Modern, fast, fully local.
</p>

<p align="center">
  <img src="images/hero.png" alt="Office Viewer rendering a PowerPoint deck inside VS Code with the thumbnail sidebar open" style="max-width: 960px;" />
</p>

## Highlights

- **Fully offline and private.** Documents are rendered locally inside a sandboxed webview. Nothing is uploaded.
- **High-fidelity rendering.** Faithful reproduction of fonts, layouts, shapes, charts, and effects so documents look the way their authors intended.
- **Selectable text and clickable links.** Copy text out like on a web page, follow external hyperlinks, and jump between sheets in Excel.
- **Full-text search.** Case-sensitive and whole-word options across all pages. In Excel, search matches displayed values or underlying formulas, with cell addresses in results.
- **Multi-pane support.** Open the same file in split panes to compare different pages side by side.

## Supported formats

### Word

<table>
  <tr>
    <td width="33%"><img src="images/docx-paper.png" alt="Academic paper demo" /></td>
    <td width="33%"><img src="images/docx-dash.png" alt="Report demo" /></td>
    <td width="33%"><img src="images/docx-recipe.png" alt="Recipe document" /></td>
  </tr>
</table>

Headers and footers, comments, footnotes, endnotes, tracked changes, bookmarks, hyperlinks, table of contents, and math equations.

### PowerPoint

<table>
  <tr>
    <td width="33%"><img src="images/pptx-chart.png" alt="Slide with a chart" /></td>
    <td width="33%"><img src="images/pptx-notes.png" alt="Slide with speaker notes panel open" /></td>
    <td width="33%"><img src="images/pptx-sorter.png" alt="Slide sorter grid view" /></td>
  </tr>
</table>

Shapes, SmartArt diagrams, charts, tables, and speaker notes. Continuous scroll or single-slide mode, plus a slide sorter grid view.

### Excel

<table>
  <tr>
    <td width="33%"><img src="images/xlsx-sales.png" alt="Sales workbook with charts and conditional formatting" /></td>
    <td width="33%"><img src="images/xlsx-expense.png" alt="Expense tracker" /></td>
    <td width="33%"><img src="images/xlsx-assets.png" alt="Asset register workbook" /></td>
  </tr>
</table>

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
