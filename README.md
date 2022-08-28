# ADS Project 1

All notebooks will run start to finish. Please run the notebooks in this order -
- `download_script`
- `preprocessing`
- `EDA`
- `modelling`

## Please note - Property data requires manual adjustment prior to running `preprocessing`
The property valuation data downloaded from the ___ includes some leading rows that provide context about the data. This is unnecessary and interferes with reading the excel file through pandas, so these rows must be deleted manually. To do this, you must:
- Run the download script in `download_script` to get the files on your machine
- Open the first property file (named after one of NYC's 5 boroughs)
- Select the first 4 rows of the Excel spreadsheet by clicking, holding and dragging down from the `1` to the `4` on the left
- Right click the selection you just made and click `Delete`
- Save the file with `CTRL + S`
- Repeat for the other borough files
