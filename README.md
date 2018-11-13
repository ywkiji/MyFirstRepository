# MyFirstRepository
My First Description


First lets import all the required  libraries

'''
import pandas as pd
import urllib.request
import time
import datetime
import os
'''

Set our variables

'''
apikey = "ALPHAVANTAGEKEY"
root = "/data/S&P500 Data/" # download location of data from Alpha Vantage
output = "/data/S&P500 Data/" # output of joining download files
'''

Get a list of all the companies in the S&P500

'''
pathSP500 = "/data/S&P500 Data/SP500.csv"
dfSP500 = pd.read_csv(pathSP500)
'''

