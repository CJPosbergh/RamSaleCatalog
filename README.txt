RAM SALE ONLINE CATALOG - how to host and update
================================================

This folder is the whole website:
  index.html        the catalog page (don't need to edit it)
  catalog.xlsx      the sale order spreadsheet the page reads
  percentiles.xlsx  breed percentile cutoffs for the top 5/10/20% highlights (optional)

PUT IT ONLINE (pick one)
  - Your existing website host (e.g. the association site): upload both files to one folder.
  - GitHub Pages (free): create a repository, upload both files, Settings > Pages > deploy from main.
  - Netlify Drop (free): drag this folder onto app.netlify.com/drop.
  Note: opening index.html by double-clicking it on your computer won't load the spreadsheet;
  it has to be served from a web address.

UPDATE THE CATALOG
  Edit the spreadsheet, save it as catalog.xlsx, and replace the old file on the host.
  Buyers see the change the next time they load or refresh the page. Nothing else to do.

  Before uploading, you can check a new spreadsheet with "Preview a spreadsheet..." at the
  bottom of the page. Only you see the preview.

SUBSTITUTIONS AND SCRATCHES (see the "How to update" sheet in the workbook)
  Status column:  SUB   = substitution (yellow SUBSTITUTE tag + changes banner)
                  OUT   = out of sale (hidden unless buyers choose to see it)
                  SOLD  = sold (add Price / Buyer columns if you want those shown)
  Replaces Tag:   original ram's tag, for substitutions
  Status Note:    any explanation you want buyers to see
  Typing OUT OF SALE in the Breed column (as the sheet already does) also works.

  Lot 1 carries an EXAMPLE substitution - clear its Status, Replaces Tag and Status Note cells.

BREED RANK HIGHLIGHTS (top 5 / 10 / 20%)
  percentiles.xlsx is the NSIP EBV percentile table (Aug 2026): one tab per breed (Targhee,
  Rambouillet, Suffolk), a Percentile column (100, 99 ... 95, 90, 80 ... 0) and one column
  per EBV. The page uses the 95 / 90 / 80 rows as the top 5 / 10 / 20% cutoffs. When NSIP
  publishes new tables, save them under this name and replace the file. Each EBV on the page is
  then colored by tier (pink top 5%, blue top 10%, green top 20% -
  the same colors as the printed sale catalogue), and buyers can filter to rams in the top 5/10/20% of their breed.
  Update it once a year when new tables come out. Leave it blank (or delete it) to turn
  the highlighting off. See the "How to fill" tab.

RECORDING PRICES ON SALE DAY
  Each lot has a price-per-head box and a buyer box. Pens of 2 (e.g. 54A/54B) share one
  price; the lot total is price x head. The running total shows at the top, and the
  Results view summarizes by breed, consignor, section and buyer.
  Prices are saved only in the browser where you type them (not in the spreadsheet and
  not visible to buyers). Use "Copy for Excel" or "Download CSV" in Results to keep them.
  A Price / Buyer column in catalog.xlsx, if present, fills the boxes as a starting value.

KEEP SCREEN ON (phones and tablets)
  The "Keep screen on" button stops the device from dimming or locking while the page is
  open. It needs the site to be on https (GitHub Pages, Netlify and most hosts are) and a
  current browser: Chrome/Android, or Safari on iPhone/iPad with iOS 16.4 or later.
  If the phone is locked by hand or you switch apps, it turns back on when you return.
  Low Power Mode on iPhone can still dim the screen.

COLUMNS
  Headers are matched by name, so you can reorder columns or add sheets. Any sheet with a
  "Lot #" header is included. A new numeric column (a new trait) appears online automatically.
