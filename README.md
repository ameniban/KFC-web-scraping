# KFC-web-scraping
##1 KFC Tunisia's website : https://kfc.com.tn/#wbProdCat-10_tab
#1st Step : import and install the needed librairies : 
BeautifulSoup : !pip install BeautifulSoup
from bs4 import BeautifulSoup
Requests: !pip install requests
import requests
csv : import csv 
datetime: import datetime
time: import time

#the desired result:
Create a csv (Comma-Seperated-Value) file that contains the current date, the name and the price of the meal.
we want the file to be generated every thirty seconds in case there's  a change in the price of the meal.

##Important: Once you download the csv file, please make sure you check the separator before you open the file on EXCEL because if changes from a region to another. I had to change the seperator from ';' to ',' in my computer settings.
For more information, please check this Link: https://www.exceldemy.com/how-to-change-comma-separator-in-excel/#:~:text=7%20Easy%20Methods%20to%20Change%20Comma%20Separator%20in,7%207.%20Applying%20Text%20to%20Columns%20Feature%20 
