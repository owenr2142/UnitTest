import unittest
import datetime

#symbol

symbol = input("Enter Symbol: ")
if symbol.isalpha() == True and len(symbol) == 7 and symbol.isupper() == True:
    print("Valid Symbol")
else:
    print("Invalid Symbol")

#Chart Type
try:
    chart_type = int(input("Enter Chart Type: "))
    if chart_type == 1 or chart_type == 2:
        print("Valid Chart Type")
    else:
        print("Invalid Chart Type")
except ValueError:
    print("Invalid Chart Type")

#Time Series
try:
    time_series = int(input("Enter Time Series: "))
    if time_series > 0 and time_series < 5:
        print("Valid Time Series")
    else:
        print("Invalid Time Series")
except ValueError:
    print("Invalid Time Series")

#Start Date
date_string1 = input("Enter start date in format YYYY-MM-DD: ")
date_format = '%Y-%m-%d'

try:
    date_obj = datetime.datetime.strptime(date_string1, date_format)
    print("Valid date format")
except ValueError:
    print ("Invalid date format, please enter using the proper date format YYYY-MM_DD: ")

#End Date
date_string2 = input("Enter start date in format YYYY-MM-DD: ")
date_format = '%Y-%m-%d'

try:
    date_obj = datetime.datetime.strptime(date_string2, date_format)
    print("Valid date format")
except ValueError:
    print ("Invalid date format, please enter using the proper date format YYYY-MM_DD: ")

