# python-pingmonitor

That's an IP ping monitor program it exports Up / Down results to excel (.xls) and send e-mail notifications to admins

Pingmonitor reads the ip addresses of network devices from ip.txt file then send a ping packet all the devices one by one and save the results to pingsonuclari.csv file.

At the second part it converts csv to excel and send the ping report to network admins or who ever your want.

Do not forget to allow mail relay from your mail server for your script.

Here is a screenshot below.

![alt text](https://github.com/goksinenki/python-ping-monitor/blob/master/pingmonitor.png)
INSTALLATION (Windows/Linux)

Installation

Just install the required modules/libraries to your python project directory if you do not have them

import smtplib
import xlsxwriter
import csv
import openpyxl

For example:

pip install openpyxl

Open ip.txt and replace hostnames and ip addresses with your network device information.
Open monitor.py and replace the required e-mail addresses with your information.

Then, execute monitor.py

That's all !
