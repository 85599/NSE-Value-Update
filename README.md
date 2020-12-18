NSE-Value-Update
About
Scrape everyday data from NSE Servers and append them into the excel file.
The data can now be worked upon easily by a common user.

Why ?
The NSE Website allows to view only one day historical data per time.
This poses a problem for the user to study all the values.
My project, appends the values at user specified location, thus able to view the values all together.

Working
Finds the Dates, whose NSE values are missing from the excel file.
For each Date (Skipping Public Holidays and Sat-Sun, when market is closed):
Scrapes, FIIs Participant Data.
Scrapes, DIIs Participant Data
Scrapes, NIFTY Index Data.
Appends them at right positions.
Working Model
NSE-Index-1

Next Update Log
Do, the mathematical calculations on above data and append them into the file.
More User Friendly and faster.
Google Sheets Integration.
More varied Data Addition into the file.
Contributions
If you have any method, to make the running time slower, you can Create a branch, with required Solution for further review.

Date Project Started
Thu Nov 22 15:18:29 2018
