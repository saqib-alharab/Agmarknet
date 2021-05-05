The Code I have Submitted is best suited to Run in Jupyter Notebook Environment

For The Coding Part I Havent used Web Scraping Because In the agmarknet website itself there is a direct option for Import to excel (have attached th sc below for this) So I have used that , However the exported file is in the Format of XLS its little bit nuance to read the xls file in python  you need to install a Seperate Package Called XLRD So I Have Just Coverted The Data to XLSX By Simply Copying the Data into an XlSX File

Anyhow If You Want it in XLS Format Follow the Steps

install it using command prompt

pip install xlrd

Then Code

1_import xlrd

2_import pandas as pd

3_xls = pd.ExcelFile(r"yourfilename.xls") #use r before absolute file path 

Remaining I Have Answered the Questions in Word File (also commented steps in jupyter notebook for better understanding)

**Link For Excel File Used in Analysis : https://drive.google.com/file/d/1hCmh8RGuHjewIJk_Rt1kJEzZscIaNNgi/view?usp=sharing**


![Screenshot (101)_LI](https://user-images.githubusercontent.com/75921135/117129789-c4ac1180-adbc-11eb-8d2b-1968b125c7b7.jpg)
