# Sheets

An Excel-style spreadsheet that runs in the browser.

**Live:** https://orhava.github.io/office-sheets/

## Features
- Formula engine with 100+ functions: SUM, AVERAGE, IF/IFS/IFERROR, SUMIF(S), COUNTIF(S), VLOOKUP/HLOOKUP/XLOOKUP, INDEX/MATCH, text functions, date functions (TODAY, DATE, EDATE, NETWORKDAYS…), financial (PMT, FV, PV, NPV), statistics (MEDIAN, STDEV, RANK, LARGE…), cross-sheet references (`Sheet2!A1`), named ranges, `%`, `&`, `^`, comparison operators, circular-reference detection
- Fill handle (series & formula autofill), fill down/right, cut/copy/paste with relative-reference adjustment, paste values, paste from Excel/Google Sheets (TSV)
- Insert/delete rows & columns (formulas adjust), resize rows/columns, auto-fit, freeze panes, merge cells, wrap text
- Number formats (number, integer, percent, $ ₪ € currency, date, text), decimals, fonts, bold/italic/underline/strike, colors, borders, alignment
- Conditional formatting (greater/less/equal/contains, color scale, data bars), data validation dropdowns, checkboxes, cell notes
- Sort A→Z/Z→A (auto-detects header), filter rows, remove duplicates, trim whitespace
- Charts (bar, line, area, pie) that live-update, drag & resize, export SVG
- **AI assistant** (your own Anthropic/OpenAI key): formulas from plain words, explain a formula, clean data, insights, generate tables — results applied straight into cells
- Pivot tables, multi-column sort, split text to columns, paste transposed, goal seek, freeze at any cell, protect sheet, import CSV from URL, column statistics
- Dynamic arrays that spill: FILTER, SORT, UNIQUE, SEQUENCE, TRANSPOSE; SPARKLINE mini-charts in cells; HYPERLINK; MAXIFS/MINIFS/AVERAGEIFS, DATEDIF, IRR, RATE, NPER…
- Formula autocomplete while typing, colored highlighting of referenced cells, click cells to insert references into a formula
- Multiple sheets per file, multiple files, autosave, undo/redo, find & replace, keyboard navigation like Excel, context menus, dark mode, RTL
- Open `.xlsx` / `.csv` / `.tsv`; download as **Excel (.xlsx)** with formulas and number formats, CSV, or JSON

Part of the office suite: [office-writer](https://github.com/OrHava/office-writer) · [office-slides](https://github.com/OrHava/office-slides) · [office-sheets](https://github.com/OrHava/office-sheets) · [office-mail](https://github.com/OrHava/office-mail)
