# Sneaker-Sale-Uploader

This program is designed to allow imports of sales exported from ecommerce platforms StockX and GOAT Group into a Google Sheets spreadsheet for tax and bookkeeping purposes. A version of the spreadsheet format intended for use with this program is available [here](https://docs.google.com/spreadsheets/d/1O1RHGqKlPKzBL-8SvFyYYg16RxQCSN6y09q-5giCICE/edit#gid=378756784). This is a heavily modified version of a spreadsheet originally provided by [thesnkrbible](https://www.thesnkrbible.com/free-content-main/sales-tracking-and-profit-monitoring-with-included-spreadsheet). Two example data .xlsx spreadsheets are provided if you would like a live demonstration of the program. **Please note that any exported spreadsheets from StockX or Goat Group must first be converted from .csv format to .xlsx format.**

<p>This importer program automatically calculates whether a product has reached the minimum sales fee threshold of $7 on StockX for more accurate tracking of total fees incurred on the platform. However, these sales will still show up as Cash/Gift which reflects no seller fee. This will be improved in a later update. </p>



<p> 
This program is still in a draft phase. Among opther things, you must manually edit the Python code to insert your spreadsheet ID, Google Sheets authentication token in order to access the Google Sheets API, the path of the StockX and GOAT Group exported spreadsheets, and also your seller fee percentage per month on StockX. Currently, I am refactoring the code into Go and improving the end user experience for easier usage. I will also be improving the import speeds by leveraging proper use of Google Sheets' API to import more than one sale at a time. 
</p>
