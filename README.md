# remove-duplicates

import xlrd
import openpyxl
import pandas

import pandas as pd
data = pd.read_excel(r"C:\Users\HondaUser.KPIT\Documents\Remove_Duplicates\KPIT-OTA1-TJBX_Planning _and_Execution_Report.xlsx", sheet_name= "Onsite-BNE426", usecols= 'E')
df = data.drop_duplicates(keep = False)
print(df)

