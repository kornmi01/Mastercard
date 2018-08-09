# Post Undergraduate Salaries

The data to show which colleges and univerisites offer their graduates the highest pay upon graduating.

#Post-Grad Salaries

import pandas as pd

import xlrd

pip install xlrd

import pandas as pd

file = 'salaries.csv'

xl = pd.ExcelFile(file)

print(xl.sheet_names)

df1 = xl.parse('Sheet1')
