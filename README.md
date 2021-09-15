# Excel-Sheets-Merger

#### Hey so this is 4 Lines of code which will help us to merge the sheets which are in same excel sheet 

How to Combine Lot's of same data of differnt sheets in just a minute ? 

**Step 1**
- `import pandas as pd`

**Step 2**
- `df = pd.concat(pd.read_excel('Excel sheet name.xlsx', sheet_name=None), ignore_index=True)`
- This is where you have to change the Excel sheet name only*

**Step 3**
- `df`
- This will show the total rows and data view

**Step 4**
- `df.to_excel("output.xlsx")`
- This will convert all sheets of single file [ Sheet1, Sheet2, ..... N Sheets] into Single Sheet named as Output.xlsx[Excel File]
