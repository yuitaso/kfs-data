# kfs-data

Static JSON data published for the kfs_hp site's schedule embeds, served via
[jsDelivr](https://www.jsdelivr.com/) instead of hitting Google Apps Script
on every page view.

Files under `data/` are overwritten by a Google Apps Script (in the
`kfs_hp` project's Sheets, triggered manually from a custom menu) whenever
the source spreadsheet is updated. Don't edit them by hand — changes will
be overwritten on the next update.

- `data/summer.json` — green (summer) schedule data
