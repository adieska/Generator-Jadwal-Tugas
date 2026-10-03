## 2025-05-18 - Excel Formula Injection (CSV/XLSX Injection)
**Vulnerability:** User-controlled schedule inputs (host names, addresses, role assignments, notes) exported to Excel could contain leading formula characters (`=`, `+`, `-`, `@`, `\t`, `\r`), causing spreadsheet applications to execute arbitrary commands or DDE functions upon opening the generated file.
**Learning:** Client-side spreadsheet export tools like SheetJS (`xlsx`) pass raw string values directly into sheet cells. If user input begins with formula characters, Excel evaluates them automatically.
**Prevention:** Always prepend a single quote `'` to any string cell value starting with `=`, `+`, `-`, `@`, `\t`, or `\r` before passing data to spreadsheet exporters.
