import json
import urllib
import requests
import pandas as pd
from json import JSONEncoder
import csv, openpyxl
import numpy as np
import time
import numpy as np
import os
import datetime
import xlrd
import sys
from xlrd import open_workbook
import xlsxwriter
import smtplib
import logging
from email.mime.text import MIMEText
from email.mime.multipart import MIMEMultipart
from email.header import Header
from email.mime.base import MIMEBase
from email import encoders

with open('Info.json') as o:
	data_json = json.load(o)

url = 'https://XXXXXXX/api/v1/data/XXXXXXformat=json'

x = requests.get(url, auth=(data_json["USERNAME"], data_json["PASSWD"]))
t = json.loads(x.text)
d = json.dumps(t)

